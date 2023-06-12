# Problem Domain, Objects, and the DOM

### JavaScript Object Basics
How would you describe an object to a non-technical friend you grew up with?

> An object is like a variable but with multiple data points and values that you can change, as well as some functions you can have run when it's called. Think of it like a robot that you've programmed to remember you friends' birthdays, and when you tell it to it will automatically DM your friend on their birthday. You just had to go in and tell it to do those things so it knew what you were talking about.

What are some advantages to creating object literals?

> Object literals can help you write less lengthy code, as you can utilize the syntax as a sort of shorthand. Also using this.whatever allows it to be self-referential which is especially helpful when you're making multiple objects with the same code.

How do objects differ from arrays?

> You could think of objects as an associative arrays of sorts? The biggest difference is that you can call items with a string rather than needing an index number. Plus you can build in some functions

Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

> If the object value is a variable, you'll need to use bracket notation to access it.

Evaluate the code below. What does the term this refer to and what is the advantage to using this?

> 'this' refers to the parent object, in this case dog. It would be a shorthand of writing dog.name, for example. The main reason to use this is that it's shorter, especially if you're using the same code in multiple spots. Especially especially useful if you're using constructors to make a bunch of objects with similar parameters. Like maybe you also need a cat constant with similar values and functions.

### Introduction To The DOM

What is the DOM?

> Document Object Model is a way to interface with web documents. You can use it with JavaScript to access parts of the webpage to call or change values.

Briefly describe the relationship between the DOM and JavaScript.

> the DOM is not a coding language, rather it's an interface for coding languages, like JavaScript, to access web elements and content.
