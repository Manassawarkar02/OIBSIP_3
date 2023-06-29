# OIBSIP_3
The following repository provides the program code for a Temperature converter  which I've made using HTML, CSS and JAVASCRIPT.
The provided code is an HTML document that creates a simple temperature conversion tool. Here's a breakdown of the code:

- The document starts with the HTML doctype declaration and the opening `<html>` tag.
- The `<head>` section contains metadata and external resources used by the document. It includes:
  - `<meta>` tags for specifying the character encoding and viewport settings.
  - The `<title>` element that sets the title of the document.
  - A link to a Google Font called "Roboto Mono" to be used for styling.
  - An external stylesheet file named "style.css" for additional styling.
- The `<body>` section is where the visible content of the webpage is placed. It consists of:
  - A `<div>` element with the class "wrapper" that serves as a container for the content.
  - Inside the wrapper, there are two identical `<div>` elements with the class "container". Each container represents a temperature input field.
  - The first container includes a `<label>` element with the text "Celsius" and an `<input>` field with the id "celsius". This field is used to enter the temperature in Celsius.
  - The second container includes a similar set of elements for Fahrenheit temperature input.
- At the end of the `<body>` section, just before the closing `</body>` tag, there is a `<script>` tag that references an external JavaScript file called "script.js". This file contains the temperature conversion logic and is responsible for updating the converted temperature in real-time as the user inputs values.
- Finally, the document ends with the closing `</html>` tag.

Overall, this code creates a basic web page with two input fields for Celsius and Fahrenheit temperatures, allowing users to convert between the two units dynamically. The styling of the page is handled by an external CSS file, and the functionality of the temperature conversion is implemented in a separate JavaScript file.
