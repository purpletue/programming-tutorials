/* learn.c
 * C learning guide
 *
 * This file contains comments only. It is meant as a study guide,
 * not as a working C program. Read the syntax notes, then write
 * your own code separately to practice.
 *
 * Use this file as a reference while you learn C concepts.
 */

/* ------------------------------------------------------------------
 * 1) C program structure
 * ------------------------------------------------------------------
 *
 * A C program typically has:
 *   - #include directives for headers
 *   - function declarations and definitions
 *   - a main() function as the program entry point
 *
 * The simplest program is:
 *   int main(void) {
 *       return 0;
 *   }
 *
 * Study how main returns an exit code to the operating system.
 */

/* ------------------------------------------------------------------
 * 2) Variables and types
 * ------------------------------------------------------------------
 *
 * C is statically typed. Common types include:
 *   int, long, float, double, char
 *
 * Use declarations like:
 *   int count;
 *   double rate = 3.14;
 *
 * Understand the difference between signed and unsigned types.
 * Learn how to initialize variables and how scope works.
 */

/* ------------------------------------------------------------------
 * 3) Expressions and operators
 * ------------------------------------------------------------------
 *
 * C expressions use operators such as:
 *   +, -, *, /, %, ++, --
 *
 * Learn operator precedence and when to use parentheses.
 * Practice integer arithmetic and floating-point arithmetic.
 *
 * Also study relational operators:
 *   ==, !=, <, >, <=, >=
 * and logical operators:
 *   &&, ||, !
 */

/* ------------------------------------------------------------------
 * 4) Control flow
 * ------------------------------------------------------------------
 *
 * C uses if/else, switch, for, while, and do/while.
 * Learn the syntax for each form and how to use braces.
 *
 * Example structures:
 *   if (condition) {
 *       ...
 *   } else {
 *       ...
 *   }
 *
 *   for (int i = 0; i < n; i++) {
 *       ...
 *   }
 *
 * Study how loop conditions and increments work.
 */

/* ------------------------------------------------------------------
 * 5) Functions
 * ------------------------------------------------------------------
 *
 * Functions are defined with return type, name, and parameters.
 * Example:
 *   int add(int a, int b) {
 *       return a + b;
 *   }
 *
 * Learn how to declare functions before using them,
 * pass arguments by value, and return values.
 *
 * Also study the difference between function declaration and definition.
 */

/* ------------------------------------------------------------------
 * 6) Arrays and strings
 * ------------------------------------------------------------------
 *
 * Arrays are fixed-size sequences of elements:
 *   int numbers[5];
 *
 * Strings are arrays of char terminated by '\0'.
 * Use string literals and functions from <string.h>.
 *
 * Learn how to index arrays, iterate them, and avoid out-of-bounds access.
 */

/* ------------------------------------------------------------------
 * 7) Pointers
 * ------------------------------------------------------------------
 *
 * Pointers hold memory addresses.
 * Example:
 *   int x = 5;
 *   int *p = &x;
 *
 * Learn dereferencing with * and the difference between pointer and value.
 * Study pointer arithmetic and passing pointers to functions.
 */

/* ------------------------------------------------------------------
 * 8) Input and output
 * ------------------------------------------------------------------
 *
 * C uses printf and scanf for console I/O.
 * Study format specifiers like %d, %f, %c, %s.
 *
 * Learn how to check scanf return values and avoid buffer overflows.
 */

/* ------------------------------------------------------------------
 * 9) Memory and safety
 * ------------------------------------------------------------------
 *
 * Understand automatic vs static vs dynamic storage.
 * Learn malloc/free for dynamic memory.
 *
 * Practice checking for NULL and freeing memory.
 * Avoid common errors like use-after-free and buffer overflow.
 */

/* ------------------------------------------------------------------
 * 10) Exercises to practice C
 * ------------------------------------------------------------------
 *
 * These exercises are for you to implement in separate source files.
 * Use the notes above as guidance, but write the code yourself.
 *
 * Exercise 1: Basic arithmetic
 * - Write a program that reads two integers from the user.
 * - Print their sum, difference, product, quotient, and remainder.
 * - Use printf and scanf safely.
 *
 * Exercise 2: Conditionals
 * - Read a number from the user.
 * - Print whether it is positive, negative, or zero.
 * - Print whether it is even or odd.
 *
 * Exercise 3: Loops
 * - Use a for loop to print the numbers 1 through 10.
 * - Use a while loop to compute and print the factorial of 6.
 *
 * Exercise 4: Functions
 * - Write a function int max(int a, int b).
 * - Call it from main and print the result.
 * - Write another function for min.
 *
 * Exercise 5: Arrays
 * - Create an array of 5 integers.
 * - Fill it with values from the user.
 * - Print the array sum and average.
 *
 * Exercise 6: Strings
 * - Read a short string from the user.
 * - Print its length and a copy of the string.
 * - Use functions from <string.h>.
 *
 * Exercise 7: Pointers
 * - Write a function that swaps two integers using pointers.
 * - Call it from main and verify the values change.
 *
 * Exercise 8: Dynamic memory
 * - Allocate an array of ints using malloc.
 * - Populate it with values and print them.
 * - Free the memory before exiting.
 *
 * Exercise 9: Structs
 * - Define a struct for a point with x and y coordinates.
 * - Write a function that computes the distance between two points.
 *
 * Exercise 10: Error checking
 * - Write a program that opens a file.
 * - Check for failure and print an error message if the file cannot be opened.
 */

/* ------------------------------------------------------------------
 * 11) Learning tips
 * ------------------------------------------------------------------
 *
 * Compile often with gcc -Wall -Wextra -std=c11.
 * Use clang-format or consistent indentation.
 * Read compiler warnings and fix them.
 * Try small functions first, then build up.
 *
 * End of C learning guide.
 */
