# E-Commerce and Employee Management System

## Overview
This is a combined E-Commerce and Employee Management System application built using Java and Spring Boot. The e-commerce module allows users to view products and provides admin functionalities like adding, editing, and deleting products. The employee management module allows users to manage employee records with features like adding and viewing employees.

## Technologies Used:
- **Java**: Core backend programming language.
- **Spring Boot**: Simplifies the setup and development of the application.
- **Spring MVC**: For handling HTTP requests and rendering views using Thymeleaf.
- **Thymeleaf**: Templating engine for dynamic HTML generation.
- **Spring Data JPA**: Simplifies data access with automatic CRUD operations.
- **Hibernate**: ORM for mapping Java objects to relational database tables.
- **MySQL**: Relational database for storing product and employee data.
- **Lombok**: Reduces boilerplate code in Java entities.

## Features
### E-Commerce Module:
- View products on the home page.
- View detailed information for individual products.
- Admin functionalities to add, edit, and delete products.

### Employee Management Module:
- Add new employees.
- View a list of all employees.

## Setup Instructions

### Prerequisites
- Java 8 or higher
- MySQL installed
- Maven installed

### Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone <repository_url>

src/main/java/com/wipro/
    ├── ecommerce/
    │   ├── EcommerceApplication.java          # Main entry point for e-commerce module
    │   ├── Product.java                       # Product entity class
    │   ├── ProductController.java             # Controller for product-related requests
    │   ├── ProductService.java                # Service layer for product operations
    └── employee_management/
        ├── EmployeeManagementApplication.java # Main entry point for employee management module
        ├── Employee.java                      # Employee entity class
        ├── EmployeeController.java            # Controller for employee-related requests
        ├── EmployeeService.java               # Service layer for employee operations
        ├── EmployeeRepository.java            # Repository interface for employee operations
