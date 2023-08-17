# Passing Functions as Props

## React Docs - lists and keys

What does .map() return?

> .map() returns an array the same size as it's input array, modified by whichever functioned you passed into it.

If I want to loop through an array and display each value in JSX, how do I do that in React?

> You should use a key

Each list item needs a unique ____.

> Key value

What is the purpose of a key?

> A key is there to help identify list elements. Using indexes is great until the array changes and you needed to reference a specific entry, so a key allows the data to change and still know how to reference certain list items without everything breaking.

## The Spread Operator

What is the spread operator?

> Ellipses (...)

List 4 things that the spread operator can do.

> It can split out the contents of an array when passing it as a variable, such that instead of the array itself getting passed, all of the contents are passed separately instead.
>
> You can also use it to populate a new array with the contents of an existing array, though at a certain point wouldn't assigning arr2 to arr1 basically do the same? There's probably some syntax where it makes more sense than the example I saw on MDN.
>
> What's better than that, you can use it to more easily concatenate arrays. [...arr1, ...arr2] combines the contents of arr1 and arr2.
>
> Looks like it can also be used to shorthand making a new object with a constructor, as it won't take an array, but you can use ...arr to spread out the contents to plug in the values just fine.

Give an example of using the spread operator to combine two arrays.

    let arr = [0,1,2]; 
    let arr2 = [3,4,5]; 
    let comboArr = [...arr,...arr2]; 
    console.log(comboArr);

> Those 4 lines of code would yield [0,1,2,3,4,5]

Give an example of using the spread operator to add a new item to an array.

    let arr = [0,1,2]; arr = [...arr, 3];

Give an example of using the spread operator to combine two objects into one.

    let obj1 = { name: "inigo montoya", schtick: "You killed my father, prepare to die" };
    let obj2 = { name: "count rugen", schtick: "You've got six fingers on your right hand." };
    let clash = { ...obj1, ...obj2};
    // Then you can enter the two contestants into the thunderdome?

## How to Pass Functions Between Components

In the video, what is the first step that the developer does to pass functions between components?

> He made an increment function to handle the interaction when the user clicks the button.

In your own words, what does the increment function do?

> It....increments. It handles an event listener effect, essentially, updates the count total, then updates the state so the page will update the value after the click event has resolved.

How can you pass a method from a parent component into a child component?

> You can pass along a propery from parent to child, in this case he passed the method as a property by way of <Thing increment={this.increment}> and then the method is passed as a prop to be used by the child.

How does the child component invoke a method that was passed to it from a parent component?

> this.props.methodName(parameter)
