# HTML Lists, Control Flow with JS, and the CSS Box Model

### HTML

When should you use an unordered list in your HTML document?

> An unordered list is great when you have things in no particular order, like if you just want bullet points to get your point across.

How do you change the bullet style of unordered list items?

> Ideally, use CSS to change the 'list-style-type' attribute to either circle, disc, or square.

When should you use an ordered list vs an unorder list in your HTML document?

> An ordered list is great if you want a numbered list, like if you want things to be specifically sequential in how they're presented.

Describe two ways you can change the numbers on list items provided by an ordered list?

> Preferably using CSS, you can change the 'list-style-type' to be '1' for numbers, the default, 'a' for lowercase letters, 'A' for uppercase, 'i' for roman numerals, or 'I' for uppercase roman numerals. You can also use the attribute 'start' to start on a number/letter other than the default 1/A

### CSS

Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

> The Margin is the vanguard of the Spacial Army, The Padding is the Royal Guard whose purpose is to protect the Khantent from the Space Invaders. Between them is The Border, another fleet of soldiers who stand between the vanguard and the royal guard that are the more visible units on the Spacial battlefield.

List and describe the four parts of an HTML elements box as referred to by the box model.

> Margin, the outer-most box, separates the innards from other elements. Border is a potentially visible box that lines the outside of Padding, which is there to add space between the border and the content: the words or images or whatever is the main focal point innards of the whole Matryoshka doll of content sorcery.

### JS

What data types can you store inside of an Array?

> strings, numbers, objects, and other arrays are all valid options.

Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

> Each array inside the array is functionally all under one index value, in this case \['pete', 32, 'librarian', null] has an index of 0. If you wanted to pull a value out of THAT array, you could need to then pull from the index of THAT array, so people\[0]\[1] would get you 32.

List five shorthand operators for assignment in javascript and describe what they do.

> = is regular assignment; += is addition assignment, which is shorthand for x = x + f(); -= is subtraction assignment, which is shorthand for x = x - f(); *= is multiplication assignment, which is shorthand for x = x * f(); and **= is exponentiation assignment, which is shorthand for x = x ** f().

Read the code below and evaluate the last expression and explain what the result would be and why.

> 10dog would be the result, as a boolean 'false' would return a zero when added to 10, so the value would remain 10 before concatenating to 'dog'.

Describe a real world example of when a conditional statement should be used in a JavaScript program.

> There's lots of real world uses for conditional statements. like 
if(iAteDinner) {
  getDesert();
} else {
  getDinner();
}
There's an example of a conditional statement that could be used in your head when 8pm rolls round. Have you eaten dinner yet? Get some dessert. Otherwise go eat dinner, you fool!

Give an example of when a Loop is useful in JavaScript.

> Loops are useful when you need to do things multiple times and don't want to painstakingly write it out multiple times, or even if you don't know how many times to do something because it might vary depending on some external input.
while (thereIsNoCheese) {
  isThereCheeseYet = getCheese(); // There is a chance of failure from the Cheese Quest.
  if (isThereCheeseYet) {
    thereIsNoCheese = false;
  }
}
You want to only proceed with your life when there is cheese, so you want to loop the getCheese() function, which will hopefully yield cheese, until cheese has been acquired, then you can break out of the loop and proceed with your life.
