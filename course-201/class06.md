# Problem Domain, Objects, and the DOM

### JavaScript Object Basics
How would you describe an object to a non-technical friend you grew up with?

> An object is like a variable but with multiple data points and values that you can change, as well as some functions you can have run when it's called. Think of it like a robot that you've programmed to remember you friends' birthdays, and when you tell it to it will automatically DM your friend on their birthday. You just had to go in and tell it to do those things so it knew what you were talking about.

What are some advantages to creating object literals?

> 

How do objects differ from arrays?
Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
Evaluate the code below. What does the term this refer to and what is the advantage to using this?
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
### Introduction To The DOM

What is the DOM?
Briefly describe the relationship between the DOM and JavaScript.