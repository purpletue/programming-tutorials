// learn.jsonc
// JSONC learning guide
//
// This file contains comments only. It is a study guide for JSONC
// syntax and concepts, not a real data file. Read the notes, then write
// your own JSONC files separately.
// ------------------------------------------------------------------
// 1) What is JSONC?
// ------------------------------------------------------------------
// JSONC is JSON with comments. It is useful for configuration files
// that need explanations but still use JSON-like structure.
//
// Learn that JSONC is not standard JSON and is supported by editors
// and some tools, especially in the JavaScript ecosystem.
// ------------------------------------------------------------------
// 2) Syntax basics
// ------------------------------------------------------------------
// JSONC uses normal JSON syntax plus comments.
// You can use single-line comments:
//   // comment
// And multi-line comments:
//   /* comment */
//
// Learn the core JSON rules: objects, arrays, strings, numbers,
// booleans, and null.
// ------------------------------------------------------------------
// 3) Objects and properties
// ------------------------------------------------------------------
// An object is a set of key/value pairs:
//   {
//     "name": "Alice",
//     "age": 30
//   }
//
// Learn that keys must be quoted strings, and values can be any valid
// JSON expression except trailing commas are not allowed in strict JSON.
// JSONC may allow trailing commas depending on the parser.
// ------------------------------------------------------------------
// 4) Arrays
// ------------------------------------------------------------------
// Arrays hold ordered values:
//   ["red", "green", "blue"]
//
// Learn how arrays can contain objects, arrays, and primitive values.
// ------------------------------------------------------------------
// 5) Data types
// ------------------------------------------------------------------
// Valid JSON values are:
//   string, number, object, array, true, false, null
//
// Learn that JSONC keeps these values but lets you add comments around them.
// ------------------------------------------------------------------
// 6) Comments in JSONC
// ------------------------------------------------------------------
// Use comments to explain configuration or annotate values.
//   {
//     "port": 8080, // server port
//     /* allowed origins */
//     "origins": ["*"]
//   }
//
// Learn that comments are ignored by parsers that support JSONC.
// ------------------------------------------------------------------
// 7) Trailing commas
// ------------------------------------------------------------------
// Some JSONC parsers allow trailing commas in objects and arrays.
// Example:
//   {
//     "foo": 1,
//     "bar": 2,
//   }
//
// Learn parser-specific behavior and avoid relying on trailing commas
// unless your tool explicitly supports them.
// ------------------------------------------------------------------
// 8) Use cases
// ------------------------------------------------------------------
// JSONC is commonly used for editor settings, IDE config, and other
// human-readable configuration files.
//
// Learn when plain JSON is enough and when JSONC adds helpful clarity.
// ------------------------------------------------------------------
// 9) Tools and editors
// ------------------------------------------------------------------
// Many tools that understand JSON also support JSONC in practice.
// Editors like VS Code treat .jsonc as JSON with comments.
//
// Learn how to configure toolchains to parse JSONC files safely.
// ------------------------------------------------------------------
// 10) Exercises to practice JSONC
// ------------------------------------------------------------------
// Write these exercises in separate .jsonc files. Use this guide only as
// reference, and write the solutions yourself.
//
// Exercise 1: Basic config
// - Create an object with string and number values.
// - Add comments for each setting.
//
// Exercise 2: Array config
// - Create an array of values.
// - Add comments explaining the items.
//
// Exercise 3: Nested objects
// - Create nested objects for a settings section.
// - Add comments at different levels.
//
// Exercise 4: Trailing commas
// - Try a JSONC object with a trailing comma.
// - Determine whether your parser accepts it.
//
// Exercise 5: Complex values
// - Use arrays, objects, booleans, and null values.
// - Add explanatory comments.
//
// Exercise 6: Editor settings
// - Write a sample editor config file with comments.
// - Use JSONC syntax to explain each config option.
//
// Exercise 7: Compare with JSON
// - Convert a JSONC file to strict JSON by removing comments.
// - Validate the result with a JSON parser.
//
// Exercise 8: Production safety
// - Identify parser differences in JSONC support.
// - Note which tools allow comments and trailing commas.
// ------------------------------------------------------------------
// 11) Learning tips
// ------------------------------------------------------------------
// Use JSONC only where comments add value.
// When sharing files with tools, prefer strict JSON if compatibility is required.
// Keep comments clear and avoid obscuring the data structure.
// End of JSONC learning guide.
