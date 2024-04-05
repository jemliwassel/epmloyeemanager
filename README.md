# Employee Manager App

Employee Manager App is a simple Spring Boot application for managing employee data. It provides CRUD (Create, Read, Update, Delete) operations for employee entities.

## Features

- Add a new employee
- Retrieve all employees
- Retrieve an employee by ID
- Update an existing employee
- Delete an employee by ID

## Technologies Used

- Spring Boot
- Spring Data JPA
- MySQL Database
- Maven

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository to your local machine.
2. Make sure you have Java and Maven installed.
3. Navigate to the project directory in your terminal.
4. Run the command `mvn spring-boot:run`.
5. Once the application is running, you can access it at `http://localhost:8080`.

## Usage

- To add a new employee, send a POST request to `/employee/add` with the employee data in the request body.
- To retrieve all employees, send a GET request to `/employee/all`.
- To retrieve a specific employee by ID, send a GET request to `/employee/find/{id}`.
-
