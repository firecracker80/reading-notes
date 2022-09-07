# Reading Assignment 17

>## Spring Boot and OAuth2
>
>Spring Boot:
> - *simple:* a very basic static app with just a home page and unconditional login via Spring Boot’s OAuth 2.0 configuration properties (if you visit the home page, you will be automatically redirected to GitHub).
>
> - *click:* adds an explicit link that the user has to click to login.
>
> - *logout:* adds a logout link as well for authenticated users.
>
> -  *two-providers:* adds a second login provider so the user can choose on the home page which one to use.
>
> - *custom-error:* adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API.
><!-- >Retreived from spring.io tutorials -->
>All app use, and can be viewed, on localhost:8080. The OAuth 2.0, will allow the user to login/signup using GitHub or Google. When creating the app, add Springs Security and this will allow you to use OAuth 2.0 as a "social login" by default.
>
> - GitHub - must add a new GitHub app, an include name, description, and homepage.
>To configure the security of your app, Spring uses WebSecurityConfigurerAdapter with the annotation @SpringBootApplication. This will configure the security filter chain.
>
> -You want to allow:
>
>   - / since that’s the page you just made dynamic, with some of its content visible to unauthenticated users
>
>   - /error since that’s a Spring Boot endpoint for displaying errors, and
>
>   - /webjars/** since you’ll want your JavaScript to run for all visitors, authenticated or not
><!-- >Retreived from spring.io tutorial. -->
>
>To logout, requires using the Cross Site Request Forgery (CSRF). It's the token that provides protection for the current session, and is available as a cookie. 

>## Things I want to know more about...
>What other framewroks are available as an alternative to Spring?