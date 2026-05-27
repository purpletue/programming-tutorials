# learn.r
# R learning guide
#
# This file contains comments only. It is meant as a study guide for R
# syntax and concepts, not a runnable script. Read the notes, then write
# your own R code separately.

# ------------------------------------------------------------------
# 1) R script structure
# ------------------------------------------------------------------
#
# R scripts are executed from top to bottom.
# You can save code in a .R file and run it with Rscript or source().
#
# Learn how to structure scripts and use functions for reusable code.

# ------------------------------------------------------------------
# 2) Variables and types
# ------------------------------------------------------------------
#
# R is dynamically typed. Common types include:
#   numeric, integer, character, logical, factor, list, data.frame
#
# Assign values with <- or =:
#   x <- 5
#   name <- "Alice"
#
# Learn how vectors and scalars behave in R.

# ------------------------------------------------------------------
# 3) Expressions and operators
# ------------------------------------------------------------------
#
# R operators include:
#   +, -, *, /, ^, %%
#   ==, !=, <, >, <=, >=
#   &, |, !
#
# Learn vectorized operations and how arithmetic works on vectors.

# ------------------------------------------------------------------
# 4) Control flow
# ------------------------------------------------------------------
#
# R supports if, else, for, while, and repeat.
# Example forms:
#   if (condition) {
#       ...
#   } else {
#       ...
#   }
#
#   for (i in 1:5) {
#       ...
#   }
#
#   while (condition) {
#       ...
#   }
#
# Practice controlling flow and using braces.

# ------------------------------------------------------------------
# 5) Functions
# ------------------------------------------------------------------
#
# Define functions with:
#   add <- function(a, b) {
#       return(a + b)
#   }
#
# Learn how arguments are passed and how to return values.
# Practice writing small reusable functions.

# ------------------------------------------------------------------
# 6) Vectors and data structures
# ------------------------------------------------------------------
#
# Vectors are central in R:
#   nums <- c(1, 2, 3)
#
# Also learn lists, matrices, and data frames:
#   df <- data.frame(x = 1:3, y = c("a", "b", "c"))
#
# Learn indexing, subsetting, and vectorized operations.

# ------------------------------------------------------------------
# 7) Data input/output
# ------------------------------------------------------------------
#
# Read data with read.csv, read.table, scan, or readLines.
# Write data with write.csv or write.table.
#
# Learn how to inspect data with head(), str(), and summary().

# ------------------------------------------------------------------
# 8) Packages and libraries
# ------------------------------------------------------------------
#
# Use library(pkg) or require(pkg) to load installed packages.
# Learn how to install packages with install.packages("pkg").
#
# Practice using common packages such as dplyr and ggplot2 when ready.

# ------------------------------------------------------------------
# 9) Error handling and debugging
# ------------------------------------------------------------------
#
# Use tryCatch() for error handling.
# Use print() and str() to inspect values.
#
# Learn how to debug code with browser() and traceback().

# ------------------------------------------------------------------
# 10) Exercises to practice R
# ------------------------------------------------------------------
#
# These exercises should be written in separate R scripts.
# Use this guide as a reference, but implement the solutions yourself.
#
# Exercise 1: Basics
# - Write a script that prints a greeting.
# - Assign variables and print their values.
#
# Exercise 2: Arithmetic and vectors
# - Create a numeric vector.
# - Compute its sum, mean, and length.
#
# Exercise 3: Conditionals
# - Write code that checks whether a number is positive,
#   negative, or zero.
# - Use if/else statements.
#
# Exercise 4: Loops
# - Use a for loop to print values 1 to 10.
# - Use a while loop to compute the factorial of 5.

# Exercise 5: Functions
# - Define a function that adds two numbers.
# - Define a function that computes the square of a number.

# Exercise 6: Data frames
# - Create a data frame with at least two columns.
# - Print summary statistics for the data frame.

# Exercise 7: Subsetting
# - Filter a vector or data frame based on a condition.
# - Print the filtered results.

# Exercise 8: Plotting
# - Create a simple plot with plot() or barplot().
# - Label the axes and title the plot.

# Exercise 9: Packages
# - Install and load a package.
# - Use one function from that package.

# Exercise 10: Error handling
# - Use tryCatch() around code that may fail.
# - Print a message when an error occurs.

# ------------------------------------------------------------------
# 11) Learning tips
# ------------------------------------------------------------------
#
# Run R scripts with Rscript learn.r or source("learn.r").
# Keep code small and test often.
# Use comments to explain what your code does.
# Read error messages carefully and fix issues step by step.

# End of R learning guide.
