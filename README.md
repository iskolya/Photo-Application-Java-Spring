
# Photo Application

The Photo App Project is a stellar example of a Java Spring-based web application, meticulously crafted to serve as a versatile foundation for the development of secure and scalable photo-centric applications. Tailored for developers seeking a streamlined starting point, the project incorporates essential features such as User Address Entity, User Entity, Security, and Email Verification. By leveraging the power of Java Spring, the Photo App Project not only provides a robust framework but also exemplifies best practices in Java Spring development. Developers, whether working individually or as part of a larger team, will find this project to be an excellent showcase and a reliable foundation for creating innovative and feature-rich photo-centric web applications effortlessly.


## Documentation



Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.3/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.3/gradle-plugin/reference/html/#build-image)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/3.1.3/reference/htmlsingle/index.html#data.sql.jpa-and-spring-data)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.3/reference/htmlsingle/index.html#web)

## Guides
The following guides illustrate how to use some features concretely:

* [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)

* 
## End-Points
The UserController exposes a set of RESTful end-points to manage user-related operations in the Photo App Project. These end-points enable seamless interaction with user data, including retrieval, creation, updating, and deletion of user profiles. The primary end-points include:

GET /users/{id}: Retrieve details of a specific user by providing the user ID.

POST /users: Create a new user by submitting the necessary user details in the request payload.

PUT /users/{id}: Update an existing user's information by specifying the user ID and providing updated details in the request payload.

DELETE /users/{id}: Delete a user profile based on the provided user ID.

GET /users: Retrieve a list of users with optional pagination parameters for enhanced control over result sets.

GET /users/{userId}/addresses: Retrieve a collection of addresses associated with a specific user.

GET /users/{userId}/addresses/{addressId}: Retrieve details of a specific address associated with a user.

GET /users/email-verification: Verify an email token for email verification.

Each end-point is designed to facilitate seamless integration and interaction with the user management functionalities of the Photo App, catering to diverse use cases within your application. For further details on request and response structures, please refer to the respective methods in the UserController class.





