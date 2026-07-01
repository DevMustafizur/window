
## What is Window Object?
The window object is the global object in browser JavaScript.
It represents the current browser tab and provides access to global variables, functions, and browser APIs.

## Why does the Blink engine create the window object?
##### Blink engine creates the window object because:
The Blink engine creates the window object to provide JavaScript with a global browser environment.
The window object is the browser's global object. It exposes browser features and Web APIs—such as the DOM, timers, navigation, storage, and networking—to JavaScript, allowing JavaScript code to interact with web pages and browser functionality.

## What does Window Object do?
##### The window object is used for:
1. Global scope storage
var a = 10;
console.log(window.a); // 10

2. Browser APIs
window.document
window.location
window.history
setTimeout, setInterval

3. DOM access
document.getElementById("id")

4. Global functions & variables (browser only)
Global var becomes window.property
Global functions become window.functionName

## Role in Execution Context
When Global Execution Context (GEC) is created:
- Lexical Environment is created
- Variable Environment is created
- this is set to window (in browser)
