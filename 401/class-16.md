# Reading Assignment 16

>## Spring Security overview
>
>### **Authentication and Access Control**
>
>#### **Authentication**
>
>Spring has an interface for authentication called, AuthenticationManager, which only has one method, authenticate. This method will return either a boolean, stating that you have neem authenticated, throw an exception if the nput is invalid, or return null. 
>
>This manager is most commonly used to implement the ProviderManager. This manager allows instances of the AuthenticationProvider to allow a query of which authentication types it supports. If it doesn't recognize the authentication type it will skip it.
>
>#### **Customizing Authentication Managers**
>
>The authenitcation manager has a configuration helper(use @Confifuration) called, AuthenticationManagerBuilder, to help customize user details, using the UserDetailsService. @Autowiring the manager into @Bean makes it a global parent. (I wonder if by doing this, is why it makes it more applicable?)
>
>#### **Authorization or Access Control**
>
>At this point, for authorization, we have to use the AccessDecisionManager, which has three implementations to delegate to the AccessDeviceVoter instances. This voter takes in the authentication and secure object. This object represents any info the user is requesting access to. It is wrapped in ConfigAtrributes, which determines the level of permissions to access the reuqested info. It's an interface that also only has one method.
>
>### **Web Security**
>
>Based on a servlet Filters, meaning it is important to look at the role it holds first. The container the request is sent in, decides which filter and servlet it will use. The servlet can only  hanlde one request at a time, but filters can be chained together in an order. This is important and is managed through @Beans and @Order to implement Ordered. The Filter also has veto power if it decides it wants to handle the request. It can also modify the request and the response.
>
>Spring Security is installed on a single Filter in the chain, but the reasons behind it still escape me.