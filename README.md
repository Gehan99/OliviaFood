# Food Ordering Web Application

This is a Java Spring Boot project for a Food Ordering Web Application. It provides functionalities for users to view menus, add items to cart, delete items from cart, and place orders. The project follows the MVC (Model-View-Controller) architecture.

## Features

- **User Management**: Allows CRUD (Create, Read, Update, Delete) operations on user accounts.
- **Order Management**: Handles the process of placing and managing orders.
- **Admin Dashboard**: Provides administrative functionalities.

## Technologies Used

- Java
- Spring Boot
- Hibernate 
- MySQL 

## Installation

1. Clone the repository to your local machine.
2. Import the project into your preferred Java IDE.
3. Configure your database settings in `application.properties`.
4. Run the application.

## Usage

- **User Management**: 
  - Access user-related endpoints through `/users`.
  - Endpoints include:
    - GET `/users`: Retrieve all users.
    - POST `/users`: Create a new user.
    - PUT `/users`: Update an existing user.
    - DELETE `/users/{id}`: Delete a user by ID.
    - DELETE `/users?name={name}`: Delete a user by name.
    - GET `/users?name={name}`: Retrieve user(s) by name.


