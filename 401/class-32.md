# Reading Assignment 32

## Intro to Serverless
>
>Def: A cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers.
><!-- (Retreived from hackernoon.com)  -->
>A serverless application allows you to focus more on the productivity and applicability of the application than on the infrastructure. Though this sounds amazing, serverless may not always be the best choice.
>
>It operates as an event-triggered, ephemeral, stateless computing container, which is completely maintained by the cloud provider. This takes the responsibility of managing the servers out of your hands and onto the cloud vendors.
>
>### Advantages
>
> - Reduced costs for provisioning and maintaining servers.With serverless, you are only charged for the amount of executions.
> - Because you pay per execution, setting up your environment will be much easier because you won't have to set up your dev environment.
> - Scaling is automatic.
>
>### Disadvantages
>
> - Networking. You cannot access the "server" from your IP. Serverless functions via private APIs, therefore you must set up an API gateway.
> - 3rd Party Dependencies. Projects will depend on external libraries that aren't already built in and can be heavy without system-level access.
> -It has a strict 300 second timeout limit, which can be a problem for applocations with variable executions.
> - When scaling, we will not have control, making it hard to address and mitigate potential errors.

## AWS Amplify
>
>Allows a developer to build a frontend and then fully build, ship, and host a full-stack application. With it comes the full force of what AWS offers as a backend "server" without the necessity of cloud experience.
>
>Amplify has hundreds of features you can add to your web or mobile app and it allows you to deploy and scale fast. You have their open source libraries at your disposal and can manage your your app from your command line after installing their CLI.

## GraphQL Intro
>
>Uisng DynamoDB, GraphQL creates database tables following a schema. It automatically creates an id as a key to the database. It uses an API to perform create, read, update,delete, and list operations.
<!-- Retreived from amplify docs. -->

> 1. What makes an API RESTful?
>
> - It is an architectural design for an API that makes use of HTTP requests to access and consume data.
>
> 2. What is the benefit of using GraphQL? Any downsides?
>
> - Retrieves only precise and particular data in a single request.
>
> 3. Describe “serverless” to a new 301 Code Fellows student.
>
> - "Serverless" is slightly deceptive because there are still servers involved in backend services. The difference is the vendor is in charge of all infrastructure and server space issues allowing developers to work on their projects without having to worry about servers.

## Things I want to know more about

>Amplify features.
