# Microservices JWT Authentication

This repository demonstrates the implementation of **JWT (JSON Web Token) Authentication** in an **ASP.NET Core Web API** using a microservices-based architecture. It includes secure API endpoints, role-based authorization, user authentication, configuration management, and project organization.

## Repository Structure

```text
├── Controllers/
├── Models/
├── Properties/
├── .gitkeep
├── Program.cs
├── WeatherForecast.cs
├── Microservices_JWT.csproj
├── Microservices_JWT.http
├── appsettings.json
├── appsettings.Development.json
└── README.md
```

## Project Components

### Controllers
- **AuthController** – Handles user authentication and JWT token generation.
- **AdminController** – Provides administrator-only endpoints with role-based authorization.
- **SecureController** – Contains protected endpoints that require authenticated access.
- **WeatherForecastController** – Demonstrates sample REST API endpoints.

### Models
- **User** – Represents user information used for authentication and authorization.

### Properties
- **launchSettings.json** – Configures launch profiles and development environment settings.

### Configuration Files
- **appsettings.json** – General application configuration.
- **appsettings.Development.json** – Development-specific settings.
- **Microservices_JWT.http** – HTTP request file for testing API endpoints.
- **.gitkeep** – Preserves empty directories in the Git repository.

## Features

- JWT-based Authentication
- Role-based Authorization
- Secure RESTful API Endpoints
- Admin and User Access Control
- Environment-based Configuration
- HTTP Request Testing Support
- Sample Weather Forecast API

## Technologies Used

- C#
- ASP.NET Core Web API
- .NET
- JWT Authentication
- REST API
- JSON Configuration

## Learning Objectives

- Implement JWT authentication in ASP.NET Core.
- Secure APIs using role-based authorization.
- Configure ASP.NET Core applications with environment-specific settings.
- Test API endpoints using HTTP request files.
- Understand the structure of a microservices-ready Web API project.

## Author

**Yaminisaraswati Muthireddy**

---

*This repository is created for educational and learning purposes.*
