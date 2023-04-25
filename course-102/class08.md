# Operators and Loops

What is an expression in JavaScript?

> An expression is a chunk of code that resolves into a value of some sort. Usually they're using operators, like x = 42 or howManyBells = steeples - 1

Why would we use a loop in our code?

> Loops are great if you want to do something a few times until a particular outcome is achieved. Or maybe you need to repeat some code X number of times and don't want to write it out that many times. You can do something like: 
> let n = 4;
> while(n > 0){
> doStuff();
> n--;   
> }
> Voila! You did a doStuff() 4 times before it reached it's exit strategy.

When does a for loop stop executing?

> For loops keep going until the specified condition returns the boolean FALSE. You can set your condition to whatever you might need as long as it can return a boolean value.

How many times will a while loop execute?

> The while loop will go until its specified condition returns false. Like the above example, while(n > 0){} goes until n <= 0. Typically this would be achieved by changing the value of n within the loop. The other option for either the for loop or the while loop to stop executing is to use a break statement.
