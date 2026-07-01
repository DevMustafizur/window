
## What is Window Object?
The window object is the global object in browser JavaScript.
It represents the current browser tab and provides access to global variables, functions, and browser APIs.

## Why Blink Engine creates Window Object?
##### Blink engine creates the window object because:
JavaScript needs a global environment to run JavaScript (V8) with browser features.
window exposes browser APIs like DOM, timers, and navigation etc.
It acts as a bridge between JS and browser

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
