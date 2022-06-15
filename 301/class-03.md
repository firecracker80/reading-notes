# Reading Assignment 3

## Lists and Keys

>*What does .map() return?*
> - It takes an array, changes or doubles its value and then returns a new array.
>
>*If I want to loop through an array and display each value in JSX, how do I do that in React?*
> - You have to assign a `key`. It helps React identify which items or information has changed, added, or removed. 
>
>*Each list item needs a unique* **id.**
>
>*What is the purpose of a key?*
> - A `key` is assigned to the elements within the array to stabilize their identity. Its purpose is to tell React that those components don't get passed into a component.

<br/>

## How to Use the Spread Operator (…) in JavaScript

>*What is the spread operator?*
> - A quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
(*Information retreived from Coding at Dawn.*)
>
>*List 4 things that the spread operator can do.*
> -Concatenating or combining arrays
> - Adding an item to a list
> - Adding to state in React
> - Using Math functions
>
>*Give an example of using the spread operator to combine two arrays.*
> - Combining a subject with a concept. You define both subject and concept as variables within curly brackets, then define another variable that combines both using `...`before each variable within the curly brackets.
>
>*Give an example of using the spread operator to add a new item to an array.*
> - Lets say we have an existing array of the names of all the children in a family, then another child is born, you define another variable as an a new array,first adding the new child name followed by the `,...existing array` within curly brackets.
>
>*Give an example of using the spread operator to combine two objects into one.*
> - What better example than 2 single parents getting married. Both are defined to include their children, then a third object, the marriage, is defined combining both parents with their children, as follows `{...mom, ...dad, family: "all their names"}`

<br/>

## How to Pass Functions Between Components

>*In the video, what is the first step that the developer does to pass functions between components?*
> - He created an increment function to pass in the person or name, that already exists within the state.
>
>*In your own words, what does the increment function do?*
> - This function loops through the list of name within the state, and once it matches, it adds to that name, returning a new array with a new count.
>
>*How can you pass a method from a parent component into a child component?*
> - Step 1: Create a parent and child component.
> - Step 2: Create a state to store the data.
> - Step 3: Import the child component into the parent component.
> -Step 4: Return
> - Step 5: Create a function.
> - Step 6: Create a button to trigger the function in step 5.
>
>*How does the child component invoke a method that was passed to it from a parent component?*
> - Using props().

<br/>

## Things I want to know more about...

>I actually would like to practice more creating the compponents, applying the spread operator, and invoking them to change the info.