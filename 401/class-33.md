# Reading Assignment 33

## One-to-many and many-to-one connections using GraphQL in AWS Amplify
>
>### @hasMany

>Used to create a one-directionalone-to-many relationship between two models, to generate quieries and mutations to retrieve data from the source.
>It allows you to query the associated model from the source model by configuring a default secondary index on the related table. It can be customized with @index annotation on the field in the related table.
><!-- Retreived from amplify docs. -->

## CompletableFuture in Java
>
>### Asynchronous Computation in Java
>
>In Java 5, the Future interface was introduced to act as the output of an asynchronous calculation, but it lacked the ability to combine these computations or address potential faults.
>
>The CompletableFuture class first appeared in Java 8. It addressed the shortcomings of the Future interface with the CompletionStage interface. This interface specifies the terms of an asynchronous computing step that can be added to other phases.It contains 50 different methods for creating, merging, and carrying out asynchronous computation steps, to include failures. CompletableFuture functions as both a building block and a framework.
>
>### Using CompletableFuture as a Simple Future
>
>To represent a future outcome, we can build an instance of this class with a no-arg constructor, provide it to the consumers, then complete it at a later time using the complete method.

> 1. Describe asynchronous actions in your own words.
>
> - An asynchronous action is when data request and response can be done at varying times.
>
> 2. What is the benefit of asynchronous methods?
>
> - One primary benefit is better performance and responsiveness of the application.

## Things I want to know more about
>Implementation of the relationships.