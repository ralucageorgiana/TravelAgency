# ✈️ Travel Agency

A full-stack Travel Agency application developed as a team project during a Java development course.

The application provides functionality for managing travel-related data and users through a Spring Boot backend and an Angular-based frontend.

The project was developed to practice building a complete web application using Java, Spring Boot, REST APIs, database persistence, authentication and frontend-backend communication.

## 🛠 Technologies

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- REST APIs
- MySQL
- Maven
- Lombok

### Frontend
- Angular
- TypeScript / JavaScript
- HTML
- CSS

## 🚀 Main Features

- User registration and login
- Role-based access control
- User and administrator roles
- Management of travel-related entities
- REST API communication between frontend and backend
- Database persistence using JPA and Hibernate
- Password encryption using BCrypt
- CORS configuration for frontend-backend communication
- Validation and exception handling

## 🧩 Main Entities

The application works with several domain entities, including:

- User
- Role
- SuperAdmin
- Country
- City
- Airport
- Hotel
- Tour
- Review

Relationships between entities are managed using JPA/Hibernate annotations.

## 🏗 Backend Architecture

The backend follows a layered architecture:

- **Controller** – handles HTTP requests and REST endpoints
- **Service** – contains application business logic
- **Repository** – manages database access
- **Entity** – represents database entities
- **DTO** – transfers data between application layers
- **Mapper** – converts between entities and DTOs
- **Configuration** – contains security and application configuration
- **Exception** – handles application-specific exceptions

## 🔐 Security

Spring Security is used to manage authentication and authorization.

The application includes:

- User authentication
- Role-based authorization
- Password encryption with BCrypt
- Security configuration for protected and public endpoints
- Dedicated authentication endpoints

## 🌐 REST API

The backend exposes REST endpoints used by the frontend to interact with the application.

The API supports operations related to authentication, users and travel-related resources such as airports, cities, countries, hotels and tours.

## 🗄 Database

The application uses MySQL as a relational database.

Database persistence and entity relationships are managed using:

- Spring Data JPA
- Hibernate

Database credentials are configured through environment variables and are not stored in the repository.

## 📁 Project Structure

```text
src/main/java/com/travelagency/travelagency
│
├── configuration
├── controller
├── dto
├── entity
├── exception
├── mapper
├── repository
├── service
└── TravelagencyApplication.java
