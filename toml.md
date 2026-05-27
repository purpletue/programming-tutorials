# learn.toml
# TOML learning guide
#
# This file contains comments only. It is a study guide for TOML
# syntax and concepts, not a configuration file to use directly.
# Read the notes, then write your own TOML files separately.
# ----------------------------------------------------------------
# 1) What is TOML?
# ----------------------------------------------------------------
# TOML is a configuration file format designed to be minimal and readable.
# It uses key/value pairs, tables, and arrays of tables.
#
# Learn that TOML is strict about types and that formatting is intended
# to be human-friendly.
# ----------------------------------------------------------------
# 2) Basic key/value pairs
# ----------------------------------------------------------------
# In TOML, keys map to values:
#   title = "Example"
#   enabled = true
#   count = 42
#
# Learn that strings must use quotes, booleans are plain words, and numeric
# values can be integers or floats.
# ----------------------------------------------------------------
# 3) Tables
# ----------------------------------------------------------------
# Tables group related values under a heading:
#   [server]
#   ip = "127.0.0.1"
#   port = 8080
#
# Learn how dotted keys can create nested tables.
# ----------------------------------------------------------------
# 4) Arrays
# ----------------------------------------------------------------
# Arrays hold ordered values:
#   colors = ["red", "green", "blue"]
#
# Learn that arrays must contain values of the same type and can include
# tables as array items.
# ----------------------------------------------------------------
# 5) Arrays of tables
# ----------------------------------------------------------------
# Array-of-tables syntax is used for repeated sections:
#   [[products]]
#   name = "A"
#
#   [[products]]
#   name = "B"
#
# Learn how this differs from normal tables and when to use it.
# ----------------------------------------------------------------
# 6) Data types
# ----------------------------------------------------------------
# TOML supports strings, integers, floats, booleans, datetimes, arrays,
# and inline tables.
#
# Learn how datetimes are written and how strings can be multiline.
# ----------------------------------------------------------------
# 7) Comments
# ----------------------------------------------------------------
# Comments start with # and run to the end of the line.
# Example:
#   # this is a comment
#   title = "Hello"
#
# Learn to use comments for documentation and to avoid breaking the format.
# ----------------------------------------------------------------
# 8) Inline tables and nested keys
# ----------------------------------------------------------------
# Inline tables are compact object literals:
#   point = { x = 1, y = 2 }
#
# Learn how nested keys can be written with dots:
#   physical.color = "red"
#
# ----------------------------------------------------------------
# 9) TOML rules and pitfalls
# ----------------------------------------------------------------
# Avoid trailing commas in arrays and tables.
# Strings must be properly quoted and escape sequences must be valid.
#
# Learn that TOML is intentionally less flexible than YAML to reduce
# ambiguity.
# ----------------------------------------------------------------
# 10) Exercises to practice TOML
# ----------------------------------------------------------------
# Write these exercises in separate .toml files. Use this guide only as
# reference, and write the solutions yourself.
#
# Exercise 1: Basic configuration
# - Create top-level keys for title, enabled, and count.
# - Use string, boolean, and integer values.
#
# Exercise 2: Server table
# - Add a [server] table with host and port.
# - Use a table heading and plain values.
#
# Exercise 3: Array values
# - Add an array of strings and an array of integers.
# - Keep element types consistent.
#
# Exercise 4: Nested tables
# - Create nested tables using dotted keys.
# - Group settings logically.
#
# Exercise 5: Array of tables
# - Define [[products]] or similar repeated sections.
# - Add at least two entries.
#
# Exercise 6: Multiline and inline tables
# - Use a multiline basic string or a literal string.
# - Add an inline table to represent compact data.
# ----------------------------------------------------------------
# 11) Learning tips
# ----------------------------------------------------------------
# Use a TOML parser to validate your files.
# Keep formatting consistent and avoid unnecessary complexity.
# Prefer simple tables and clear headings.
# End of TOML learning guide.
