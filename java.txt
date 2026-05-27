// learn.java
// Java learning guide
//
// This file contains comments only. It is a study guide for Java
// syntax and concepts, not a runnable program. Read the notes, then write
// your own Java files separately.
// ------------------------------------------------------------------
// 1) Java overview
// ------------------------------------------------------------------
// Java is a statically typed, object-oriented language that runs on the JVM.
// It uses classes, methods, and strong compile-time checking.
//
// A basic program defines a class with a main method:
//   public class Main {
//     public static void main(String[] args) {
//       System.out.println("Hello");
//     }
//   }
//
// Learn about the Java classpath, compilation, and JVM execution.
// ------------------------------------------------------------------
// 2) Types and variables
// ------------------------------------------------------------------
// Java has primitive types and object types.
// Primitives include: byte, short, int, long, float, double, boolean, char.
// Object types include classes, interfaces, arrays, and enums.
//
// Declare variables with explicit types:
//   int count = 10;
//   String name = "Alice";
//
// Learn about local variables, fields, and final modifiers.
// ------------------------------------------------------------------
// 3) Operators and expressions
// ------------------------------------------------------------------
// Use arithmetic operators: +, -, *, /, %, ++, --.
// Use comparison operators: ==, !=, <, >, <=, >=.
// Use logical operators: &&, ||, !.
//
// Learn the difference between primitive equality and object equality
// with .equals().
// ------------------------------------------------------------------
// 4) Control flow
// ------------------------------------------------------------------
// Use if / else and switch statements for branching.
// Use for, while, and do/while loops for repetition.
// Use break and continue inside loops.
//
// Learn how switch works with int, enum, String, and pattern matching
// in newer Java versions.
// ------------------------------------------------------------------
// 5) Methods and parameters
// ------------------------------------------------------------------
// Define methods inside classes:
//   public static int add(int a, int b) {
//     return a + b;
//   }
//
// Learn method overloading, return types, and access modifiers
// such as public, private, and protected.
// ------------------------------------------------------------------
// 6) Classes and objects
// ------------------------------------------------------------------
// Java is class-based. Define classes with fields, constructors, and methods.
//   public class Person {
//     private String name;
//     public Person(String name) { this.name = name; }
//   }
//
// Learn about encapsulation, constructors, and object creation with new.
// ------------------------------------------------------------------
// 7) Inheritance and interfaces
// ------------------------------------------------------------------
// Use extends for class inheritance and implements for interfaces.
//   class Animal { void speak() {} }
//   class Dog extends Animal {}
//
// Learn abstract classes, interfaces, and when to use each.
// ------------------------------------------------------------------
// 8) Collections and generics
// ------------------------------------------------------------------
// Use Java collections such as List, Set, and Map.
//   List<String> names = new ArrayList<>();
//
// Learn generics, type parameters, and bounded type arguments.
// ------------------------------------------------------------------
// 9) Exceptions and error handling
// ------------------------------------------------------------------
// Use try / catch / finally for exception handling.
//   try {
//     // code
//   } catch (IOException e) {
//     e.printStackTrace();
//   }
//
// Learn checked exceptions vs unchecked exceptions.
// ------------------------------------------------------------------
// 10) Java modules and packaging
// ------------------------------------------------------------------
// Use packages to organize classes.
//   package com.example;
//
// Learn how to compile with javac and run with java.
// Use JAR files to package applications and libraries.
// ------------------------------------------------------------------
// 11) Exercises to practice Java
// ------------------------------------------------------------------
// Write these exercises in separate .java files. Use this guide only as
// reference, and write the solutions yourself.
//
// Exercise 1: Hello world
// - Create a class with a main method.
// - Print a greeting to the console.
//
// Exercise 2: Variables and types
// - Declare primitive variables: int, double, boolean, char.
// - Declare a String value.
//
// Exercise 3: Control flow
// - Write a method that uses if/else.
// - Use a loop to process an array.
//
// Exercise 4: Methods
// - Write a static method that returns a value.
// - Write an instance method that uses object fields.
//
// Exercise 5: Classes
// - Define a class with private fields and a constructor.
// - Add a method that returns a formatted description.
//
// Exercise 6: Inheritance and interfaces
// - Create a base class and a subclass.
// - Define an interface and implement it in a class.
//
// Exercise 7: Collections and generics
// - Use a List<String> or Map<String, Integer>.
// - Write a generic method or class.
//
// Exercise 8: Exceptions
// - Throw and catch an exception.
// - Use try/finally or try-with-resources.
//
// Exercise 9: Packages and compilation
// - Place classes in a package.
// - Compile and run code with javac and java.
//
// Exercise 10: Java runtime behavior
// - Demonstrate String immutability.
// - Compare object references using == and .equals().
// ------------------------------------------------------------------
// 12) Tips for learning
// ------------------------------------------------------------------
// Use the Java compiler (javac) and Java runtime (java).
// Read API docs for java.lang and java.util.
// Start with simple classes and gradually add structure.
// Practice writing plain Java before using frameworks.
// End of Java learning guide.
