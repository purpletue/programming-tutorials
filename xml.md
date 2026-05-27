<!-- learn.xml -->
<!-- XML learning guide -->
<!--
     This file contains comments only. It is a study guide for XML
     syntax and structure, not a runnable document. Read the notes, then
     write your own XML files separately.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 1) XML overview -->
<!-- ---------------------------------------------------------------- -->
<!-- XML is a markup language for representing structured data.
     It is strict about syntax, well-formed nesting, and matching tags. -->
<!--
     XML uses elements, attributes, and a hierarchical structure.
     Learn how to model data as nested tags with meaningful names.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 2) Elements -->
<!-- ---------------------------------------------------------------- -->
<!-- Elements are the basic building blocks of XML.
     Example:
       <person>
         <name>Alice</name>
       </person>
-->
<!-- Learn that element names must start with a letter or underscore and
     cannot contain spaces. -->
<!-- ---------------------------------------------------------------- -->
<!-- 3) Attributes -->
<!-- ---------------------------------------------------------------- -->
<!-- Attributes provide metadata on elements.
     Example:
       <item id="123" type="book" />
-->
<!-- Learn when to use attributes vs child elements for data.
     Attributes must be quoted and cannot contain unescaped < or &.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 4) Prolog and declarations -->
<!-- ---------------------------------------------------------------- -->
<!-- XML documents often begin with a prolog:
       <?xml version="1.0" encoding="UTF-8"?>
-->
<!-- Learn the importance of declaring encoding and version.
     A document must be well-formed to be parsed successfully.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 5) Namespaces -->
<!-- ---------------------------------------------------------------- -->
<!-- XML namespaces avoid name collisions in mixed vocabularies.
     Example:
       <x:book xmlns:x="http://example.com/books">
         <x:title>...</x:title>
       </x:book>
-->
<!-- Learn how to define and use namespace prefixes.
     Understand default namespaces and qualified names.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 6) CDATA and text content -->
<!-- ---------------------------------------------------------------- -->
<!-- Use CDATA sections when you need literal text with markup characters.
     Example:
       <![CDATA[<tag>not markup</tag>]]>
-->
<!-- Learn how XML text content works and when to escape special characters.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 7) Entities and escaping -->
<!-- ---------------------------------------------------------------- -->
<!-- XML has predefined entities: &amp;, &lt;, &gt;, &quot;, and &apos;.
     Example:
       <note>Tom &amp; Jerry</note>
-->
<!-- Learn to escape reserved characters in text and attributes.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 8) DTD and validation -->
<!-- ---------------------------------------------------------------- -->
<!-- XML can be validated against a DTD or schema.
     Example DTD snippet:
       <!ELEMENT note (to,from,heading,body)>
-->
<!-- Learn the difference between well-formed XML and valid XML.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 9) XML tools and parsing -->
<!-- ---------------------------------------------------------------- -->
<!-- XML is typically parsed by libraries or tools.
     Common APIs include DOM, SAX, and StAX.
-->
<!-- Learn how document structure is represented as a tree.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 10) Exercises to practice XML -->
<!-- ---------------------------------------------------------------- -->
<!-- Write these exercises in separate .xml files. Use this guide only as
     reference, and write the solutions yourself. -->
<!--
     Exercise 1: Simple document
     - Create a root element with child elements.
     - Add text content inside elements.

     Exercise 2: Attributes
     - Add attributes to several elements.
     - Use quotes and valid names.

     Exercise 3: Nested structure
     - Create nested elements representing a hierarchy.
     - Ensure matching open and close tags.

     Exercise 4: CDATA
     - Add a CDATA section containing HTML-like text.
     - Reference text without needing escapes.

     Exercise 5: Namespaces
     - Create elements with namespace prefixes.
     - Declare the namespace URI in the root.

     Exercise 6: Escaping
     - Include special characters in text using entities.
     - Use &amp;, &lt;, &gt;, &quot;, and &apos;.

     Exercise 7: DTD validation
     - Add a simple DTD to a document.
     - Validate the document structure against it.

     Exercise 8: Comments
     - Add XML comments in several places.
     - Ensure comment syntax is correct.

     Exercise 9: Metadata
     - Add elements for title, author, and date.
     - Use meaningful names and structure.

     Exercise 10: Schema awareness
     - Read about XML Schema or Relax NG.
     - Compare schema validation to DTD validation.
-->
<!-- ---------------------------------------------------------------- -->
<!-- 11) Learning tips -->
<!-- ---------------------------------------------------------------- -->
<!-- Start with well-formed XML before learning validation.
     Test XML with a parser or editor that reports errors.
     Keep element names consistent and avoid unnecessary complexity.
-->
<!-- End of XML learning guide. -->
