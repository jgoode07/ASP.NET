# ASP.NET Web API Projects  
**Author: Joe Goode**

This repository contains multiple ASP.NET Core Web API projects developed throughout the course. Each project demonstrates progressively more advanced backend concepts including REST APIs, Entity Framework Core, authentication, and API documentation.

---

## Projects Included

### A1 – Minimal API Products
A basic ASP.NET Core **Minimal API** project demonstrating:

- Simple REST endpoints
- In-memory or lightweight data handling
- Basic HTTP verbs (GET, POST)

This project focuses on understanding how APIs work without controllers.

---

### A2 – Account Management API
A full **MVC-style Web API** using controllers and Entity Framework Core.

**Features:**
- Create, read, update accounts
- SQL Server database integration
- Code-First migrations
- Structured MVC architecture

**Key Concepts Practiced:**
- Controllers
- Dependency Injection
- Entity Framework Core
- Database persistence

---

### A3 – Products API (JWT Authentication)
A secure **ASP.NET Core Web API** that demonstrates authentication and protected endpoints.

**Features:**
- Product CRUD operations
- SQL Server LocalDB
- Entity Framework Core (Code-First)
- JWT Bearer Authentication
- Swagger (OpenAPI) documentation with authorization support

---

## Database

All database-driven projects use:

- **Entity Framework Core**
- **SQL Server LocalDB**
- **Code-First Migrations**

Migrations are used to automatically generate database schemas based on models.

Data persists between application restarts.

---

## Authentication (A3 Project)

The Products API uses **JWT Bearer Authentication** to protect endpoints.


Without a token → **401 Unauthorized**  
With a valid token → **Authorized access**

---

## API Documentation

Swagger (OpenAPI) is enabled for all Web API projects.

Swagger provides:
- Interactive endpoint testing
- Request/response schema visualization
- JWT authentication support for protected APIs

When running in Development mode, open Swagger in your browser to test endpoints.

---

## Technologies Used

- ASP.NET Core
- C#
- Entity Framework Core
- SQL Server LocalDB
- Swagger / OpenAPI
- JWT Bearer Authentication

---

## Testing

Projects were tested using:
- Swagger UI
- Browser requests
- Database inspection via SSMS

Testing verified:
- Correct request handling
- Proper status codes
- Data persistence
- Authentication enforcement (A3)