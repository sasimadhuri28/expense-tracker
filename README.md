# Expense Tracker REST API

A RESTful backend API to track personal expenses built with Java and Spring Boot.

## Tech Stack
- Java 17
- Spring Boot 4.0.6
- Spring Data JPA + Hibernate
- MySQL 8
- Lombok
- Tested with Postman

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/expenses | Add a new expense |
| GET | /api/expenses | Get all expenses |
| GET | /api/expenses/{id} | Get expense by ID |
| GET | /api/expenses/category/{name} | Filter by category |
| GET | /api/expenses/summary | Total grouped by category |
| GET | /api/expenses/filter?start=&end= | Filter by date range |
| PUT | /api/expenses/{id} | Update an expense |
| DELETE | /api/expenses/{id} | Delete an expense |

## Sample Request
POST /api/expenses
```json
