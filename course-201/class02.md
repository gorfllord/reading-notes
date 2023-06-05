# Basics of HTML, CSS, & JS

## HTML Text fundamentals. HTML Advanced Text Formatting

Why is it important to use semantic elements in our HTML?

> Using semantic elements in HTML makes things much easier to read and understand for both yourself and for anyone else that might need to use or review your code.

How many levels of headings are there in HTML?

> There are 6 levels of headings in HTML

What are some uses for the \<sup> and \<sub> elements?

> Exponents and footnotes are great uses for superscript, subscript is also good for footnotes and citations. Also the specified examples are for things like the "th" in 25th or chemical formulas.

When using the \<abbr> element, what attribute must be added to provide the full expansion of the term?

> Abbreviations are good tools for accessibility so that a reader can know how to properly pronounce an abbreviation, like Rev Dr Martin Luther King. Without the abbreviate element, it might try to read it phonetically as "rev derr Martin Luther King" or something silly like that. The attribute added for this functionality is "title", like \<abbr title="Doctor">Dr.\</abbr>

## How CSS is Structured

What are ways we can apply CSS to our HTML?

> You can either do it in-line per element, place a style tag with CSS inside in the head, or reference a CSS file to pull the style from.

Why should we avoid using inline styles?

> inline styles work for a single page, but as soon as you have multiple pages it's way more efficient to have everything reference one CSS file, especially so that if you make any changes to the style, it'll translate to all pages on your website. 

Review the block of code below and answer the following questions:
What is representing the selector?

> h2 is the selector in this case

Which components are the CSS declarations?

> each line that ends with a semi-colon are declarations, so in this case "color: black;" and "padding: 5px;" are the CSS declarations.

Which components are considered properties?

> color and padding are the properties in this case that are being assigned values.

## Learn JavaScript

What data type is a sequence of text enclosed in single quote marks?

> String

List 4 types of JavaScript operators.

> +, =, ==, !==

Describe a real world Problem you could solve with a Function.

> You want to calculate someone's age based on a supplied birthday, so you could build a function that takes a supplied birthday answer and compares it to the current date with some math sorcery to return an answer of their age.

An if statement checks a __ and if it evaluates to ___, then the code block will execute.

> An if statement checks a condition and if it evaluates to TRUE, then the code block will execute.

What is the use of an else if?

> An else if gives you the ability to check for an additional condition if the first and/or previous condition was FALSE

List 3 different types of comparison operators.

> ==, <, >=

What is the difference between the logical operator && and \||?

> && is and, \|| is or. && wants both things to be true, \|| wants one of the things to be true.
