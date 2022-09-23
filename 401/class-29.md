# Reading Assignment 29

> 1. What database engine is Room wrapped around? Do you think this is a good choice? Why or why not?
> - Room is wrapped around SQLite. Is it a good choice? Not sure. I do, however, think it is covenient to have compiled time verifications, minimized repetition, and streamlined migration paths. All things that speak to speed and accuracy. Concepts that are important to today's generation and those of us in tech.
> 2. Do Rooms have any similarities to JPA?
> - Both are initiated with @Entity annotation, both use interfaces that have there own methods, to query you must use @Query annotation, which allows SQL statements to be exposed as a DAO method, SQLite and JPA are relational databases, this allows the definition of relationships between objects.
> 3. Describe a DAO in your own words.
> - It is a object that contains data access activities. The data access element from and to an external data system is enabled, or abstracted away, by an object in object-oriented programming. It's a very particular type of database, or any generic data source that could be this data system.

## Things I want to know more about...
>Are DAOs only used in mobile development, or can it be implemented in overall web applications?