// learn.rs
// Rust learning guide
//
// This file contains comments only. It is meant as a study guide
// for Rust syntax and concepts, not a runnable program.
// Read the notes, then write your own Rust files separately.

// ------------------------------------------------------------------
// 1) Rust program structure
// ------------------------------------------------------------------
//
// A Rust program usually starts with a main function:
//   fn main() {
//       // program entry
//   }
//
// Use modules, functions, and imports to organize code.
// Learn how Cargo projects are structured when you are ready.

// ------------------------------------------------------------------
// 2) Variables and mutability
// ------------------------------------------------------------------
//
// Rust has immutable variables by default:
//   let x = 5;
//
// Make variables mutable with `mut`:
//   let mut x = 5;
//
// Understand shadowing:
//   let x = 5;
//   let x = x + 1;
//
// Learn how Rust enforces safety through ownership and borrowing.

// ------------------------------------------------------------------
// 3) Data types and casting
// ------------------------------------------------------------------
//
// Common primitive types:
//   i32, i64, u32, u64, f32, f64, bool, char
//
// Rust also has tuples and arrays:
//   let tup: (i32, f64, char) = (1, 2.0, 'a');
//   let arr = [1, 2, 3];
//
// Learn how to explicitly cast between numeric types with `as`.

// ------------------------------------------------------------------
// 4) Expressions and operators
// ------------------------------------------------------------------
//
// Rust uses expressions instead of statements in many places.
// Example:
//   let y = {
//       let x = 3;
//       x + 1
//   };
//
// Learn arithmetic operators and comparison operators.
// Practice using `if` as an expression.

// ------------------------------------------------------------------
// 5) Control flow
// ------------------------------------------------------------------
//
// Rust supports `if`, `else`, `loop`, `while`, and `for`.
// Example:
//   for i in 1..=5 {
//       println!("{}", i);
//   }
//
// Learn the difference between `..` and `..=` ranges.
// Practice using `match` for powerful pattern matching.

// ------------------------------------------------------------------
// 6) Ownership and borrowing
// ------------------------------------------------------------------
//
// Ownership is a core Rust concept.
// A value has one owner, and it is dropped when the owner goes out of scope.
// Example:
//   let s = String::from("hello");
//
// Borrow values with `&` and mutable borrow with `&mut`.
// Study how the borrow checker prevents invalid references.

// ------------------------------------------------------------------
// 7) Functions
// ------------------------------------------------------------------
//
// Functions are declared with `fn`.
// Example:
//   fn add(a: i32, b: i32) -> i32 {
//       a + b
//   }
//
// Learn how parameters and return types are specified.
// Practice passing ownership and borrowing across functions.

// ------------------------------------------------------------------
// 8) Structs and enums
// ------------------------------------------------------------------
//
// Define custom data types with structs and enums.
// Example struct:
//   struct Point {
//       x: f64,
//       y: f64,
//   }
//
// Example enum:
//   enum Color {
//       Red,
//       Green,
//       Blue,
//   }
//
// Learn how to use pattern matching with enums.

// ------------------------------------------------------------------
// 9) Error handling
// ------------------------------------------------------------------
//
// Rust has `Result` and `Option` types for error handling.
// Use `match`, `if let`, and the `?` operator.
//
// Learn the difference between recoverable and unrecoverable errors.
// Prefer `Result` for functions that may fail.

// ------------------------------------------------------------------
// 10) Exercises to practice Rust
// ------------------------------------------------------------------
//
// These exercises should be implemented in separate Rust files.
// Use this guide as a reference, but write the code yourself.
//
// Exercise 1: Basics
// - Write a program that prints a greeting.
// - Declare mutable and immutable variables.
//
// Exercise 2: Arithmetic
// - Read two numbers from the user.
// - Compute and print the sum, difference, product, and quotient.
//
// Exercise 3: Control flow
// - Use `if` to classify a number as positive, negative, or zero.
// - Use `match` to map a number to a word.
//
// Exercise 4: Loops and ranges
// - Use a `for` loop with a range to print numbers 1 through 10.
// - Use `while` to compute the factorial of 5.
//
// Exercise 5: Functions
// - Write a function that adds two `i32` values.
// - Write a function that returns the larger of two values.
//
// Exercise 6: Ownership and borrowing
// - Write a function that takes a `String` by reference.
// - Write another function that returns a `String`.
//
// Exercise 7: Structs and enums
// - Define a `struct` for a point.
// - Define an `enum` for shapes or colors.
// - Use pattern matching to handle enum values.

// Exercise 8: Collections
// - Create a `Vec<i32>` and push values into it.
// - Iterate over the vector and compute the sum.
//
// Exercise 9: Error handling
// - Write a function that returns `Result<i32, String>`.
// - Call it and handle both success and failure.

// Exercise 10: Cargo practice
// - Create a new Cargo project with `cargo new`.
// - Add a small program and run it with `cargo run`.

// ------------------------------------------------------------------
// 11) Learning tips
// ------------------------------------------------------------------
//
// Use `cargo build` and `cargo run` for project development.
// Keep your code small and compile often.
// Read compiler messages carefully and fix errors one at a time.
// Learn by writing and testing small programs.

// End of Rust learning guide.
