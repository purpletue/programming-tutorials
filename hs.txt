-- learn.hs
-- Haskell learning guide
--
-- This file contains comments only. It is a study guide for Haskell syntax
-- and concepts, not a runnable program. Read the notes, then write your
-- own Haskell code separately.

-- ------------------------------------------------------------------
-- 1) Haskell program structure
-- ------------------------------------------------------------------
--
-- Haskell programs are built from expressions and functions.
-- A simple program can define a main value:
--   main :: IO ()
--   main = putStrLn "Hello"
--
-- Learn how modules and imports organize code.

-- ------------------------------------------------------------------
-- 2) Types and values
-- ------------------------------------------------------------------
--
-- Haskell is statically typed with type inference.
-- Common types include:
--   Int, Integer, Float, Double, Bool, Char, String
--
-- Learn how to write type annotations:
--   x :: Int
--   x = 5
--
-- Practice with algebraic data types and type synonyms later.

-- ------------------------------------------------------------------
-- 3) Expressions and operators
-- ------------------------------------------------------------------
--
-- Haskell uses expressions for computation.
-- Common operators include:
--   +, -, *, /, ^, &&, ||, ==, /=, <, >, <=, >=
--
-- Learn how function application has the highest precedence.
-- Practice using parentheses to group expressions.

-- ------------------------------------------------------------------
-- 4) Functions
-- ------------------------------------------------------------------
--
-- Functions are defined by equations:
--   add x y = x + y
--   square x = x * x
--
-- Learn how to use recursion and pattern matching.
-- Practice writing pure functions.

-- ------------------------------------------------------------------
-- 5) Lists and tuples
-- ------------------------------------------------------------------
--
-- Lists are a fundamental collection type:
--   nums = [1, 2, 3]
--
-- Tuples group fixed-size values:
--   pair = (1, "one")
--
-- Learn list operations like head, tail, map, filter, and fold.

-- ------------------------------------------------------------------
-- 6) Pattern matching and guards
-- ------------------------------------------------------------------
--
-- Use pattern matching to branch on data:
--   fact 0 = 1
--   fact n = n * fact (n - 1)
--
-- Use guards for conditional definitions:
--   abs x
--       | x < 0     = -x
--       | otherwise = x
--
-- Practice matching constructors and using guards.

-- ------------------------------------------------------------------
-- 7) I/O and monads
-- ------------------------------------------------------------------
--
-- Haskell separates pure code from I/O.
-- The `IO` type represents side effects.
-- Example:
--   main = do
--       putStrLn "Hello"
--       line <- getLine
--       putStrLn line
--
-- Learn how `do` notation sequences actions.

-- ------------------------------------------------------------------
-- 8) Higher-order functions
-- ------------------------------------------------------------------
--
-- Functions can take functions as arguments and return them.
-- Examples include map, filter, and foldr.
--
-- Practice writing functions that compose other functions.

-- ------------------------------------------------------------------
-- 9) Types and typeclasses
-- ------------------------------------------------------------------
--
-- Learn common typeclasses: Eq, Ord, Show, Read.
-- Type signatures clarify function behavior.
--
-- Example:
--   elem :: Eq a => a -> [a] -> Bool
--
-- Practice writing polymorphic functions.

-- ------------------------------------------------------------------
-- 10) Exercises to practice Haskell
-- ------------------------------------------------------------------
--
-- These exercises should be written in separate Haskell files.
-- Use this guide as a reference, but implement the solutions yourself.
--
-- Exercise 1: Hello, Haskell
-- - Write a program that prints a greeting.
-- - Define main using putStrLn.
--
-- Exercise 2: Arithmetic functions
-- - Write functions for add, subtract, multiply, and divide.
-- - Add type signatures for each function.
--
-- Exercise 3: Conditionals and guards
-- - Write a function that returns the absolute value.
-- - Write a function that classifies a number as positive, negative, or zero.
--
-- Exercise 4: Recursion
-- - Write a recursive factorial function.
-- - Write a recursive function to compute the nth Fibonacci number.

-- Exercise 5: Lists
-- - Use map to square a list of numbers.
-- - Use filter to keep only even numbers.
-- - Use foldr or foldl to sum a list.

-- Exercise 6: Pattern matching
-- - Write a function that returns the first element of a list.
-- - Write a function that splits a list into head and tail.

-- Exercise 7: I/O
-- - Write a program that reads a line from the user.
-- - Print the line back with a prefix.

-- Exercise 8: Higher-order functions
-- - Write a function that applies another function twice.
-- - Use function composition with (.) and ($).

-- Exercise 9: Typeclasses
-- - Write a function with a polymorphic type signature.
-- - Use Show to convert values to strings.

-- Exercise 10: Modules
-- - Create a module with a few functions.
-- - Import it from another file and use those functions.

-- ------------------------------------------------------------------
-- 11) Learning tips
-- ------------------------------------------------------------------
--
-- Run Haskell code with runhaskell or compile with ghc.
-- Keep functions small and test often.
-- Read type errors carefully and use type signatures.
-- Practice by writing small pure functions first.

-- End of Haskell learning guide.
