# Reading Assignment 1

## Java Basics

### Variables

> 1. The term "instance variable" is another name for *non-static fields*.
> 2. The term "class variable" is another name for *static fields*.
> 3. A local variable stores temporary state; it is declared inside a *local variables*.
> 4. A variable declared within the opening and closing parenthesis of a method signature is called a *parameter*.
> 5. What are the eight primitive data types supported by the Java programming language?
> - *byte, int, short, long, double, float, boolean, char.*
> 6. Character strings are represented by the class *literal*.
> 7. An *array* is a container object that holds a fixed number of values of a single type.

### Operators

> 1. Consider the following code snippet.
arrayOfInts[j] > arrayOfInts[j+1]
> - Which operators does the code contain? *Relational*
> 2. Consider the following code snippet.
int i = 10;
int n = i++%5;
> - What are the values of i and n after the code is executed? *6*
> - What are the final values of i and n if instead of using the postfix increment operator (i++), you use the prefix version (++i))? *7*
> 3. To invert the value of a boolean, which operator would you use? *Ternary*
> 4. Which operator is used to compare two values, = or == ? *Conditional*
> 5. Explain the following code sample: result = someCondition ? value1 : value2;
> - *If the result equals someCondition assign it value1, if not assign it value2.

### Expressions, Statements, and Blocks

> 1. Operators may be used in building *expressions*, which compute values.
> 2. Expressions are the core components of *statements*.
> 3. Statements may be grouped into *blocks*.
> 4. The following code snippet is an example of a *compound* expression.
> - 1 * 2 * 3
> 5. Statements are roughly equivalent to sentences in natural languages, but instead of ending with a period, a statement ends with a *semi-colon*.
> 6. A block is a group of zero or more statements between balanced *braces* and can be used anywhere a single statement is allowed.

### Control Flow Statements

> 1. The most basic control flow statement supported by the Java programming language is the *if-then* statement.
> 2. The *switch* statement allows for any number of possible execution paths.
> 3. The *do-while* statement is similar to the while statement, but evaluates its expression at the *bottom* of the loop.
> 4. How do you write an infinite loop using the for statement?
> - *for(variable){
  //code to be evaluated
}
> 5. How do you write an infinite loop using the while statement?
> - *while (true){
  //code to be evaluated
}*

### What does it mean to compile code?

>From the Reddit thread, I understood that when asked to compile the code, we are expected to take the existing code and convert it into a language the machine can understand. It doesn't necessarily guarantee that it will work, but the machine can understand it.

### Reading Java Documentation

> NOTES:
>Java surfaced in 1995, with a library of 250 programs that later grew to over 4000 programs. The library is called, Application Programming Interface(API).
>To write Java programs, you need four tools:
> - A Java compiler
> - A Java Virtual Machine.
> - The Java API.
> - The Java API documentation.
> //Retrieved from dummies.com.
> In Java, a direct instruction that tells the computer to do something is called a statement. 
> - Everything starts with classes, everything is enclosed in classes, and everything is based on classes.
>//Retrieved from dummies.com.
>A method can only call one kind of action, while the statement is a type of method that can call various kinds of statements.
>System.out.println method displays text.
>NoClassDefFoundError - pops up when you have errors in your code when you try to compile it. Look for errors in the file.
>NoSuchMethodError - this is signaling a misspelling or capitalization of a method name that is inconsistent.
>Cannot Resolve Symbol - misspelling of capitalization of identifiers and keywords.
>Expected ';' (Or Expected Something Else) - go through the code and make sure your statements and declarations end with a semi-colon.

## Things I want to know more about...
>Debugging error messages. As I completed the prework, I ran into errors i simply did not understand nor was able to decipher.