# Reading Assignment 10

## Understanding the JavaScript Call Stack

>*What is a ‘call’?*
> - Used to call a method and pass an owner object as an argument (parameter). An object can use a method from another object by using the call() function.
>
>*How many ‘calls’ can happen at once?*
> - 1
>
>*What does LIFO mean?*
> - Last-In-First-Out
>
>*Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.*
>
> - ![Call Stack](301/callstack.jpg "Call Stack")
>
>*What causes a Stack Overflow?*
> - When a recursive function, a function that calls itself, does not have an exit point. The number of stack calls that the browser can handle before throwing a stack error is limited.
>

## JavaScript error messages

>*What is a ‘reference error’?*
> - An error occurs when you try to use a variable that hasn't been declared.
>
>*What is a ‘syntax error’?*
> - Whenever there is something that cannot be understood in terms of syntax.
>
>*What is a ‘range error’?*
> - These kinds of errors appear if you try to manipulate an object that has a length and give it an improper length.
>
>*What is a ‘type error’?*
> - These errors show up when you try to use or access a type (number, string, etc) that is incompatible. For example, when you try to access a property in a variable with an undefined type.
>
>*What is a breakpoint?*
> - A place where the program's code will stop working.
>
>*What does the word ‘debugger’ do in your code?*
> - Programmers can halt a program's execution, check the values of variables, go through the program's code line by line, and put breakpoints on certain lines of code or functions that, when reached, would cause the program to stop running immediately.
>

## Things I want to know more about...

Debugging