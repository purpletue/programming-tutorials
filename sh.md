#!/bin/bash
# learn.sh
# Bash learning guide
#
# This file is a comment-only guide for learning Bash syntax and structure.
# It does not solve the exercises for you. Read the notes, then write
# your own scripts from scratch based on what you learn here.
#
# Save this file and use it as a study reference while you practice.
#
# ------------------------------------------------------------------
# 1) Shell structure and syntax
# ------------------------------------------------------------------
#
# A shell script is a sequence of commands and control structures.
# The first line often starts with a shebang:
#   #!/bin/bash
#
# Comments begin with # and are ignored by the shell.
# Blank lines and indentation are for readability only.
#
# The shell reads each line, expands variables, and executes commands.
# The simplest shell script is a list of commands, but learning comes
# from combining variables, logic, and loops.
#
# ------------------------------------------------------------------
# 2) Variables and quoting
# ------------------------------------------------------------------
#
# Assign values without spaces around =:
#   name="value"
#   number=42
#
# Use variables with $name or ${name}:
#   echo "$name"
#
# Use quotes to preserve whitespace and avoid word splitting.
# Without quotes, strings may break into separate words.
#
# Example forms to study:
#   single_quote='literal text'
#   double_quote="interpolated text: $name"
#   no_quote=unquoted_value
#
# Shell arithmetic uses $(( ... )):
#   result=$((a + b))
#
# Learn the difference between assignment and command substitution:
#   today=$(date)
#   list=$(ls)
#
# ------------------------------------------------------------------
# 3) Command execution and pipelines
# ------------------------------------------------------------------
#
# A command can be simple or combined with pipes and redirects.
# Familiarize yourself with:
#   command arg1 arg2
#   command > output.txt
#   command 2> error.txt
#   command | other_command
#
# The shell executes each command and connects standard streams.
# Use command substitution to capture output into variables.
#
# ------------------------------------------------------------------
# 4) Conditional statements
# ------------------------------------------------------------------
#
# Use if/then/else/fi for branching.
# Study the syntax, not only the examples.
#
# Test expressions can be written with [[ ... ]] or [ ... ]:
#   [[ $x -lt $y ]]
#   [[ $name == "Alice" ]]
#   [[ -f "/etc/passwd" ]]
#   [[ -d "/tmp" ]]
#
# Remember:
#   if condition; then
#       commands
#   elif other_condition; then
#       other commands
#   else
#       fallback commands
#   fi
#
# Also learn the difference between = and == in string tests,
# and the arithmetic operators -eq, -ne, -lt, -gt.
#
# ------------------------------------------------------------------
# 5) Loops
# ------------------------------------------------------------------
#
# There are several loop forms in Bash:
#   for var in item1 item2; do ... done
#   while condition; do ... done
#   until condition; do ... done
#
# Practice writing loops that count, iterate arrays, and process input.
# Use (( ... )) for arithmetic tests inside loops.
#
# Learn how to break out of loops with break and skip iterations with continue.
#
# ------------------------------------------------------------------
# 6) Functions
# ------------------------------------------------------------------
#
# Define reusable blocks of code with functions.
# In Bash, functions receive positional arguments as $1, $2, ...
# They can return an exit status with return.
# Use echo to return text output, then capture it with command substitution.
#
# Example structure:
#   function name() {
#       local arg="$1"
#       ...
#       return 0
#   }
#
# Practice writing functions for small tasks, then call them from your script.
#
# ------------------------------------------------------------------
# 7) Arrays and indexing
# ------------------------------------------------------------------
#
# Bash arrays are created with parentheses:
#   values=(one two three)
# Access elements with ${values[0]}, ${values[1]}, etc.
# Use ${#values[@]} to get the array length.
#
# Iterate arrays with:
#   for item in "${values[@]}"; do ... done
#
# Learn how quoted expansions preserve each element separately.
#
# ------------------------------------------------------------------
# 8) Input and output
# ------------------------------------------------------------------
#
# Use read to accept user input.
# The -p option can prompt the user.
#
# Study how to validate input, check whether a variable is empty,
# and repeat prompts until valid input is provided.
#
# Also learn how to redirect output to files and append with >>.
#
# ------------------------------------------------------------------
# 9) Error handling and safety
# ------------------------------------------------------------------
#
# A more robust script can use:
#   set -euo pipefail
#
# This makes the shell exit on errors, on unset variables, and on failed
# commands within pipelines.
#
# Learn how to test for a command's success using if and exit codes.
# Use:
#   if ! command; then
#       echo "failed"
#       exit 1
#   fi
#
# Study how to provide default values safely:
#   value=${input:-default}
#
# ------------------------------------------------------------------
# 10) Exercises to learn Bash
# ------------------------------------------------------------------
#
# The best way to learn Bash is by writing your own scripts.
# Use the sections above as a reference, but do not copy full answers.
# Try these tasks and write each one from scratch.
#
# Exercise 1: Variable homework
# - Create a script that reads two numbers from the user.
# - Compute and print the sum, difference, product, quotient, and remainder.
# - Use quoted variable expansion and command substitution.
#
# Exercise 2: Conditional practice
# - Ask the user for a number.
# - Print whether it is positive, negative, or zero.
# - Also print whether it is even or odd.
# - Use if/elif/else and numeric tests.
#
# Exercise 3: Loop practice
# - Write a loop to print all even numbers from 2 to 20.
# - Write another loop to compute 5! (factorial of 5).
# - Write a third loop to print the first 10 Fibonacci numbers.
#
# Exercise 4: Function practice
# - Create a Bash function named is_prime.
# - It should accept one number argument and return 0 if prime or 1 if not.
# - Call the function with user input and print a helpful message.
#
# Exercise 5: Array practice
# - Create an array with at least 5 items.
# - Print the number of elements and each element on its own line.
# - Build a comma-separated string from the array elements.
#
# Exercise 6: File and path checks
# - Read a path from the user.
# - Print whether it is a regular file, directory, or missing.
# - If it is a file, print its size and permission bits.
#
# Exercise 7: Menu system
# - Write a simple menu that offers 3 actions.
# - Use functions for each action.
# - Loop until the user chooses to exit.
#
# Exercise 8: Input validation
# - Prompt for a number between 1 and 5.
# - Keep asking until the user enters valid input.
# - Print the chosen option when valid.
#
# Exercise 9: Safe scripting
# - Create a new script that begins with set -euo pipefail.
# - Use ${VAR:-default} when a variable may not be set.
# - Quote all variable expansions.
#
# Exercise 10: Command pipelines
# - Write a script that reads a directory path.
# - Count the files in that directory.
# - Print the top 3 largest files in that directory.
#
# ------------------------------------------------------------------
# 11) Study strategy
# ------------------------------------------------------------------
#
# Work through one section at a time.
# Read the syntax notes, then stop and write code without looking up answers.
# Use shellcheck or bash -n to catch syntax mistakes.
# When a script fails, inspect the error and try to understand why.
#
# End of Bash learning guide.
