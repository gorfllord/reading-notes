# Debugging

### Troubleshooting JavaScript.

Name some key differences between a Syntax Error and a Logic Error.

> Syntax errors are usually spelling mistakes or calling something by the wrong name. Maybe you changed a variable name and forgot to find it everywhere it was being used? Logic errors are when the logic doesn't follow given what's being used. You can have everything spelled right, but if you're using it wrong, you'll get a logic error.

List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.

> I ran into some syntax errors becaused I capitalized something I wasn't supposed to or vice versa. Definitely had some logic errors when I was using a method incorrectly. 

How will this topic continue to influence your long term goals?

> When developing, you will always inevitably need to debug something, so it's best to understand all of the tools to help you figure things out. Even just the fact that it'll tell you what line of code is triggering the error can save you TONS of time looking.

### The JavaScript Debugger.

How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?

> I would describe it as a tool that helps point out where your code might not be working. It'll show the code you have and let you try different commands or pause it at a certain point in the code to help you isolate just where it all went wrong.

Define what a breakpoint is.

> A break point is a line of code where you can tell it to pause so you can see what has been called so far. Especially useful if you're trying to find out where your code breaks. We've been using console logs to kind of serve this purpose, but it's helpful to be able to just hit pause on the code sometimes.

What is the call stack?

> The call stack is essentially the flow of code being activated. My first thought is to think of how CSS flows from top to bottom. JavaScript does that but doesn't, as if something invokes a function that comes later in the code, I'm pretty sure it'll still call that function? But assigning variables definitely is time-sensitive in the code. I tend to think of it like a suped-up order of operations. I also can't help but think of the idea of "the stack" in Magic the Gathering, which is essentially what dictates what cards and abilities activate when, so that when you need to be ULTRA specific, you can comb through and figure out the One True Logic that is happening.
