# Forms and JS Events

# HTML Forms

Why are forms so important in web development?

> Forms let you take input from the user.

When designing a form, what are some key things to keep in mind when it comes to user experience?

> You want to make sure you use semantic elements like label and use their name property to make sure the context in clear and concise, that way screen reader users can have the label read to them to specify the input that is desired. Also if you specify the the input in the label, if you click the label text it will select the corresponding input. Especially useful for things like radio buttons.

List 5 form elements and explain their importance.

> label will tack on a label to tell the user what the input requested is; input is the part where the user can input their response, be it text or radio button or check box or whatever input type you've utilized; button is great for having a submit button, you can just specify the 'submit' type, and as long as within the form tag, it should do the trick; textarea is an alternative to the input element, where input is a void element textarea is not, so the way you can define default text is different; the fieldset element allows you to group answers together, like if you have multiple options with radio buttons, that way the one you choose will return properly from the context you desire.

# Learn JS - Introduction To Events.

How would you describe events to a non-technical friend?

> Events lets you tell JavaScript to listen out for something to then respond to that thing, like if you wanted it to wait for a user to click on something before it did the thing you wanted that button to do, like change the background or link to a part of a page

When using the addEventListener() method, what 2 arguments will you need to provide?

> The first argument is the input you are listening for, the second argument is what to do when that condition has been met

Describe the event object. Why is the target within the event object useful?

> an event object allows you to have some short-hand on the 'what the thing does' part of the addEventListener method. The 'target' is a way to specify that it happens to the thing triggering the event, that way you can use the same code on multiple elements.

What is the difference between event bubbling and event capturing?

> Event bubbling is inside-out, event capturing is outside-in, as far as order-of-operations of what element will be chosen to apply, since technically a button is in a div is in a section, all of them technically are where you're clicking. event bubbling lets you prioritize button, event capturing allows you to prioritize section.
