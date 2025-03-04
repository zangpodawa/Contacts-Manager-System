# Contacts-Manager-System

This project is a Contacts Manager System built using C#.NET and ASP.NET Core. The system allows users to manage contacts with advanced features like authentication, authorization, logging, advanced unit testing, and CRUD operations.

**Features**
1. CRUD Operations: Create, Read, Update, and Delete contacts.
2. User Authentication & Authorization: Secure user sign-in and role-based authorization using Identity.
3. Web API: Exposes API endpoints to manage contacts using Entity Framework Core and MVC architecture.
4. Unit Testing: Advanced unit testing using xUnit, Moq, and Repository Pattern.
5. Logging & Error Handling: Integration of Serilog for centralized logging and advanced error handling.
6. Filters: Custom filters for handling requests and errors efficiently.
7. SOLID Principles: Followed SOLID principles to ensure clean, maintainable, and scalable code.
8. CLEAN Architecture: Separation of concerns through a layered architecture to enhance the maintainability and scalability of the system.
   
**Technologies Used**
1. ASP.NET Core (for backend API and MVC)
2. C# (Primary programming language)
3. Entity Framework Core (ORM for database interactions)
4. xUnit (for unit testing)
5. Moq (for mocking dependencies in tests)
6. Serilog (for logging)
7. Identity (for user authentication and authorization)
8. JWT Authentication (for securing Web API endpoints)
9. SOLID Principles (for software design)
10. CLEAN Architecture (for project structure)

Prerequisites
Before running this application, make sure you have the following installed:

.NET 6.0 or higher
Visual Studio or Visual Studio Code
SQL Server (or any other relational database for Entity Framework Core)

Usage
Sign In: Users can register and log in using JWT-based authentication. Use Postman or any HTTP client to interact with the Web API.
Contact Management: The application allows CRUD operations to manage contacts:
Create: Add new contacts.
Read: View existing contacts.
Update: Modify contact information.
Delete: Remove a contact.

Architecture
This project follows the CLEAN Architecture pattern:

Core: Contains the business logic, models, and interfaces.
Application: Implements business logic, including services and use cases.
Infrastructure: Handles data access, third-party services (e.g., logging), and external API calls.
Web API: Contains the web layer (controllers, API routes).
Security
The system utilizes JWT (JSON Web Tokens) for user authentication and authorization. Users must authenticate before performing CRUD operations.

Identity is used for managing users, passwords, roles, and permissions.
Authorization: Only authenticated users can access protected resources.
Roles: Admin users can perform all actions, while regular users can only manage their own contacts.
Logging & Error Handling
Serilog is used for structured logging, making it easier to monitor the system.
The system includes comprehensive error handling using filters and custom exception handling middleware.

Thanks
A special thanks to **Harsha Vardhan** for the amazing teaching on Udemy. His lessons were instrumental in the development of this system.
<img width="848" alt="CM1" src="https://github.com/user-attachments/assets/2e6768bd-1597-4841-93a7-f6174d700aa5" />
<img width="850" alt="CM2" src="https://github.com/user-attachments/assets/b6a968f5-33e4-4803-9528-2c09bcfabd8c" />
<img width="848" alt="CM3" src="https://github.com/user-attachments/assets/b17d4a98-f0ed-43bb-bcf0-1dc9035221e9" />
<img width="851" alt="CM4" src="https://github.com/user-attachments/assets/c8d362c9-9796-4f48-ab22-881532919ff8" />
<img width="847" alt="CM5" src="https://github.com/user-attachments/assets/72686cf2-6917-4d63-b102-b93e55da0676" />
<img width="852" alt="CM6" src="https://github.com/user-attachments/assets/a0407559-3829-4946-a723-42c0582c0a4c" />
<img width="850" alt="CM2" src="https://github.com/user-attachments/assets/669a9115-8d36-4655-be22-33e11d334af7" />



