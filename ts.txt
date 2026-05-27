// learn.ts
// TypeScript learning guide
//
// This file contains comments only. It is a study guide for TypeScript
// syntax and concepts, not a runnable program. Read the notes, then write
// your own TypeScript files separately.

// ------------------------------------------------------------------
// 1) TypeScript program structure
// ------------------------------------------------------------------
//
// TypeScript extends JavaScript with types.
// A typical file can contain imports, declarations, and code.
//
// You can write a simple program like:
//   function main() {
//       console.log('Hello');
//   }
//
// Learn how modules and exports work in TypeScript.

// ------------------------------------------------------------------
// 2) Types and annotations
// ------------------------------------------------------------------
//
// TypeScript is optionally typed. Common types:
//   number, string, boolean, any, unknown, void, null, undefined
//
// Add type annotations:
//   let x: number = 5;
//   const name: string = 'Alice';
//
// Learn the difference between explicit types and inferred types.

// ------------------------------------------------------------------
// 3) Interfaces and types
// ------------------------------------------------------------------
//
// Define object shapes with interfaces or type aliases:
//   interface Person { name: string; age: number; }
//   type Point = { x: number; y: number; };
//
// Learn how to use optional properties and readonly fields.

// ------------------------------------------------------------------
// 4) Functions and generics
// ------------------------------------------------------------------
//
// Type function parameters and return values:
//   function add(a: number, b: number): number {
//       return a + b;
//   }
//
// Learn generic functions:
//   function identity<T>(value: T): T {
//       return value;
//   }

// ------------------------------------------------------------------
// 5) Classes and objects
// ------------------------------------------------------------------
//
// TypeScript supports classes with typed members:
//   class Point {
//       constructor(public x: number, public y: number) {}
//   }
//
// Learn inheritance, access modifiers, and constructors.

// ------------------------------------------------------------------
// 6) Advanced types
// ------------------------------------------------------------------
//
// Learn union and intersection types:
//   type Result = string | number;
//   type AandB = A & B;
//
// Study mapped types, conditional types, and type guards.

// ------------------------------------------------------------------
// 7) Modules and imports
// ------------------------------------------------------------------
//
// Use ES module syntax:
//   import { something } from './module';
//   export function foo() {}
//
// Learn how default and named exports differ.

// ------------------------------------------------------------------
// 8) Tooling and compilation
// ------------------------------------------------------------------
//
// TypeScript is compiled with tsc.
// The tsconfig.json file controls the compiler settings.
//
// Learn how to compile a file and how to use `tsc --watch`.

// ------------------------------------------------------------------
// 9) Exercises to practice TypeScript
// ------------------------------------------------------------------
//
// Write these exercises in separate .ts files. Use this guide only as
// reference, and write the solutions yourself.
//
// Exercise 1: Hello and variables
// - Write a function that prints a greeting.
// - Declare variables with number and string types.
//
// Exercise 2: Function typing
// - Write a typed function that adds two numbers.
// - Write a function that returns a string message.
//
// Exercise 3: Interfaces
// - Define an interface for a person object.
// - Create a value that satisfies the interface.
//
// Exercise 4: Classes
// - Create a class with typed fields and a constructor.
// - Add a method that returns a description string.

// Exercise 5: Generics
// - Write a generic identity function.
// - Write a generic function that returns the first element of an array.

// Exercise 6: Union and intersection types
// - Define a union type for different input kinds.
// - Define an intersection type combining two object shapes.

// Exercise 7: Type guards
// - Write a function that narrows a union type.
// - Use `typeof` or `in` checks to distinguish types.

// Exercise 8: Modules
// - Split code into two modules.
// - Import and export functions between files.

// Exercise 9: tsconfig and compilation
// - Create a tsconfig.json file.
// - Compile a sample file with tsc.

// Exercise 10: Strict mode
// - Enable `strict` in tsconfig.
// - Fix any type errors that appear.

// ------------------------------------------------------------------
// 10) Learning tips
// ------------------------------------------------------------------
//
// Run `tsc` to compile TypeScript code.
// Use `npm install -g typescript` if tsc is not installed.
// Use editors with TypeScript support for autocomplete and errors.
// Keep declarations explicit when you are learning types.

// End of TypeScript learning guide.
