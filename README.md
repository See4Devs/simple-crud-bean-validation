# Spring Boot CRUD application with Bean Validation
In a simple CRUD application with an in-memory database, we use bean validation to ensure that user-provided information meets specific criteria for acceptance. The required user information includes their name, email, and password, and the validation process is crucial to ensure data quality.

Our high-level architecture for this application involves a backend server with RESTful APIs and an in-memory H2 database. This setup provides a flexible and efficient means for processing user data and handling requests.

![Application Sequence Diagram](https://i.imgur.com/ysNttIp.png)

# Run tests
To run the tests, open a terminal, navigate to the root directory of your project, and run the following command:

```
mvn test
```
### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.0-SNAPSHOT/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.0-SNAPSHOT/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.0-SNAPSHOT/reference/htmlsingle/#web)
* [Validation](https://docs.spring.io/spring-boot/docs/3.1.0-SNAPSHOT/reference/htmlsingle/#io.validation)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/3.1.0-SNAPSHOT/reference/htmlsingle/#data.sql.jpa-and-spring-data)


