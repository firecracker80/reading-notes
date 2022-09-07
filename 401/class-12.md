# Reading Assignment 12

>## Spring guide: Accessing Data with JPA
>
>Start by creating a Spring app in the Spring Initalizer and ensuring to install JPA as a dependency. You can gain access by using the @Entity annotation. Ensure to create a protected default constructor for the JPA. You will need @Id so that the JPA can recognize the object's id.
>
>The JPA stores,relational data in a database, Postgres. It automatically creates repo implementations from the repo interface at runtime.
>
>## Baeldung: Comparing repositories
>
>NOTES:
>
>Each of these defines its own functionality:
>
> - CrudRepository provides CRUD functions
> - PagingAndSortingRepository provides methods to do pagination and sort records
> - JpaRepository provides JPA related methods such as flushing the persistence context and delete records in a batch.
>
>CRUD functionality:
>
> - save(…) – save an Iterable of entities. Here, we can pass multiple objects to save them in a batch
> - findOne(…) – get a single entity based on passed primary key value
> - findAll() – get an Iterable of all available entities in database
> - count() – return the count of total entities in a table
> - delete(…) – delete an entity based on the passed object
> - exists(…) – verify if an entity exists based on the passed primary key value
>
>JPA Repo Interface methods:
>
> - findAll() – get a List of all available entities in database
> - findAll(…) – get a List of all available entities and sort them using the provided condition
> - save(…) – save an Iterable of entities. Here, we can pass multiple objects to save them in a batch
> - flush() – flush all pending task to the database
> - saveAndFlush(…) – save the entity and flush changes immediately
> - deleteInBatch(…) – delete an Iterable of entities. Here, we can pass multiple objects to delete them in a batch
><!-- Retreived from Baeldung. -->

>## Things I want to know more about...
>What happens if the internal implementations are exposed?