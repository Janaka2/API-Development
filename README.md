# API-Development
# API Development with Java and Spring Boot

## Overview
This repository contains a highly-scalable, industry-standard RESTful API designed using Java 11 and Spring Boot. The API demonstrates proficiency in the latest Spring technologies and best practices, focusing on providing an efficient and secure way to access and manage data for modern web applications.

## Features
- **Modern, modular architecture** using Java 11 and Spring Boot for easy maintenance and scalability
- **Secure authentication and authorization** using OAuth2 and JWT
- **Input validation and error handling** with Spring's validation features
- **Comprehensive documentation** using OpenAPI Specification (formerly Swagger) and Springdoc
- **API versioning** to ensure backward compatibility
- **Pagination and filtering** using Spring Data JPA
- **Comprehensive testing suite** with JUnit and Mockito

## Technologies
- Java 11
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- PostgreSQL
- Redis (for caching)
- Docker (for containerization)

## Setup and Run
1. Clone this repository
2. Install dependencies: `mvn clean install`
3. Set up environment variables or update the `application.properties` file with the following configurations:
   - `spring.datasource.url`: Your PostgreSQL connection string
   - `spring.datasource.username`: Your PostgreSQL username
   - `spring.datasource.password`: Your PostgreSQL password
   - `spring.security.oauth2.jwt.secret`: A secret key for signing JWT tokens
   - `spring.redis.host`: Your Redis hostname (optional)
   - `spring.redis.port`: Your Redis port (optional)
4. Run the server: `mvn spring-boot:run`
5. The API will be accessible at `http://localhost:8080`

## Documentation
API documentation is available at `/swagger-ui.html` using Springdoc and OpenAPI Specification. The API documentation is interactive, allowing you to send requests and view responses directly from the documentation.

## Testing
1. Ensure the required configurations are set for testing (refer to the setup section)
2. Run the test suite: `mvn test`

## Fun Fact
While developing this API, I learned about the versatility of the Spring Boot framework. The wide range of Spring projects, like Spring Security and Spring Data JPA, allowed me to create a robust and feature-rich API with minimal boilerplate code. The Spring ecosystem has made it easier than ever to build enterprise-grade applications while focusing on writing clean and maintainable code.

# I'm Janaka Premathilaka,
📫 Feel free to reach out to me at janaka2@gmail.com , on [LinkedIn](https://www.linkedin.com/in/janakap/) or give me a call at +41 76 224 84 45. 💌 🚀
