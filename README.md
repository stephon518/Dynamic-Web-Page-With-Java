# **Dynamic Web Page With Java**

It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension.
The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file).
If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.

Examples:

<!DOCTYPE html> <html>
<head>
<title>Constructive &amp; Co.</title>
<link rel ="stylesheet" href="css/cOl.css" />
</head> <body>
<hl>Constructive &amp; Co.</hl>
<p>For all orders and inquiries please call <em>555-3344</em></p> <script src="js/add-content.js"></script>
JAVASCRIPT RUNS WHERE IT IS FOUND IN THE HTML
When the browser comes across a <script>element, it stops to load the script and then checks to see if it needs to do anything.
</body> </html>

Websites are made up of three layers.
1. Content- Where the content of the page was = HTML
2. Presentation- Enhances the HTML with notes that state how the HTML looks = CSS
3. Behavior- This is where we can change how the page behaves and adds interactivity = JavaScript

**Statements**

Statement- A scripts a series of instructions that a computer can follow. Each direction or step is a statement. Statements should end in a semicolon(;) Each Statement should start on a new line and stops in a semicolon (;), and it tells JavaScript when a step is over. Statements can be organized into Code blocks {}, which are not followed by a semicolon.

Example of a Statement

var today = newDate (); 

Remember: JavaScript is case sensitive, so “hello” and “Hello” are different.

Always write comments in your code to explain what your system does. Comments make your code easier to read and understand to others who read it.
Multi-line Comments

**Variables**

* A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.
Rules for naming Variables
* Name your variables based on the terms of the subject area, so that the variable name clearly describes its purpose.
* Create variable names by deleting spaces that separate the words. Capitalize each word in the name, including prepositions and pronouns that consist of a single letter.
* Do not begin variable names with an underscore.
* Do not use variable names that consist of a single character. Short variable names are only allowed for loop counters.
* Name variables that describe binary states (“true” or “false”) after the state that matches the “true” value. 

