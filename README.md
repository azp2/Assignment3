# Device Management System

## Overview
A Spring Boot-based Device Management System developed as part of the COOP Training assignment3. This application provides a comprehensive REST API and an MVC web interface (Thymeleaf) for managing devices, secured with Spring Security (Role-Based Access Control) and documented using Swagger/OpenAPI.

**Author:** Abdulaziz Alamri

## Technologies Used
- **Java 26**
- **Spring Boot 3.0.2**
- **Spring Web** (REST APIs & MVC Controller)
- **Spring Data JPA & Hibernate**
- **MySQL** (Database)
- **Spring Security** (JDBC Authentication, BCrypt Password Encoder)
- **Thymeleaf** (UI Templates)
- **Spring Boot Actuator** (Health & Info Endpoints)
- **SpringDoc OpenAPI** (Swagger UI)
- **Validation** (Hibernate Validator)

## Setup & Installation

### 1. Database Configuration
1. Open MySQL and create a database named `devicedb`.
2. The application is configured to connect using the following credentials (configured in `application.properties`):
   - **Username:** `springstudent`
   - **Password:** `springstudent`
   - **Port:** `3306`

### 2. Run the Application
The application runs on port `8081`. You can run it via your IDE (Eclipse/IntelliJ) or using Maven:
```bash
mvn spring-boot:run
