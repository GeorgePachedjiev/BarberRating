# 💈 BarberRating

**BarberRating** is an ASP.NET Core MVC web application that allows users to discover barbers, explore their profiles, and share their experiences through ratings and reviews.

This project was developed independently as a final project for the IT Career program.

## 🚀 Features

- **User Authentication** – Registration and login using ASP.NET Core Identity.
- **Role-Based Authorization** – Separate permissions for Admin and User roles.
- **Barber Management** – Create, view, edit, and delete barber profiles.
- **Reviews & Ratings** – Users can share feedback and rate barbers.
- **User Management** – Administrative functionality for managing users.
- **Filtering & Sorting** – Easily find and organize barber profiles.
- **Pagination** – Organized navigation through available content.
- **Image Upload** – Upload and manage barber profile images.

## 🛠️ Technologies Used

- C#
- ASP.NET Core MVC (.NET 8)
- Entity Framework Core
- ASP.NET Core Identity
- Microsoft SQL Server
- Razor Views
- HTML5 & CSS3
- Dependency Injection
- Service Layer Architecture

## 🏗️ Architecture

The application follows a structured architecture with separation of responsibilities through:
- Controllers
- Services and Interfaces
- ViewModels
- Data Models
- Entity Framework Core

## 👤 User Roles

**Admin**
- Manage users.
- Manage barber profiles.
- Manage application content.

**User**
- Browse barber profiles.
- Submit ratings and reviews.
- Manage permitted user interactions.

## 🎓 Project Information

- **Project Type:** Individual Project
- **Program:** IT Career
- **Framework:** ASP.NET Core MVC
- **.NET Version:** 8.0

## ⚙️ Getting Started

1. Clone the repository:
   ```bash
   git clone YOUR_REPOSITORY_URL
   ```
2. Open the solution in Visual Studio.
3. Configure your database connection in `appsettings.json`.
4. Apply Entity Framework Core migrations:
   ```bash
   dotnet ef database update
   ```
5. Run the application:
   ```bash
   dotnet run
   ```

## 📌 Purpose

The project demonstrates practical skills in ASP.NET Core development, database management, authentication, authorization, and building full-stack web applications.
