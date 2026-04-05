# Student Management REST API

A RESTful backend application built using Java and Spring Boot to manage student records.

## Features

- CRUD operations (Create, Read, Update, Delete)
- Layered architecture (Controller, Service, Repository)
- Input validation with error handling
- Swagger/OpenAPI documentation
- In-memory H2 database (to be upgraded to PostgreSQL)

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- Maven
- H2 Database
- Swagger (OpenAPI)

## How to Run

1. Clone the repository
2. Navigate to project folder
3. Run: ./mvnw spring-boot:run
4. Open browser: http://localhost:8080/swagger-ui/index.html

## API Endpoints

- GET /students
- GET /students/{id}
- POST /students
- PUT /students/{id}
- DELETE /students/{id}

## Example Request

POST /students
{
"name": "John",
"email": "john@example.com
"
}


## Future Improvements

- PostgreSQL integration
- Authentication (JWT)
- Deployment
