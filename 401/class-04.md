# Reading ssignment 4

## Java OO Tutorial

>*Object*
>Software bundle that contains data that is related in state and behavior.
>State is stored in fields, exposing behavior through the use of methods. These methods function based on the objects internal state. Object to object communication is its main mechanism.
>Data encapsulation - hides internal state and performs through the object's method.
>Benefits to bundling code:
> - Modularity: The writing and upkeep of an object's source code can be done separately from that of other objects. Once formed, an item is simple to move across the system.
> - Information-hiding: The specifics of an object's internal implementation are kept secret from the outer world by interacting only with its methods.
> - Code re-use: You can use an object that already exists in your program. This enables experts to create, test, and debug intricate, task-specific objects that you may use with confidence in your own code.
> - Pluggability and debugging ease: You can easily remove an object from your program and plug in another one as a substitute if it turns out to be problematic.
>*Class*
>A framework used to create objects.
>
>## Java Classes
>
> 1. Consider the following class:
>
>public class IdentifyMyParts {
    public static int x = 7; 
    public int y = 3; 
}
> a. What are the class variables?
>
> - x
> b. What are the instance variables?
>
> - y
> c. What is the output from the following code:
>
> - It will throw a series of errors, because it is missing identifiers and some of the syntax is wrong.
>
>IdentifyMyParts a = new IdentifyMyParts();
>IdentifyMyParts b = new IdentifyMyParts();
>a.y = 5;
>b.y = 6;
>a.x = 1;
>b.x = 2;
>System.out.println("a.y = " + a.y);
>System.out.println("b.y = " + b.y);
>System.out.println("a.x = " + a.x);
>System.out.println("b.x = " + b.x);
>System.out.println("IdentifyMyParts.x = " + IdentifyMyParts.x);
>
> 2. What's wrong with the following program?
>
> - The Rectangle myRect is not declared.
>public class SomethingIsWrong {
    public static void main(String[] args) {
        Rectangle myRect;
        myRect.width = 40;
        myRect.height = 50;
        System.out.println("myRect's area is " + myRect.area());
    }
}
> 3. The following code creates one array and one string object. How many references to those objects exist after the code executes? Is either object eligible for garbage collection?
>
> - After this object exceutes, 1 reference will exist (String[] students = new String[10]), the remaining 3 will be eligible for garbage collection.
>...
>String[] students = new String[10];
>String studentName = "Peter Parker";
>students[0] = studentName;
>studentName = null;
>...
> 4. How does a program destroy an object that it creates?
>
> - It automatically destroys an object when it no longer has references.
>
>## Things I want to know more about...
>Maybe not so much know more about, but simply understand binary and decimal numbers. I did the reading for this, but it went over my head.