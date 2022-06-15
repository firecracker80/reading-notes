# Reading Assignment 5

## React Docs - Thinking in React

>*What is the single responsibility principle and how does it apply to components?*
> - It is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part(*from Wikipedia*). In lamens terms, each component should only have one responsibility.
>
>*What does it mean to build a ‘static’ version of your application?*
> - It means just type out the code, without all the interactivity that functionality involves (i.e. building state).
>
>*Once you have a static application, what do you need to add?*
> - Add interactivity. This is where building state comes in.
>
>*What are the three questions you can ask to determine if something is state?*
> - Is it passed in from a parent via props? If so, it probably isn’t state.
> - Does it remain unchanged over time? If so, it probably isn’t state.
> - Can you compute it based on any other state or props in your component? If so, it isn’t state.
>**Retreived from reactjs.org.**
>
>*How can you identify where state needs to live?*
> - Identify every component that renders something based on that state.
> - Find a common owner component (a single component above all the components that need the state in the hierarchy).
> - Either the common owner or another component higher up in the hierarchy should own the state.
> - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
**Retreived from reactjs.org**

<br/>

## Higher-Order Functions

>*What is a “higher-order function”?*
> - These are functions that operate on other functions as a arguments or as a return.
>
>*Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?*
> - It is returning an value m if m is greater than n. 
>
>*Explain how either map or reduce operates, with regards to higher-order functions.*
> - Map changes the existing array by applying the higher-order function, and then builds a new array from the returned values. Reduce repeatedly takes a single element from an existing array and combines it with the current values.

<br/>

## Things I want to know more about...

>React Bootstrap