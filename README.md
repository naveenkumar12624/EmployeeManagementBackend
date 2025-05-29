# Employee Management System (Spring Boot + Gradle)

This is a simple **Employee Management System** built with **Spring Boot**, **Spring Data JPA**, and **Gradle**. It provides RESTful APIs to perform **CRUD operations** (Create, Read, Update, Delete) on employee records.



## Features

- Add new employee
- View all employees
- Get employee details by ID
- Update employee information
- Delete an employee

## Tech Stack (with MySQL)

| Technology     | Purpose                                 |
|----------------|-----------------------------------------|
| Java 17+       | Programming Language                    |
| Spring Boot    | Backend Framework                       |
| Spring Web     | To build REST APIs                      |
| Spring Data JPA| ORM for database operations             |
| MySQL          | Relational Database                     |
| Gradle         | Build and Dependency Management         |

## Project Structure
```plaintext
src/
└── main/
    ├── java/
    │   └── com/
    │       └── example/
    │           └── employeemanagement/
    │               ├── EmployeeManagementApplication.java
    │               ├── model/
    │               │   └── Employee.java
    │               ├── repository/
    │               │   └── EmployeeRepository.java
    │               ├── service/
    │               │   └── EmployeeService.java
    │               └── controller/
    │                   └── EmployeeController.java
    └── resources/
        ├── application.properties
        └── static/ (optional)
