# Reading Assignment 13

>## Related data in Spring (“One-to-Many Relationship”)
>
>Defined by using the @OneToMany and @ManyToOne annotations, and can be customized using the @RestResource annotation. The respective classes will need to be set up as entities as representation of the respective relationship. A repo will need to be created, to save the data entered. When a POST request is made, this will allow you to make the association, and verify it by using the GET method which will return a JSON file.
>
>## Baeldung: Spring Integration Testing
>
>Integration testing is important because it allows for thetesting of the end-to-end behavior of the system. Spring uses JUnit to run tests. The @WebAppConfiguration preps the web application configuration, by loading all the beans and controllers into the context. This allows for @Autowiring of the web application context. Spring MVC testing is supported by MockMvc. All web application beans are contained and made testable by it.
> - Methods available:
>   - perform() method will call a GET request method, which returns the ResultActions. Using this result, we can have assertion expectations about the response, like its content, HTTP status, or header.
>   - andDo(print()) will print the request and response. This is helpful to get a detailed view in case of an error.
>   - andExpect() will expect the provided argument. In our case, we're expecting “index” to be returned via MockMvcResultMatchers.view().
>
> - Verify Response Body:
>   - andExpect(MockMvcResultMatchers.status().isOk()) will verify that response HTTP status is Ok (200). This ensures that the request was successfully executed.
>   - andExpect(MockMvcResultMatchers.jsonPath(“$.message”).value(“Hello World!!!”)) will verify that the response content matches with the argument “Hello World!!!” Here, we used jsonPath, which extracts the response content and provides the requested value.
>   - andReturn() will return the MvcResult object, which is used when we have to verify something that isn't directly achievable by the library. In this case, we've added assertEquals to match the content type of the response that is extracted from the MvcResult object.
><!-- Retreived from Baeldung -->
>
>It's limitations are because Spring prepares a fake web application context to mock the HTTP requests and responses, it may not support all the features of a full-blown Spring application.
><!-- Retreived from Baeldung.  -->

>## Things I want to know more about...
>Testing in general.