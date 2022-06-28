# Reading Assignment 12

## Status Codes Based On REST Methods

>*In your own words, describe what each group of status code represents:*
>
> - 100’s = Informational status codes that let the client know that the header part of the request was received and that the server will try to satisfy the client's request.
> - 200’s = Success codes that inform the client that their request has been granted.
> - 300’s = Redirection codes that let the customer know that the anticipated location is no longer home to the requested resource.
> - 400’s = Client error codes tha concern erroneous requests that clients send to servers.
> - 500’s = Server error codes that point to issues with overloaded servers.
>
>*What is a status code 202?*
> - Tells the client that the request was accepted, but that processing will be done at a later time.
>
>*What is a status code 308?*
> - Tells the client to stop using the current URL and instead use a different one to access the resource.
>
>*What code would you use if an update didn’t return data to a client?*
> - 204
>
>*What code would you use if a resource used to exist but no longer does?*
> - 204
>
>*What is the ‘Forbidden’ status code?*
> - 403
>

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

>*Why do we need to pull our MongoDB database string out of our server and put it into our .env?*
> - 
>
>*What is middleware?*
> - Software that connects an operating system or database to applications.
>
>*What does app.use(express.json()) do?*
> - It processes incoming JSON requests and stores the processed data in the req variable.
>
>*What does the /:id mean in a route?*
> - It is an optional URL parameter that can have any name.
>
>*What is the difference between PUT and PATCH?*
> - When a client uses the PUT method to alter a resource, the entire resource is updated. PATCH is a method of resource modification where the client transmits updated partial data without changing the complete data.
>
>*How do you make a default value in a schema?*
> - Using the default keyword, you can provide a default value for an item.
>
>*What does a 500 error status code mean?*
> - Internal server error.
>
>*What is the difference between a status 200 and a status 201?*
> - 200 indicates that the request was received, understood, and is now being handled. 201 signifies that a request was successful, leading to the creation of a resource.
>

## Things I want to know more about...

More on how to resolve these error codes.