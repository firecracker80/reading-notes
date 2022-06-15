# Reading Assignment 4

## React Docs - Forms

>*What is a ‘Controlled Component’?*
> - Value within an input form element controlled by React.
>
>*Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.*
> - Wait, because React is going to look at the existing virtual DOM and it will have the new virtual DOM, it will compare, combine, and re-render. If you update as they enter, your state will become polluted, then it won't work anymore.
>
>*How do we target what the user is entering if we have an event handler on an input field?*
> - You target the value entered.

<br/>

## The Conditional (Ternary) Operator Explained

>*Why would we use a ternary operator?*
> - To shorten the block of code and for decision making.
>
>*Rewrite the following statement using a ternary statement:*
>`if(x===y){
  console.log(true);
} else {
  console.log(false);
}`
>
> - x===y ? 'true' : 'false'

## Things I want to know more about...

> While I have a general idea of why not to update state immediately, I am curious if it is done, why? I am not clear on the purpose of why vs. why not.