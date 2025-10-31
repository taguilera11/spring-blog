# Spring Boot Secure Blog API

A backend application for a multi-user blog platform, built with a strong focus on security using Spring Boot. This project implements user registration, password hashing (BCrypt), and JWT-based authentication.

This project serves as a robust template for any Spring Boot application requiring modern, token-based security.

## Features

* **User Registration:** Secure `/api/v1/auth/register` endpoint.
* **Password Encryption:** All user passwords are securely hashed using **BCrypt**.
* **JWT Authentication:** (Coming Soon) Secure `/api/v1/auth/login` endpoint that generates and validates JSON Web Tokens.
* **Role-Based Access Control:** (Coming Soon) Protected endpoints based on user roles (e.g., `ROLE_USER`, `ROLE_ADMIN`).
* **Data Validation:** Input validation using `spring-boot-starter-validation` (`@Valid`).
* **JPA Relational Mapping:** Clean entity mapping between `User` and `Post` tables.

## Tech Stack

* **Core:** Spring Boot 3.x
* **Security:** Spring Security 6.x
* **Authentication:** JSON Web Tokens (JWT)
* **Database:** Spring Data JPA (Hibernate)
* **Database Driver:** MySQL
* **Utilities:** Lombok, Spring Boot Validation
* **Build:** Maven
