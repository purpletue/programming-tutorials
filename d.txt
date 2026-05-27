// learn.d
// D learning guide
//
// This file contains comments only. It is a study guide for D syntax
// and concepts, not a runnable program. Read the notes, then write your
// own D code separately.

// ------------------------------------------------------------------
// 1) D program structure
// ------------------------------------------------------------------
//
// A D program typically starts with import statements and a main function:
//   import std.stdio;
//
//   void main() {
//       // program entry
//   }
//
// Learn how modules and imports organize code.

// ------------------------------------------------------------------
// 2) Variables and types
// ------------------------------------------------------------------
//
// D is statically typed. Common types include:
//   int, long, float, double, bool, char, string
//
// Declare variables with:
//   int x = 5;
//   auto y = 3.14;
//
// Learn the difference between static and inferred typing.

// ------------------------------------------------------------------
// 3) Expressions and operators
// ------------------------------------------------------------------
//
// D supports arithmetic operators:
//   +, -, *, /, %, ++, --
//
// Comparison operators:
//   ==, !=, <, >, <=, >=
//
// Logical operators:
//   &&, ||, !
//
// Learn operator precedence and how to use parentheses.

// ------------------------------------------------------------------
// 4) Control flow
// ------------------------------------------------------------------
//
// D uses if/else, switch, for, while, and do/while.
// Example:
//   if (condition) {
//       ...
//   } else {
//       ...
//   }
//
//   for (int i = 0; i < n; i++) {
//       ...
//   }
//
// Practice controlling loops and using break/continue.

// ------------------------------------------------------------------
// 5) Functions
// ------------------------------------------------------------------
//
// Functions are declared with a return type and parameters:
//   int add(int a, int b) {
//       return a + b;
//   }
//
// Learn how to pass arguments by value and return results.
// Practice using void functions as well.

// ------------------------------------------------------------------
// 6) Arrays and ranges
// ------------------------------------------------------------------
//
// D has static arrays, dynamic arrays, and ranges.
// Example dynamic array:
//   int[] nums = [1, 2, 3];
//
// Learn how to index arrays and iterate with foreach.
// Study how ranges work with std.range if you want advanced iteration.

// ------------------------------------------------------------------
// 7) Strings
// ------------------------------------------------------------------
//
// Strings are immutable arrays of chars:
//   string s = "hello";
//
// Learn basic string operations and how to use std.stdio.writefln.
// Practice formatting and concatenation.

// ------------------------------------------------------------------
// 8) Modules and imports
// ------------------------------------------------------------------
//
// Use modules to organize code and import them with import statements.
// Example:
//   import std.stdio;
//
// Learn how module names map to file structure.

// ------------------------------------------------------------------
// 9) Memory and safety
// ------------------------------------------------------------------
//
// D supports both safe and unsafe code.
// Learn the basics first, then explore @safe and @trusted annotations.
//
// Practice writing memory-safe code and avoid manual pointer misuse.

// ------------------------------------------------------------------
// 10) Exercises to practice D
// ------------------------------------------------------------------
//
// These exercises should be implemented in separate D files.
// Use this guide as a reference, but write the code yourself.
//
// Exercise 1: Hello and variables
// - Write a program that prints a greeting.
// - Declare a few variables and print their values.
//
// Exercise 2: Arithmetic
// - Read two numbers from the user.
// - Print their sum, difference, product, and quotient.
//
// Exercise 3: Conditionals
// - Ask the user for a number.
// - Print whether it is positive, negative, or zero.
//
// Exercise 4: Loops
// - Use a for loop to print numbers 1 through 10.
// - Use a while loop to compute factorial of 5.

// Exercise 5: Functions
// - Write a function that returns the maximum of two ints.
// - Write a function that swaps two values by reference.

// Exercise 6: Arrays and ranges
// - Create an int[] array and fill it with values.
// - Iterate through it with foreach and compute the sum.

// Exercise 7: Strings
// - Read a string from the user.
// - Print its length and a formatted message.

// Exercise 8: Modules
// - Split code into two modules.
// - Import one module from the other.

// Exercise 9: Error handling
// - Use try/catch to handle possible runtime errors.
// - Print an error message if something goes wrong.

// Exercise 10: Build and run
// - Compile your program with dmd or ldc.
// - Run the executable and verify the output.

// ------------------------------------------------------------------
// 11) Learning tips
// ------------------------------------------------------------------
//
// Compile with dmd learn.d or ldc2 learn.d.
// Start small and test often.
// Read compiler messages carefully and fix issues step by step.
//
// End of D learning guide.
