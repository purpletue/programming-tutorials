<!-- learn.plist -->
<!-- Property list learning guide -->
<!--
     This file contains comments only. It is a study guide for plist
     structure and syntax, not a working property list. Read the notes,
     then write your own plist files separately.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 1) What is a plist? -->
<!-- ---------------------------------------------------------------- -->
<!-- A plist is an Apple property list format used for configuration and
     serialized data. It is commonly stored as XML or binary data. -->
<!--
     In XML form, a plist begins with <?xml ...?> and a <plist> root.
     The document contains dictionaries, arrays, strings, numbers, booleans,
     dates, and data values.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 2) XML structure -->
<!-- ---------------------------------------------------------------- -->
<!-- A typical XML plist starts like this:
     <?xml version="1.0" encoding="UTF-8"?>
     <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN"
       "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
     <plist version="1.0">
       <dict>...</dict>
     </plist>
 -->
<!-- Learn the required root elements and DTD declaration. -->
<!-- ---------------------------------------------------------------- -->
<!-- 3) Dictionary entries -->
<!-- ---------------------------------------------------------------- -->
<!-- Dictionaries store key/value pairs.
     Example:
       <dict>
         <key>Name</key>
         <string>Example</string>
         <key>Count</key>
         <integer>5</integer>
       </dict>
 -->
<!-- Learn that <key> elements must appear before their value elements.
     Keys are always strings. -->
<!-- ---------------------------------------------------------------- -->
<!-- 4) Arrays -->
<!-- ---------------------------------------------------------------- -->
<!-- Arrays contain ordered values.
     Example:
       <array>
         <string>Red</string>
         <string>Green</string>
       </array>
 -->
<!-- Learn how to nest arrays inside dictionaries and how arrays preserve order. -->
<!-- ---------------------------------------------------------------- -->
<!-- 5) Value types -->
<!-- ---------------------------------------------------------------- -->
<!-- Common plist value types include:
       <string>, <integer>, <real>, <true/>, <false/>, <date>, <data>
 -->
<!-- Learn how each type is represented and when to choose it.
     Dates use ISO 8601 format, and binary data is base64-encoded.
 -->
<!-- ---------------------------------------------------------------- -->
<!-- 6) Boolean values -->
<!-- ---------------------------------------------------------------- -->
<!-- Booleans are encoded as empty tags.
     Example:
       <true/>
       <false/>
 -->
<!-- Learn that booleans do not have text content. -->
<!-- ---------------------------------------------------------------- -->
<!-- 7) Data values -->
<!-- ---------------------------------------------------------------- -->
<!-- Use <data> for binary values in base64.
     Example:
       <data>
       SGVsbG8=
       </data>
 -->
<!-- Learn to preserve whitespace and use proper encoding for base64 data. -->
<!-- ---------------------------------------------------------------- -->
<!-- 8) Keys and ordering -->
<!-- ---------------------------------------------------------------- -->
<!-- plist dictionaries are ordered maps; key order can matter in some tools.
     Keep key/value pairs grouped logically and consistently.
 -->
<!-- Learn to avoid duplicate keys and to maintain valid nesting. -->
<!-- ---------------------------------------------------------------- -->
<!-- 9) Property list tooling -->
<!-- ---------------------------------------------------------------- -->
<!-- On macOS, use plutil to validate and convert plist files.
     Example: plutil -lint file.plist
 -->
<!-- Learn how to open plists in Xcode and how to convert XML to binary. -->
<!-- ---------------------------------------------------------------- -->
<!-- 10) Exercises to practice plist -->
<!-- ---------------------------------------------------------------- -->
<!-- Write these exercises in separate .plist files. Use this guide only as
     reference, and write the solutions yourself. -->
<!--
     Exercise 1: Basic dictionary
     - Create a plist with two keys: Name and Enabled.
     - Use a string and a boolean value.

     Exercise 2: Nested structures
     - Add an array under one dictionary key.
     - Add values of different types inside the array.

     Exercise 3: Configuration example
     - Create keys for server, port, and timeout.
     - Use integer, real, and string values.

     Exercise 4: Date and data
     - Add a date value in ISO 8601 format.
     - Add a data value as base64 text.

     Exercise 5: Valid plist
     - Add the XML prolog and DOCTYPE.
     - Validate the file with plutil or a parser.
 -->
<!-- ---------------------------------------------------------------- -->
<!-- 11) Learning tips -->
<!-- ---------------------------------------------------------------- -->
<!-- Keep plists well-formed and avoid invalid characters.
     Test XML plists with validation tools.
     Use comments sparingly, because plist comments are not part of the data.
 -->
<!-- End of Property List learning guide. -->
