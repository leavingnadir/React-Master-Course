1.What are the three states of a Promise?
Pending
Fulfilled
Rejected

2.How does the async keyword affect a function's return value?
It makes the function return a Promise.

3.Explain the purpose of the await keyword.
It pauses the execution of an async function until the Promise is resolved.

4.What is a callback function and how is it used in asynchronous operations?

A callback function is a function passed as an argument to another function and is executed later.This commonly used in functions like setTimeout, event listeners.

5.Describe the role of the event loop in JavaScript.
The event loop manages asynchronous operations in Js and continuously checks the call stack and the callback queue.

6.Write a function called delayedGreeting that takes a name as an argument and logs a greeting message to the console after a 2-second delay using setTimeout. Use a callback function to achieve this.

function delayedGreeting(name, callback) {
    setTimeout(() => {
        callback(`Hello, ${name}!`);
    }, 2000);
}

delayedGreeting("Hirusha", (message) => console.log(message));