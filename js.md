// learn.js
// JavaScript learning guide
//
// This file contains comments only. It is a study guide for JavaScript
// syntax and concepts, not a runnable program. Read the notes, then write
// your own JavaScript files separately.
// ------------------------------------------------------------------
// 1) JavaScript overview
// ------------------------------------------------------------------
// JavaScript is a dynamic, prototype-based language for the web and
// general scripting. It runs in browsers and on Node.js.
//
// A basic script can use statements, expressions, functions, and objects.
// JavaScript is untyped, so values can change type at runtime.
//
// Learn about values, expressions, and statement flow.
// ------------------------------------------------------------------
// 2) Variables and scope
// ------------------------------------------------------------------
// Use let, const, and var to declare variables.
//   let x = 5;
//   const name = 'Alice';
//   var count = 0;
//
// Learn the differences:
// - const is read-only after assignment.
// - let is block-scoped.
// - var is function-scoped and hoisted.
// ------------------------------------------------------------------
// 3) Data types and values
// ------------------------------------------------------------------
// JavaScript has primitive types:
//   number, string, boolean, null, undefined, symbol, bigint
//
// It also has objects and functions as first-class values.
// Learn how arrays and plain objects store data.
// ------------------------------------------------------------------
// 4) Operators and expressions
// ------------------------------------------------------------------
// Arithmetic: +, -, *, /, %, **
// Comparison: ===, !==, ==, !=, <, >, <=, >=
// Logical: &&, ||, !
// Learn the difference between strict (===) and loose (==) equality.
// Use template literals for string interpolation.
// ------------------------------------------------------------------
// 5) Control flow
// ------------------------------------------------------------------
// Use if / else and switch for branching.
// Use for, while, do...while for loops.
// Use break and continue to control loop behavior.
// Learn how truthy and falsy values affect conditionals.
// ------------------------------------------------------------------
// 6) Functions
// ------------------------------------------------------------------
// Define functions in several ways:
//   function sum(a, b) { return a + b; }
//   const add = function(a, b) { return a + b; };
//   const square = x => x * x;
//
// Learn function parameters, default values, rest parameters,
// and how `this` behaves differently for arrow functions.
// ------------------------------------------------------------------
// 7) Objects and arrays
// ------------------------------------------------------------------
// Create objects with literals:
//   const person = { name: 'Bob', age: 30 };
// Use arrays for ordered collections:
//   const items = [1, 2, 3];
// Learn property access, destructuring, and spread/rest syntax.
// ------------------------------------------------------------------
// 8) Prototypes and classes
// ------------------------------------------------------------------
// JavaScript objects inherit from prototypes.
// Use constructor functions or class syntax:
//   class Point {
//     constructor(x, y) {
//       this.x = x;
//       this.y = y;
//     }
//   }
// Learn prototype methods, inheritance, and the `new` keyword.
// ------------------------------------------------------------------
// 9) Asynchronous JavaScript
// ------------------------------------------------------------------
// Learn callbacks, Promises, async functions, and await.
// Example:
//   async function fetchData() {
//     const res = await fetch('/data');
//     return res.json();
//   }
// Understand event loops, microtasks, and concurrency behavior.
// ------------------------------------------------------------------
// 10) Modules and tooling
// ------------------------------------------------------------------
// JavaScript modules use import / export syntax in modern environments.
//   export function foo() {}
//   import { foo } from './module.js';
// Learn the difference between ESM and CommonJS.
// Use Node.js or browser tooling to run JavaScript files.
// ------------------------------------------------------------------
// 11) Exercises to practice JavaScript
// ------------------------------------------------------------------
// Write these exercises in separate .js files. Use this guide only as
// reference, and write the solutions yourself.
//
// Exercise 1: Hello and variables
// - Write a program that logs a greeting.
// - Declare variables using let and const.
//
// Exercise 2: Data types
// - Create values for number, string, boolean, null, and undefined.
// - Use typeof to inspect each value.
//
// Exercise 3: Expressions and operators
// - Write expressions with arithmetic and string concatenation.
// - Compare values using strict equality and loose equality.
//
// Exercise 4: Control flow
// - Write a function that uses if/else.
// - Write a loop that iterates over array items.
//
// Exercise 5: Functions
// - Write a normal function and an arrow function.
// - Use default parameters and rest parameters.
//
// Exercise 6: Objects and arrays
// - Create an object and an array.
// - Use destructuring to extract values.
//
// Exercise 7: Prototypes or classes
// - Create an object using a constructor function or class.
// - Add a method and call it.
//
// Exercise 8: Asynchronous JavaScript
// - Create a Promise and resolve it.
// - Write an async function that awaits a Promise.
//
// Exercise 9: Modules
// - Split code into two files and use import/export.
// - Run the code with Node.js or a browser bundler.
//
// Exercise 10: Survey common pitfalls
// - Demonstrate the difference between var and let.
// - Show how === differs from ==.
// ------------------------------------------------------------------
// 12) Tips for learning
// ------------------------------------------------------------------
// Run JavaScript code with Node.js or in a browser console.
// Start with small programs and gradually add features.
// Use browser dev tools or Node.js debugging to inspect runtime behavior.
// Practice writing plain JavaScript before moving to TypeScript.
// End of JavaScript learning guide.
