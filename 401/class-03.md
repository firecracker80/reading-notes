# Reading Assignment 3

## Java Primitives versus Objects
>
>NOTES:
>Two-fold type system - primitives and references.
>Wrapper classes can't be changed(immutable).
>Autoboxing - converting primitive to reference if different from declared one.
>Unboxing - converting reference to primitive if different from declared one.
>
>*Single Item Memory Footprint*
>
> Primitives:
>
> - boolean – 1 bit
> - byte – 8 bits
> - short, char – 16 bits
> - int, float – 32 bits
> - long, double – 64 bits
>//Retreived from baeldung.com
>
>Variables can be accessed faster becuase they live in the stack. References are accessed slower because they live on a heap.
>
>References (wrapper class):
>
> - Boolean – 128 bits
> - Byte – 128 bits
> - Short, Character – 128 bits
> - Integer, Float – 128 bits
> - Long, Double – 192 bits
>//Retreived from baeldung.com
>
>*Memory Footprint for Arrays*
>
>Grouped into families, depending on the number of elements in an array.
>
> - long, double: m(s) = 128 + 64 s
> - short, char: m(s) = 128 + 64 [s/4]
> - byte, boolean: m(s) = 128 + 64 [s/8]
> - the rest: m(s) = 128 + 64 [s/2]
>//Retreived from baeldung.com
>
>*Performance*
>
>Depends on the following factors:
>
> - Hardware - runs the code
> - Compiler
> - State of the virtual machine
> - Activity of the processes in the operating system
>
>*Default Values*
>
>Numeric primitives = 0
>Boolean = false
>Char = \u0000
>Wrapper classes = null

## Exceptions In Java
>
> 1. Is the following code legal?
> - Yes
>
>     try {
>
>     } finally {
>
>     }
> 2. What exception types can be caught by the following handler?
>
> - Checked exception type.
>
>     catch (Exception e) {
>
>     }
> 3. What is wrong with using this type of exception handler? 
>
> - The catch parameter is final, and will not allow values to be assigned within the catch block.
> 4. Is there anything wrong with the following exception handler as written? Will this >code compile?
>
> - This exception handler is correct and will compile.
>
>       try {
>
>       } catch (Exception e) {
>
>         } catch (ArithmeticException a) {
>
>       }
>
> 5. Match each situation in the first list with an item in the second list.
>
> A. int[] A;
>     A[0] = 0;
> B. The JVM starts running your program, but the JVM can't find the Java platform classes.(The Java platform classes reside in classes.zip or rt.jar.)
> C. A program is reading a stream and reaches the end of stream marker.
> D. Before closing the stream and after reaching the end of stream marker, a program tries to read the stream again.
> 1. *D* - error
> 2. *C* - checked exception
> 3. *B* - compile error
> 4. *A* - no exception

## Using Scanner to read in a file in Java
>
>NOTES:
>Scanner breaks down formatted input into tokens, using white space.
>Supports primitive types except char.

## Things I want to know more about...
>The types of exceptions and and howand when to properly implement them.