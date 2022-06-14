# Reading Notes 1

## Component-Based Architecture

>It breaks up a written code into smaller, functional, reusable pieces(AKA: Component-oriented software design).
> ### Advantages 
>
> - Reduced time in market and the development cost by reusing existing components.
> - Increased reliability with the reuse of the existing components.
> - Ease of deployment - easier to replace existing versions with no impact on the other components.
> - Ease of development
> - Reusable
> - Modification of technical complexity - using a component container.
> - Reliable
> - System maintenance and evolution - easy to change and updatewithout affecting the system.
> - Independent
(Retrieved from tutorialspoint.com.)
>
>A component is a software object that interacts with other components enhancing certain functionalities and sometimes a set of functionalities, that can be deployed independently.
> ### Three views
>
> - *Object-oriented* - viewed as a set of one or more cooperating classes, to identify all attributes and operations when implemented.
> - *Conventional* - a functional element/module that integrates internal data structures to implement the processing logic when invoked.
> - *Process-related* - builds from existing components that is maintained ina library. These pieces are selected from the library when software architecture is being formed.
>   - UI component - contains grids, buttons referred as controls, and utility components that expose specific subsets of function when used in other components.
>   - Resource intensive components - not accessed often, and have to be activated using the JIT (Just in time) approach.
>   - Invisible - distributed in enterprise business applications and internet web applications.
> ### Characteristics
>
> - Reusable
> - Replaceable - substituted with other similar components.
> - Not context specific
> - Extensible - can be extended to ilicit a new behavior.
> - Encapsulated - allowed to use its functionality without exposing any details of the internal processes, internal variables, or state.
> - Independent 

## What is PROPS?

>It's a keyword in React used to pass data between components in a undirectonal flow.
>
>Read-only type data that shouldn't change be changed by a child component. You can, pass this data to the child component.

## Things I would like to know more about...

>I want to learn how to pass images between components. I tried this evening, and while I had all the parts, I could not succeed.