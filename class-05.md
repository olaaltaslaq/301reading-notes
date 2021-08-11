# Thinking in React

![tir](https://i.morioh.com/201022/2f6459ee.webp)

- ## How would you break a mock into a component hierarchy?

*1. draw boxes around every component (and subcomponent) in the mock and give them all names.*

*2. Use the same techniques for deciding if you should create a new function or object.*

<hr>

- ## What is the single responsibility principle and how does it apply to components?

*which mean that the component should ideally only do one thing.*

<hr>

- ## What does it mean to build a ‘static’ version of your application?

*Have a library of reusable components that render our data model, it requires a lot of typing and no thinking, we can do it using props to pass data and never use states.*

<hr>

- ## Once you have a static application, what do you need to add?

*Use states to make the UI interactive, key to do this is DRY.*

<hr>


- ## What are the three questions you can ask to determine if something is state?

*1. Is it passed in from a parent via props? If so, it probably isn’t state.*

*2. Does it remain unchanged over time? If so, it probably isn’t state.*

*3. Can you compute it based on any other state or props in your component? If so, it isn’t state.*

<hr>

- ## How can you identify where state needs to live?

***Is it passed in from a parent via props? If so, it probably isn’t state.***

*1. Identify every component that renders something based on that state.*

*2. Find a common owner component (a single component above all the components that need the state in the hierarchy).*

*3. Either the common owner or another component higher up in the hierarchy should own the state.*

*4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.*

<hr>

**HI ... my name is Ola 23 years old i'm a Nutritionist and my computer operating system version number is windows 10 and i'm so excited for this course because i want to learn something very important to me**

*click on the [link](https://github.com/olaaltaslaq) to find my GitHub*

