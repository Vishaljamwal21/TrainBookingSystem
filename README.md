# TrainBookingSystem

## Introduction

This project is a Train Booking System built using the ASP.NET Core MVC framework. Its aim is to allow users to book and cancel train tickets. The project uses the Code First approach and ASP.NET Core Identity for authentication and authorization.

## Features

- **ASP.NET Core MVC**: Web application framework
- **Entity Framework Core**: Code First approach for database interactions
- **ASP.NET Core Identity**: Authentication and authorization
- **Admin and User roles**: Admin can manage trains, and users can book and manage their tickets

## Setup

### Prerequisites

- Visual Studio 2022
- SQL Server or any preferred database

### Steps

1. **Clone the Repository**:

2. **Open the Solution**:
- Open the solution in Visual Studio 2022.

3. **Run Entity Framework Migrations**:
- Open the Package Manager Console from Tools > NuGet Package Manager > Package Manager Console.
- Select the TrainBookingSystem.Data project in the console.
- Run the following commands to add migrations and update the database:
- Add-Migration InitialMigration
- Update-Database

4. **Build and Run the Application**:
- Set TrainBookingSystem as the startup project.
- Build and run the application using Ctrl + F5.

 ### Usage
**Register as an Admin or User**:
- The first registered user will be assigned the Admin role.
- Subsequent users will be assigned the User role by default.

**Admin Functionality**:
- Admin can add, edit, or delete trains.
- Admin can view and manage all bookings.

**User Functionality**:
- Users can browse available trains.
- Users can book and cancel tickets.
- Users can view their booking history.

### Project Structure
- TrainBookingSystem: Main project with controllers, views, and other frontend components.
- TrainBookingSystem.Data: Contains the Entity Framework Core context, models, and migrations.
- TrainBookingSystem.Models: Contains the domain models.
- TrainBookingSystem.Utility: Contains utility classes and constants.

## Technologies Used
- ASP.NET Core MVC: Web framework
- Entity Framework Core: ORM for database interactions
- ASP.NET Core Identity: Authentication and authorization

## Contact
- For any queries or issues, please contact Vishal Jamwal at vishaljamwal402@gmail.com .