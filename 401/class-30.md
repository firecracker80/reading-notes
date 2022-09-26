# Reading Assignment 30

## AWS Amplify
>
>Developers can create full stack applications that seamlessly interface with the cloud using the toolkit known as AWS Amplify. Developers can use it to quickly setup, test, launch, and grow production-ready apps while spending little time concentrating on the specifics.
>
>Following its formal launch in November 2017, AWS Amplify immediately gained traction among full stack developers. It sought to differentiate itself from competing rapid development, full stack hosting providers like Google Firebase and Netlify by providing direct feature interaction with AWS' backend capabilities. 
>
>Although you can use it solely for its capacity to construct a backend. It is mostly targeted at full stack apps. Amplify's key advantage right now is that it makes it simple to add things like storage, authentication, monitoring, and pubsub features. It's a useful tool because it enables application functionality to be added without the developer having to know which AWS services to use to accomplish that feature. Behind the scenes Amplify makes use of AWS CloudFormation, a tool, to fast enable you to add additional components. CloudFormation is an Infrastructure as Code tool that enables you to specify template files that tell AWS which components you require for your application and then let AWS handle the labor-intensive task of providing those services.
>
>Some examples of AWS technologies:
> - Amazon Cognito - Authentication and Authorization.
> - AWS Appsync or API Gateway - GraphQL or REST/HTTP based, respectively.
> - Amazon S3 - raw object storage.
> - Amazon Pinpoint - analytics.
> 
>You will primarily communicate with Amplify through the CLI. Use the commands, *amplify configure and amplify init* to set up a new project. An api is a crucial element for practically any application, by using the command "amplify add api" you can easily add one. 
>
## Pros and Cons
><!-- Retrieved from beabetterdev.com AWS Amplify article. -->
>### Pros
> - Getting Started Quickly
> - Fast Development Cycles
> - Shielding From the Complexity of AWS
>
>### Cons
> - You Don’t ‘Really’ Learn AWS
> - Collaboration Can Be Frustrating
> - Stepping Outside The Box
> - Potential For Surprise Bills

> 1. What are a few alternatives to AWS Amplify? What are the differences? What are the tradeoffs?
> - GitHub - doesn't have an infrastructure, can't preview site with every push, incompatible with static site generators. The tradeoffs are 100 GB of bandwidth a month and it's carbon neutral.
> - Salesforce Heroku - supports instant rollbacks to any version, send notifications through slack, have extensions. The tradeoffs are it only supports a maximum of 25 team members on their free version, integrates with postgres, no data storage, no push notifications, nor machine learning.
> - Azure Moble Apps - no push notifications, build time per deployment is 15 min faster, have durable background functions, integrates with GitHub, and is carbon neutral. The tradeoffs are, it supports 100GB of bandwidth per month, supports serverless function custom handlers, triggered timer functions, and allows for pre-configured providers for authentication.
> 2. What AWS Region is closest to you?
> Sao Paolo, Brazil

## Things I want to know more about...
>The limits for collaboration.
