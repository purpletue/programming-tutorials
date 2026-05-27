// Go learning guide
//
// This file contains comments only. It is a study guide for Go
// syntax and concepts, not a runnable program. Read the notes, then write
// your own Go files separately.
// Ignore these, these are just for everything to not freak out.
package main

import "C"

func main() {}

// Okay, time for the actual learning guide.
// ------------------------------------------------------------------
// 1) Go overview
// ------------------------------------------------------------------
// Go is a statically typed language with built-in support for concurrency.
// It has a simple syntax and a fast compile/run cycle.
//
// A Go program starts with a package declaration and often has a main
// package with a main function.
//   package main
//
//   import "fmt"
//
//   func main() {
//     fmt.Println("Hello")
//   }
//
// Learn how Go organizes packages and the Go toolchain.
// ------------------------------------------------------------------
// 2) Types and variables
// ------------------------------------------------------------------
// Go has basic types: bool, string, int, int8, int16, int32, int64,
// uint, float32, float64, complex64, complex128, and byte/rune.
//
// Declare variables with var, short declaration, or const:
//   var x int = 5
//   y := 10
//   const name = "Alice"
//
// Learn zero values, pointers, and when to use typed vs untyped constants.
// ------------------------------------------------------------------
// 3) Control flow
// ------------------------------------------------------------------
// Use if, for, and switch for control flow.
// There is no while keyword; for is the only loop.
//
// Use defer to schedule cleanup actions.
// Learn how switch can replace multiple if/else branches.
// ------------------------------------------------------------------
// 4) Functions
// ------------------------------------------------------------------
// Functions are first-class values in Go.
//   func add(a int, b int) int {
//     return a + b
//   }
//
// Learn multiple return values, named results, variadic functions,
// and function literals.
// ------------------------------------------------------------------
// 5) Structs and methods
// ------------------------------------------------------------------
// Use structs to define composite data types.
//   type Point struct {
//     X int
//     Y int
//   }
//
// Add methods with receiver syntax:
//   func (p Point) Move(dx, dy int) Point {
//     p.X += dx
//     p.Y += dy
//     return p
//   }
//
// Learn pointer receivers versus value receivers.
// ------------------------------------------------------------------
// 6) Interfaces
// ------------------------------------------------------------------
// Interfaces define behavior by method sets.
//   type Stringer interface {
//     String() string
//   }
//
// Learn implicit implementation and how interfaces enable abstraction.
// ------------------------------------------------------------------
// 7) Error handling
// ------------------------------------------------------------------
// Go uses explicit error values instead of exceptions.
//   if err != nil {
//     return err
//   }
//
// Learn how to create custom error types and use fmt.Errorf.
// ------------------------------------------------------------------
// 8) Concurrency
// ------------------------------------------------------------------
// Go has goroutines and channels.
//   go doWork()
//   ch := make(chan int)
//
// Learn how to send and receive values, and how to avoid deadlocks.
// ------------------------------------------------------------------
// 9) Packages and tooling
// ------------------------------------------------------------------
// Go code is organized into packages.
// Use go run to execute and go build to compile binaries.
// Use go test for unit testing.
//
// Learn how modules work with go.mod and dependency management.
// ------------------------------------------------------------------
// 10) Exercises to practice Go
// ------------------------------------------------------------------
// Write these exercises in separate .go files. Use this guide only as
// reference, and write the solutions yourself.
//
// Exercise 1: Hello world
// - Write a main function that prints a greeting.
// - Use fmt.Println to display output.
//
// Exercise 2: Variables and types
// - Declare int, float64, string, and bool values.
// - Use type inference and explicit types.
//
// Exercise 3: Control flow
// - Write a function that uses if/else.
// - Use a for loop to iterate over a slice.
//
// Exercise 4: Functions
// - Write a function with multiple return values.
// - Write a variadic function.
//
// Exercise 5: Structs and methods
// - Define a struct with fields.
// - Add a method and call it.
//
// Exercise 6: Interfaces
// - Define an interface and implement it.
// - Write a function that accepts the interface type.
//
// Exercise 7: Error handling
// - Return an error from a function.
// - Handle the error in the caller.
//
// Exercise 8: Concurrency
// - Launch a goroutine.
// - Use a channel to synchronize data.
//
// Exercise 9: Modules and tooling
// - Create a go.mod file for a module.
// - Use go run or go build to execute code.
//
// Exercise 10: Go idioms
// - Use defer for cleanup.
// - Write code that favors clarity and simplicity.
// ------------------------------------------------------------------
// 11) Learning tips
// ------------------------------------------------------------------
// Use gofmt to format code consistently.
// Use go test to verify behavior.
// Keep functions small and readable.
// Practice writing idiomatic Go before adding abstractions.
// End of Go learning guide.
