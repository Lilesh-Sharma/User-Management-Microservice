# User Management Microservice

This microservice handles user-related operations such as registration, login, authentication, and managing user profiles. It utilizes Java Spring Boot for the backend development and exposes REST APIs for interaction.

## Microservice Features

1.  **User Registration:** Create a new user with basic details like name, email, and password.
2.  **User Login:** Authenticate users using JWT (JSON Web Tokens).
3.  **User Profile:** Fetch and update user details.

## Steps to Build the User Management Microservice

1.  **Set up the Spring Boot project:**
    * Create a new Spring Boot application with the following dependencies:
        * `Spring Web`
        * `Spring Data JPA`
        * `Spring Security`
        * `Lombok`
        * `MySQL Driver`

2.  **Design Database Schema:**
    * Create a `user` table with the following fields: `id`, `name`, `email`, and `password`.

3.  **Develop REST APIs:**
    * Expose the following endpoints:
        * `/register` (for user registration)
        * `/login` (for user login)
        * `/profile` (for fetching and updating user profile)

4.  **JWT Authentication:**
    * Implement JWT-based authentication for securing the defined endpoints.

5.  **Test APIs:**
    * Use tools like Postman to validate the functionality of the exposed APIs.
