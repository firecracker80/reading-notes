# Reading Assignment 6

>## Java OO Tutorial (review Object and Class, read the rest)
>
>1. Real-world objects contain *state* and *behavior*.
>2. A software object's state is stored in *fields*.
>3. A software object's behavior is exposed through *methods*.
>4. Hiding internal data from the outside world, and accessing it only through publicly exposed methods is known as data *encapsulation*.
>5. A blueprint for a software object is called a *class*.
>6. Common behavior can be defined in a *superclass* and inherited into a *subclass* using the *extends* keyword.
>7. A collection of methods with no implementation is called an *interface*.
>8. A namespace that organizes classes and interfaces by functionality is called a *namespace*.
>9. The term API stands for *Application Programming Interface*?
>
>## Java Inheritance & Interfaces Tutorial
>
>1. What methods would a class that implements the java.lang.CharSequence interface have to implement?
> - *charAt , subSequence, toString, and length.*
>
>2. What is wrong with the following interface?
>     public interface SomethingIsWrong {
        void aMethod(int aValue){
          System.out.println("Hi Mom");
        }
      }
      > - *There isn't an implements cause.*
>
>3. Fix the interface in question 2.
>     public interface SomethingIsWrong 
>       *implements "interface to implement"*{
        void aMethod(int aValue){
          System.out.println("Hi Mom");
        }
      }
>4. Is the following interface valid?
>      public interface Marker {
      }
> *It valid even though it is empty, because it doesn't require methods.*
>
>1. Consider the following two classes:

public class ClassA {
    public void methodOne(int i) {
    }
    public void methodTwo(int i) {
    }
    public static void methodThree(int i) {
    }
    public static void methodFour(int i) {
    }
}

public class ClassB extends ClassA {
    public static void methodOne(int i) {
    }
    public void methodTwo(int i) {
    }
    public void methodThree(int i) {
    }
    public static void methodFour(int i) {
    }
}
a. Which method overrides a method in the superclass?
> - *Method two.*
b. Which method hides a method in the superclass?
> - *Method four.*
c. What do the other methods do?
> - *They're going to cause errors when you attempt to compile.*
>
>2. Consider the Card, Deck, and DisplayDeck classes you wrote in Questions and Exercises: Classes. What Object methods should each of these classes override?
> - *The equals, hashCode, and the toString methods.

## Things I would like to know more about...
>I am still unclear on the annotations. I would have liked to see more examples on those.