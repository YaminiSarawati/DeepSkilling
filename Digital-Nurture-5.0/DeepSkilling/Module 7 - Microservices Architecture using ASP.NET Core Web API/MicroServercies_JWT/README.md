# Microservices JWT Authentication

This repository contains a hands-on **ASP.NET Core Web API** project demonstrating **JWT (JSON Web Token) Authentication** in a microservices environment. The project includes secure API endpoints, role-based authorization, controllers, models, configuration files, and application startup settings.

## Repository Structure

```text
├── Controllers/
├── Models/
├── Properties/
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
- **SecureController** – Contains protected endpoints accessible only to authenticated users.
- **WeatherForecastController** – Demonstrates sample API endpoints.

### Models
- **User** – Represents user information for authentication and authorization.

### Properties
- **launchSettings.json** – Configures launch profiles and development environment settings.

### Configuration
- **appsettings.json** – General application configuration.
- **appsettings.Development.json** – Development-specific configuration.
- **Microservices_JWT.http** – HTTP request file for testing API endpoints.

## Features

- JWT Authentication
- Role-based Authorization
- Secure API Endpoints
- RESTful Web API Architecture
- Environment-based Configuration
- HTTP Request Testing Support
- Weather Forecast Sample API

## Technologies Used

- C#
- ASP.NET Core Web API
- .NET
- JWT Authentication
- REST API
- JSON Configuration

## Learning Objectives

- Understand JWT-based authentication in ASP.NET Core.
- Implement secure RESTful APIs.
- Apply role-based authorization.
- Configure applications using `appsettings.json`.
- Test secured API endpoints using HTTP request files.

## Author

**Yaminisaraswati Muthireddy**

---

*This repository is created for educational and learning purposes.*
