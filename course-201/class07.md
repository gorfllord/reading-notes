# Object-Oriented Programming, HTML Tables

### Domain Modeling

Explain why we need domain modeling.

> Domain modeling sets up your workflow and gives you a rough idea as to how to handle the problem at hand. It sets you up to have a good outline so you can start writing your code with those methods in mind.

### HTML Table Basics

Why should tables not be used for page layouts?

> Tables should be used for table-purposes. You can more efficiently use CSS to set up a page layout, and using tables for page layouts makes accessibility more clunky.

List and describe 3 different semantic HTML elements used in an HTML \<table>.

> \<td> gets you table data, which is essentially the thing going into the cell. \<tr> makes a new table row, and acts as a parent container for td's. \<th> makes a cell have a heading, which is especially helpful for defining your columns and rows or making other important cells stand out.

### Introducing Constructors

What is a constructor and what are some advantages to using it?

> a constructor allows you to easily and more efficiently build multiple objects, especially if they would share a lot of code might might just have a few stored values be the differences between them. It saves you from having extra lines of code and streamlines the whole darn process.

How does the term this differ when used in an object literal versus when used in a constructor?

> this in an object refers to the object as the source of the value, function, etc. that follows. It allows you to use self-referential code to streamline.
> Using constructors, before you can fully utilize 'this' you need to bind it to the new object, like this.name = name, pulling the name from the argument being passed in. This way you can essential automate the process of building your objects with the constructor.

### Object Prototypes Using A Constructor

Explain prototypes and inheritance via an analogy from your previous work experience.
NOTE: This is a very common front end developer interview question

> You can use Object.create to make an object, and it essentially slots into the "prototype" slot with the new name that you've made, inheriting it's properties and passing in values as it's being created. It's kind of like a blueprint, from what I've gathered, but that's mostly because I had to look up additional material to understand it.
