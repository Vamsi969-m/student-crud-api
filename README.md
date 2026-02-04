# student-crud-api
This project focuses on learning REST API fundamentals, CRUD operations, and basic backend architecture. APIs tested using Postman.

# Student Management REST API (Beginner Project)

This is a basic REST API project built using Node.js, Express.js, and MongoDB.
The main goal of this project is to understand REST API concepts, CRUD operations,
and basic backend development workflow.

---

## Features
- Create, Read, Update, and Delete (CRUD) student records
- Prevent duplicate entries using unique roll numbers
- Search students using query parameters
- Pagination support for listing students
- Proper HTTP status codes and error handling
- Tested using Postman
- Follows MVC architecture (beginner level)

---

##  Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose
- Postman

---

##  API Endpoints

| Method | Endpoint | Description |
|------|---------|-------------|
| POST | /api/students | Create a new student |
| GET | /api/students | Get all students (with filters & pagination) |
| PUT | /api/students/:rollno | Update student by roll number |
| DELETE | /api/students/:rollno | Delete student by roll number |

---

## Example Request (POST)

```json
{
  "name": "Vamsi",
  "age": 22,
  "email": "vamsi@gmail.com",
  "rollno": 101
}
