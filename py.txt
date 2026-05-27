# learn.py
# Python learning guide
#
# This file contains comments only. It is a study guide for Python syntax
# and concepts, not a runnable program. Read the notes, then write your
# own Python scripts separately.

# ------------------------------------------------------------------
# 1) Python program structure
# ------------------------------------------------------------------
#
# Python files are executed from top to bottom.
# A simple script can just be a sequence of statements.
#
# You can define a main function and call it like:
#   def main():
#       pass
#
#   if __name__ == '__main__':
#       main()
#
# Learn how modules and scripts are organized.

# ------------------------------------------------------------------
# 2) Variables and types
# ------------------------------------------------------------------
#
# Python is dynamically typed.
# Common built-in types include:
#   int, float, bool, str, list, tuple, dict, set
#
# Assign variables with =:
#   x = 5
#   name = 'Alice'
#
# Learn how Python infers types and how to use variables safely.

# ------------------------------------------------------------------
# 3) Expressions and operators
# ------------------------------------------------------------------
#
# Python supports arithmetic operators:
#   +, -, *, /, //, %, **
#
# Comparison operators:
#   ==, !=, <, >, <=, >=
#
# Logical operators:
#   and, or, not
#
# Learn operator precedence and how to use parentheses.

# ------------------------------------------------------------------
# 4) Control flow
# ------------------------------------------------------------------
#
# Python uses if, elif, else, while, and for.
# Indentation defines blocks.
#
# Example:
#   if condition:
#       ...
#   elif other:
#       ...
#   else:
#       ...
#
#   for i in range(5):
#       ...
#
#   while condition:
#       ...
#
# Practice loop control and break/continue.

# ------------------------------------------------------------------
# 5) Functions
# ------------------------------------------------------------------
#
# Define functions with def:
#   def add(a, b):
#       return a + b
#
# Learn how to use positional arguments, default values, and keyword args.
# Practice returning values and multiple results.

# ------------------------------------------------------------------
# 6) Collections
# ------------------------------------------------------------------
#
# Python has lists, tuples, dicts, and sets.
# Examples:
#   nums = [1, 2, 3]
#   person = {'name': 'Alice', 'age': 30}
#
# Learn how to index, iterate, and manipulate collections.

# ------------------------------------------------------------------
# 7) Strings
# ------------------------------------------------------------------
#
# Strings are immutable.
# Use f-strings or format() for interpolation.
#
# Example:
#   message = f'Hello, {name}'
#
# Learn common string methods and slicing.

# ------------------------------------------------------------------
# 8) Input/output and files
# ------------------------------------------------------------------
#
# Use input() to read from the user.
# Use print() for output.
# Use with open(...) as f: to read and write files.
#
# Learn to handle file paths and exceptions when files are missing.

# ------------------------------------------------------------------
# 9) Error handling
# ------------------------------------------------------------------
#
# Use try/except/finally to handle errors.
# Example:
#   try:
#       ...
#   except ValueError:
#       ...
#   finally:
#       ...
#
# Learn to catch specific exceptions and avoid broad except clauses.

# ------------------------------------------------------------------
# 10) Exercises to practice Python
# ------------------------------------------------------------------
#
# These exercises should be written in separate Python files.
# Use this guide as a reference, but implement the solutions yourself.
#
# Exercise 1: Hello and variables
# - Write a script that asks for a name.
# - Print a greeting using an f-string.
#
# Exercise 2: Arithmetic
# - Read two numbers from the user.
# - Print their sum, difference, product, and quotient.
#
# Exercise 3: Conditionals
# - Ask the user for a number.
# - Print whether it is positive, negative, or zero.
# - Print whether it is even or odd.
#
# Exercise 4: Loops
# - Use a for loop to print numbers 1 through 10.
# - Use a while loop to compute factorial of 6.
#
# Exercise 5: Functions
# - Write a function that returns the max of two numbers.
# - Write a function that swaps two variables and returns them.
#
# Exercise 6: Lists and dictionaries
# - Create a list of values and print each item.
# - Create a dict with keys and values, then print its items.
#
# Exercise 7: Strings
# - Read a string from the user.
# - Print its length, uppercase version, and substring.
#
# Exercise 8: File I/O
# - Write text to a file.
# - Read it back and print the contents.
# - Handle file errors with try/except.

# Exercise 9: Modules
# - Split code into two Python files.
# - Import one module from the other.
#
# Exercise 10: Simple CLI menu
# - Write a menu that repeats until the user exits.
# - Use functions for each action.

# ------------------------------------------------------------------
# 11) Learning tips
# ------------------------------------------------------------------
#
# Run scripts with python learn.py or python3 learn.py.
# Keep your code simple and test often.
# Use meaningful variable names and follow PEP 8.
# Read error messages carefully and fix the problem.

# End of Python learning guide.
