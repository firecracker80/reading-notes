# Reading Assignment 10

> ## Error Handling & Debugging
>
> - *Execution Context:*
>   - Global context - code that scripts outside a function.
>   - Function context - code run within a function
>
> - *Variable Scope:*
>   - Global scope - variable declared outside  function that can be used anywhere.
>   - Function-level scope - variable declared within a function nd can only be used in that function.
>
>A **stack** is a function code stacked one on top of another. It has to be stack in order, otherwise the returned data will not make sense.
>
>*Error objects:*
> - Error - generic.
> - SyntaxError -syntax wasn't followed.
> - ReferenceError -tried to refernce an undelared var.
> - TypeError - unexpected data type that can't be coerced.
> - RangeError - # not in an acceptable range.
> - URIError - methods used incorrectly (i.e encodeURI(), decodeURI()).
>
>Error messages will guide you in finding where the error is. Set breakpoints to give yourself time to pause the execution and check the stored values. It also allows you to test smaller pieces of the function.
>
>*Console Methods:*
> - .log -write data from the scriptto the console.
> - .info - general info.
> - .warn - warnings.
> - .error - holds errors.
> - .group - group messages together.
>
>The debugger keyword automatically creates a breakpoint. You can also set it within a conditonal statement, so thatwhen the code executes, it does so based on whether a condition was met.
>
>*Handling Execptions*
> - Try - a function used to test code that has been identified to potentially fail. Must always contain a catch, finally, or both.
> - Catch - initiates when the try code block throws an exception.
> - Finally - this set of code will whether the try block succeeds or fails.

<br/>

## Things I want to know more about...

>JS has been very confusing as difficult for me. I want to spend more time with everything JS. I feel that more exposure and hands-on practice will help me in becoming proficient at it.