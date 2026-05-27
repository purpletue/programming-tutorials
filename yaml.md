# learn.yaml
# YAML learning guide
#
# This file contains comments only. It is a study guide for YAML
# syntax and concepts, not a real YAML data file. Read the notes,
# then write your own YAML documents separately.
# ----------------------------------------------------------------
# 1) What is YAML?
# ----------------------------------------------------------------
# YAML is a human-friendly data serialization format often used for
# configuration. It uses indentation to express structure.
#
# Learn that YAML is whitespace-sensitive and that indentation is
# significant, not optional.
# ----------------------------------------------------------------
# 2) Basic syntax
# ----------------------------------------------------------------
# YAML uses key-value pairs and sequences.
# Example object:
#   name: Alice
#   age: 30
# Example array:
#   colors:
#     - red
#     - blue
#
# Learn how YAML avoids braces and brackets in favor of indentation.
# ----------------------------------------------------------------
# 3) Scalars
# ----------------------------------------------------------------
# YAML supports plain scalars, quoted strings, numbers, booleans, and null.
# Examples:
#   title: Hello
#   enabled: true
#   count: 42
#   empty: null
#
# Learn when to use quotes and how multiline strings work with | and >.
# ----------------------------------------------------------------
# 4) Mapping and sequences
# ----------------------------------------------------------------
# Use mappings for objects and sequences for lists.
# Example:
#   person:
#     name: Alice
#     hobbies:
#       - reading
#       - music
#
# Learn how to nest mappings and sequences with consistent indentation.
# ----------------------------------------------------------------
# 5) Indentation and structure
# ----------------------------------------------------------------
# YAML relies on spaces, not tabs. Use a consistent indentation width.
# Nested blocks are created by indenting child lines beneath parents.
#
# Learn to align values carefully and avoid mixing tabs and spaces.
# ----------------------------------------------------------------
# 6) Comments
# ----------------------------------------------------------------
# YAML comments start with #.
# Example:
#   # This is a comment
#   port: 8080
#
# Learn to use comments to explain config without affecting the data.
# ----------------------------------------------------------------
# 7) Complex structures
# ----------------------------------------------------------------
# YAML supports nested sequences, mappings, and anchors/aliases.
# Example:
#   default: &default
#     timeout: 30
#   server:
#     <<: *default
#     host: localhost
#
# Learn how anchors reuse values and aliases reference them.
# ----------------------------------------------------------------
# 8) Multiline text
# ----------------------------------------------------------------
# Use | for literal blocks and > for folded blocks.
# Example:
#   description: |
#     This text preserves line breaks.
#
# Learn the difference between literal and folded block styles.
# ----------------------------------------------------------------
# 9) YAML versions and compatibility
# ----------------------------------------------------------------
# YAML has several versions; most tools support YAML 1.2 or a subset.
# Be aware of parser-specific features like explicit tags and anchors.
#
# Learn to write YAML that is compatible with your target parser.
# ----------------------------------------------------------------
# 10) Exercises to practice YAML
# ----------------------------------------------------------------
# Write these exercises in separate .yaml files. Use this guide only as
# reference, and write the solutions yourself.
#
# Exercise 1: Basic config
# - Create top-level keys for name, version, and enabled.
# - Use strings, numbers, and booleans.
#
# Exercise 2: Nested data
# - Create a mapping for a service with host and port.
# - Add a list of endpoints.
#
# Exercise 3: Lists
# - Create a sequence of items.
# - Use both plain and quoted scalars.
#
# Exercise 4: Multiline strings
# - Add a literal block using |
# - Add a folded block using >
#
# Exercise 5: Anchors and aliases
# - Define an anchor for a shared config block.
# - Reference it with an alias.
#
# Exercise 6: Comments
# - Add comments explaining each section.
# - Keep comments clear and concise.
#
# Exercise 7: Parser compatibility
# - Avoid YAML features that are uncommon in simple parsers.
# - Validate the YAML with a parser.
# ----------------------------------------------------------------
# 11) Learning tips
# ----------------------------------------------------------------
# Use a YAML linter or parser to validate your documents.
# Keep indentation consistent and avoid tabs.
# Write YAML for readability and maintainability.
# End of YAML learning guide.
