# Readings: State and Props

## React lifecycle

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

> The render happens first

What is the very first thing to happen in the lifecycle of React?

> Mounting, but inside of that, the constructor function will be called before it mounts

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

> constructor - render - React updates - componentDidMount - componentWillUnmount

What does componentDidMount do?

> It invokes immediately after a component mounts, sounds like it's good for any network requests or if you need to initialize the DOM

## React State Vs Props

What types of things can you pass in the props?

> variables, initial values, I am thinking of it like a passed parameter into a function

What is the big difference between props and state?

> Props seems like a passed parameter, where as a state sounds like it's locally scoped and would need to be returned to pass outside of the component. I guess technically as soon as you pass a state onto something outside of that component, it becomes a prop? Honestly it just kind of sounds like variables in a function and the scope of those variables.

When do we re-render our application?

> When a state changes, it will trigger a re-render.

What are some examples of things that we could store in state?

> Just locally scoped things, so a form sounds like a good example. As the user interfaces with the form, we need to store what they're putting in that form before it gets submitted. I guess another thought is even something as simple as a text prompt at a command line, the things I've typed would be a state until I hit return, which would probably then turn that into a prop for other things to use?
