
Spring Boot Security Project
Overview
This project demonstrates a comprehensive implementation of security features using Spring Boot.
The application covers various aspects of security, 
including authentication, authorization, and role-based access control.
It serves as a robust starting point for developers looking to integrate security into their Spring Boot applications.

Features:
User Authentication: Secure login and registration using JWT (JSON Web Tokens).
Role-Based Authorization: Access control based on user roles and permissions.
Secure Endpoints: Protect REST API endpoints with role-based access restrictions.
CORS Configuration: Custom CORS settings for secure cross-origin requests.
Service Layer Security: Secure business logic in the service layer.
Exception Handling: Global exception handling for security-related issues.
Technologies Used:
Spring Boot: The primary framework for building the application.
Spring Security: For implementing security features.
JWT: For stateless authentication.
Hibernate: ORM for database interactions.
Postgres Database: In-memory database for testing and development.
Maven: For project management and dependency management.
Project Structure:
/src/main/java: Contains the main application code.

Configuration: Security and CORS configuration classes.
Controllers: REST API controllers.
Services: Business logic and service implementations.
Repositories: Data access layer using Spring Data JPA.
Entities: JPA entities representing database tables.
DTOs: Data Transfer Objects for API requests and responses.
Utils: Utility classes for various helper functions.
/src/main/resources: Configuration files and static resources.

application.properties: Main configuration file for the application.
Setup and Running the Project


1 Clone the repository:
git clone https://github.com/Dahmoudjerrah/springboot_security.git
cd springboot_security

2 Build the project:
mvn clean install

3Run the application:
mvn spring-boot:run

Access the application:

The application will be accessible at http://localhost:8080.
