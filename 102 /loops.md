# Expressions and Operators


> ## Expressions
>
> This is a valid unit of code that resolves to a value. There are two types, one that will assign value to a variable and another that will resolve to a value.
>
><br/>
>
> ## Operators
>
> There are several types of operators that can be both binary and unary. The conditional operator is a special ternary operator.
>
> - Binary - requires one operand before and after the operator.
> - Unary - requires one operand before OR after.
> - Ternary - takes 3 operands, meaning the operator can have 1 of 2 values based on the condition defined.
>
> ### Assignment
>
> These assign value to the left operand based on the right operand. (Reference "Programming" page for operators.)
>
> Avoid assignment chains, because it present with undesired behavior.
><br/><br/>

<br/>

# Loops and Iteration

> Loops allow you to do something repeatedly. They determine a start and end of a loop.
>
> ## for statement
>
> This type of loop will repeat until the condition is met or becomes false.
>
> ## do...while statement
>
> This loop will repeat until a specific condition is metor becomes false.
>
> The do statement is always executed one time before the condition is checked. One checked, if true, the statement will execute again. Once the condition returns false, the statement will stop being executed.
>
> ## while statement
>
> This loop will continue to execute for as long as the statement evaluates as true.
>
> ## labeled statement
>
> It's a statement that has an identifier that will allow you refer to it somewhere else in the program. (i.e break or continue).
>
> ## break statement
>
> This terminates the loop. When using break without a label, it terminates the innermost enclosing of the loop. When using break with a label, it terminated the specifically labeled statement.
>
> ## continue statement
>
> This can be used to restart a loop. When using continue without a label, the innermost enclosing is terminated, but it continues onto the following iteration. In others, only part of the loop is terminated, the rest with continue to run. When using a label, it works the same way it would in a break statement.
>
> ## for...in statement
>
> This iterates a specific variable over properties of an object. So, for each property, JS will execute a specified statement.