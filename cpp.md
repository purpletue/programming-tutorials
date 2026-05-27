// learn.cpp
// C++ learning guide
//
// This file contains comments only. It is meant as a study guide,
// not as a runnable program. Read the notes carefully and then write
// your own C++ code separately.
//
// Use this file as a reference while you build your language catalog.

// ------------------------------------------------------------------
// 1) C++ program structure
// ------------------------------------------------------------------
//
// A C++ source file usually includes headers and defines functions.
// The entry point is typically:
//   int main() {
//       return 0;
//   }
//
// Learn how headers, namespaces, and declarations organize code.

// ------------------------------------------------------------------
// 2) Types and variables
// ------------------------------------------------------------------
//
// C++ supports built-in types such as:
//   int, long, float, double, char, bool
//
// It also supports type inference with auto:
//   auto value = 42;
//
// Understand the difference between value types and pointers/references.

// ------------------------------------------------------------------
// 3) Expressions and operators
// ------------------------------------------------------------------
//
// Common operators include:
//   +, -, *, /, %, ++, --
//
// Comparison operators:
//   ==, !=, <, >, <=, >=
//
// Logical operators:
//   &&, ||, !
//
// Learn operator precedence and how to use parentheses for clarity.

// ------------------------------------------------------------------
// 4) Control flow
// ------------------------------------------------------------------
//
// C++ uses if/else, switch, for, while, and do/while.
// Also learn ranged-for loops:
//   for (auto item : collection) {
//       ...
//   }
//
// Practice each form and understand when to use braces.

// ------------------------------------------------------------------
// 5) Functions
// ------------------------------------------------------------------
//
// Functions are declared with a return type, name, and parameters.
// Example:
//   int add(int a, int b) {
//       return a + b;
//   }
//
// Learn passing by value, by reference, and by pointer.
// Study function overloading and default arguments.

// ------------------------------------------------------------------
// 6) Input/output
// ------------------------------------------------------------------
//
// C++ basic I/O uses iostream:
//   std::cout << "text" << std::endl;
//   std::cin >> value;
//
// Learn how to handle input and output safely and how to format text.

// ------------------------------------------------------------------
// 7) Arrays, vectors, and strings
// ------------------------------------------------------------------
//
// C++ has built-in arrays and standard containers like std::vector.
// Example:
//   std::vector<int> nums;
//
// Strings are typically std::string.
// Learn indexing, iteration, and container operations.

// ------------------------------------------------------------------
// 8) Object-oriented programming
// ------------------------------------------------------------------
//
// C++ supports classes, structs, constructors, and destructors.
// Learn about encapsulation and member functions.
//
// Example features:
//   class Point {
//   public:
//       int x, y;
//       Point(int x, int y) : x(x), y(y) {}
//   };
//
// Practice writing simple classes and using them.

// ------------------------------------------------------------------
// 9) Memory and resource management
// ------------------------------------------------------------------
//
// C++ uses stack allocation and dynamic allocation with new/delete.
// Prefer RAII and smart pointers like std::unique_ptr and std::shared_ptr.
//
// Learn to manage resources safely and avoid leaks.

// ------------------------------------------------------------------
// 10) Exercises to practice C++
// ------------------------------------------------------------------
//
// These exercises are for you to implement separately.
// Use the notes above, but write the code yourself.
//
// Exercise 1: Hello and variables
// - Write a program that asks for a name.
// - Print a greeting using std::cout.
//
// Exercise 2: Arithmetic
// - Read two integers from the user.
// - Print their sum, difference, product, and quotient.
//
// Exercise 3: Conditionals
// - Ask the user for a number.
// - Print whether it is positive, negative, or zero.
// - Print whether it is even or odd.
//
// Exercise 4: Loops
// - Use a for loop to print numbers 1 through 10.
// - Use a while loop to compute the factorial of 6.
// - Use a ranged-for loop over a vector.
//
// Exercise 5: Functions
// - Write a function that returns the maximum of two ints.
// - Write a function that swaps two integers using references.
//
// Exercise 6: Vectors and strings
// - Create a std::vector<int> and fill it with user values.
// - Compute and print the sum and average.
// - Read a std::string and print its length.
//
// Exercise 7: Classes
// - Define a simple class with properties and a constructor.
// - Create an object and print its members.
//
// Exercise 8: Pointers and references
// - Write code that uses pointers and references.
// - Understand the difference between address-of and dereference.
//
// Exercise 9: File I/O
// - Read from a text file using std::ifstream.
// - Write output to a file using std::ofstream.
// - Handle failure to open the file.
//
// Exercise 10: Smart pointers
// - Use std::unique_ptr to manage dynamic memory.
// - Practice passing ownership and resetting pointers.

// ------------------------------------------------------------------
// 11) Learning tips
// ------------------------------------------------------------------
//
// Compile often with g++ -Wall -Wextra -std=c++17.
// Use consistent formatting and clear names.
// Start with small examples and grow complexity.
// Read compiler warnings and fix them.

// End of C++ learning guide.
