JavaScript Basics Practice

A collection of beginner-friendly JavaScript examples and notes to practice fundamental concepts such as console logging, loops, DOM manipulation, and event handling.

📌 Topics Covered

Introduction to JavaScript

History: Created by Brendan Eich in 1995.

ECMAScript versions: ES5, ES6, ES2016, ES2017, etc.

Browser Console Basics

Open console: Ctrl + Shift + I → Console tab.

Example:

console.log("hi shafin");


✅ Output: hi shafin

Loops in JavaScript

for (var i = 0; i < 10; i++) {
    console.log(i);
}


✅ Output: 0 1 2 3 4 5 6 7 8 9

DOM Manipulation

document.getElementsByTagName("h1")[0].style.color = "#ff0000";


✅ Changes the first <h1> heading color to red.

Event Handling (Click Example)

document.body.addEventListener('click', function () {
    var myParent = document.getElementsByTagName("h1")[0]; 
    var myImage = document.createElement("img");
    myImage.src = 'https://thecatapi.com/api/images/get?format=src&type=gif';
    myParent.appendChild(myImage);
    myImage.style.marginLeft = "160px";
});


✅ Adds a random cat GIF when clicking on the page.
