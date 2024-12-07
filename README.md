Spring Boot Application for Order Management
Description
This project is a Spring Boot application that manages orders using REST APIs. It includes functionalities to insert new orders into a MySQL database using a POST request. The Order entity contains details like Order ID, Product Name, Quantity, Order Date, and Customer Name.

Features
Add New Order: Insert new order data using a REST API endpoint.
Validation:
Order ID must be provided manually, must not be null, and must be unique.
Database operations are powered by Spring Data JPA.
Easy testing using Postman or similar API tools.
Technologies Used
Spring Boot: Framework for building Java-based REST APIs.
Spring Data JPA: Simplifies database interactions.
MySQL: Database used for storing order details.
Maven: Dependency management.
Postman: For testing API endpoints.
