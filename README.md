Warehouse Management System
A robust backend application designed to streamline inventory tracking and stock management. This system provides a secure, role-based environment for managing warehouse operations via a RESTful architecture.

🚀 Key Features
Inventory & Stock Management: Full CRUD (Create, Read, Update, Delete) functionality for managing warehouse items.

Secure Authentication: Implementation of Spring Security to safeguard endpoints.

Role-Based Access Control (RBAC): Distinct permissions for Admin and User roles to manage sensitive inventory actions.

RESTful API: Clean and documented API endpoints for seamless frontend integration.

🛠️ Tech Stack
Language: Java

Framework: Spring Boot

Database: PostgreSQL (or specify your DB)

Security: Spring Security / JWT

Tools: Maven/Gradle, Postman for API testing

📋 Getting Started
Prerequisites
Java 17 or higher

Maven/Gradle

PostgreSQL installed and running

Installation
Clone the repository:

Bash
git clone https://github.com/AvazbekGaniev/Warehouse-Web-Application.git
Configure Database:
Update src/main/resources/application.properties with your database credentials.

Build the project:

Bash
mvn clean install
Run the application:

Bash
mvn spring-boot:run
🔒 Security & Roles
Admin: Full access to view, add, edit, and delete inventory and users.

User: Restricted access to view inventory and stock levels.
