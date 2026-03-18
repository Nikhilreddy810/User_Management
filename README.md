# User Management System

A RESTful backend API for managing users built with Java and Spring Boot.

## Tech Stack
- Java 17, Spring Boot 3.5
- MySQL, Spring Data JPA / Hibernate
- Maven, Postman

## Features
- Full CRUD operations
- Search users by name
- Filter users by role
- Input validation

## Getting Started
1. Clone the repository
2. Create MySQL database: `CREATE DATABASE user_management;`
3. Set DB password: `DB_PASSWORD=your_password`
4. Run: `mvn spring-boot:run`

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/users | Create user |
| GET | /api/users | Get all users |
| GET | /api/users/{id} | Get user by ID |
| PUT | /api/users/{id} | Update user |
| DELETE | /api/users/{id} | Delete user |
| GET | /api/users/search?name= | Search by name |
| GET | /api/users/role?role= | Filter by role |
