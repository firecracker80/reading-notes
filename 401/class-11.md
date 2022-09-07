# Reading Assignment 11

>## Spring App Basics
>
>A tutorial to walk you through the steps of using Spring. Then it goes into how to create a controller to handle HTTP requests, using the @Controller annotation. It goes on the explain each annotation used in the example controller:
> - @GetMapping - maps the request to the method
> - @RequestParam - binds the query parameter to the method; not required, if not present will set to default.
>
>To implement the method body, Spring uses Thymeleaf, which will render the server-side. Something I liked, the dev tools, to help minimize unnecesary time vortex of changing code, restart and refresh, by enabling the LiveReload. This will automatically refresh the browser, very handy.
>
>## Spring MVC and Thymeleaf
>
>Spring has model attributes they call, context variables. They are used within the model and access using the addAttribute method.
>
>Sending requests in Spring, is doen through a controller, which handles the routes. Very similar to using ThunderClient. You access your parameter by using the param prefix.
>
>Spring Beans! These are registered in the Spring Application Context. You can access them using the @Beans annotation.
>

>## Things I want to know more about...
>
>What exactly does a Spring Bean do?