// learn.cs
// C# learning guide
//
// This file contains comments only. It serves as a study guide for C#
// concepts and exercises, not as a runnable program. Read the notes,
// then write your own C# code separately.
//
// Use this file as a reference while you build your language catalog.

// ------------------------------------------------------------------
// 1) C# program structure
// ------------------------------------------------------------------
//
// A C# program is organized into namespaces, classes, and methods.
// The entry point is typically a static Main method.
//
// Example structure:
//   using System;
//
//   namespace MyApp {
//       class Program {
//           static void Main(string[] args) {
//               // program start
//           }
//       }
//   }
//
// Learn how classes and namespaces group code.

// ------------------------------------------------------------------
// 2) Types and variables
// ------------------------------------------------------------------
//
// C# is statically typed. Common types include:
//   int, long, float, double, decimal, bool, char, string
//
// You can declare variables with:
//   int count = 0;
//   string name = "Alice";
//
// Learn the difference between value types and reference types.
// Also study nullable types, e.g. int? and string?.

// ------------------------------------------------------------------
// 3) Expressions and operators
// ------------------------------------------------------------------
//
// C# supports arithmetic operators:
//   +, -, *, /, %, ++, --
//
// And relational/logical operators:
//   ==, !=, <, >, <=, >=, &&, ||, !
//
// Learn operator precedence and use parentheses when needed.
// Practice string concatenation and formatting.

// ------------------------------------------------------------------
// 4) Control flow
// ------------------------------------------------------------------
//
// C# uses if/else, switch, for, foreach, while, and do/while.
// Syntax examples:
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
//   foreach (var item in collection) {
//       ...
//   }
//
// Study when to use each loop form and how to avoid infinite loops.

// ------------------------------------------------------------------
// 5) Methods and parameters
// ------------------------------------------------------------------
//
// Methods are defined inside classes and can return values.
// Example:
//   static int Add(int a, int b) {
//       return a + b;
//   }
//
// Learn how to pass arguments, use return values, and overload methods.
// Practice writing methods that perform specific tasks.

// ------------------------------------------------------------------
// 6) Collections and arrays
// ------------------------------------------------------------------
//
// C# has arrays and collections like List<T>.
// Example array declaration:
//   int[] values = new int[5];
//
// Example list declaration:
//   var names = new List<string>();
//
// Learn how to index arrays, iterate collections, and use collection methods.

// ------------------------------------------------------------------
// 7) Object-oriented basics
// ------------------------------------------------------------------
//
// C# is object-oriented. Learn about:
//   classes, objects, fields, properties, methods
//   inheritance, encapsulation, polymorphism
//
// Practice defining simple classes and using constructors.
// Learn the difference between public, private, and protected members.

// ------------------------------------------------------------------
// 8) Error handling
// ------------------------------------------------------------------
//
// C# uses try/catch/finally for exceptions.
// Example structure:
//   try {
//       // risky code
//   } catch (Exception ex) {
//       // handle error
//   } finally {
//       // cleanup
//   }
//
// Learn how to catch specific exceptions and avoid swallowing errors.

// ------------------------------------------------------------------
// 9) Input/output and debugging
// ------------------------------------------------------------------
//
// Use Console.WriteLine and Console.ReadLine for console I/O.
// Learn how to parse input using int.TryParse and other type parsers.
//
// Practice reading user input safely and printing helpful messages.

// ------------------------------------------------------------------
// 10) Exercises to practice C#
// ------------------------------------------------------------------
//
// These exercises should be implemented in separate C# files.
// Do not copy full solutions from the guide. Write your own code.
//
// Exercise 1: Hello and variables
// - Write a program that asks for a name.
// - Print a greeting using the entered name.
// - Use string interpolation.
//
// Exercise 2: Arithmetic
// - Read two numbers from the user.
// - Print their sum, difference, product, and quotient.
// - Use numeric parsing with int.TryParse or double.TryParse.
//
// Exercise 3: Conditionals
// - Ask the user for a number.
// - Print whether it is positive, negative, or zero.
// - Print whether it is even or odd.
//
// Exercise 4: Loops
// - Use a for loop to print numbers 1 through 10.
// - Use a while loop to compute and print the factorial of 6.
// - Use foreach to iterate a collection of strings.
//
// Exercise 5: Methods
// - Write a method that returns the maximum of two integers.
// - Write another method that returns the minimum.
// - Call both methods from Main.
//
// Exercise 6: Arrays and lists
// - Create an array of 5 integers.
// - Fill it with values and print the sum.
// - Repeat the exercise with a List<int>.
//
// Exercise 7: Classes
// - Define a simple class with properties and a constructor.
// - Create an instance and print its values.
//
// Exercise 8: Exception handling
// - Write code that attempts to parse user input.
// - Use try/catch to handle invalid input.
// - Print a friendly error message.
//
// Exercise 9: LINQ and collections
// - Create a list of numbers or strings.
// - Use LINQ methods like Where and Select.
// - Print the filtered or transformed results.
//
// Exercise 10: File I/O
// - Write text to a file.
// - Read it back and print it to the console.
// - Handle exceptions when the file cannot be accessed.

// ------------------------------------------------------------------
// 11) Learning tips
// ------------------------------------------------------------------
//
// Use dotnet build or csc to compile your code.
// Use consistent formatting and meaningful names.
// Start with small examples and build up complexity.
// Read compiler warnings, and fix issues early.

// End of C# learning guide.
