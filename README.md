# Student Records API

This is a simple sample project for documenting a REST API that manages student records in a university.  
The project demonstrates how to create, retrieve, and view student details using a minimal API design.

## Features
- Add a new student record
- Get a list of all students
- Get details of a specific student by ID
- API documentation provided in `openapi.yaml` (OpenAPI 3.0 standard)

## Installation
1. Clone the repository:
   git clone https://github.com/yourusername/student-records-api.git
   cd student-records-api

2. (Optional) If you want to run it locally with Node.js:
   npm install
   npm start

## Usage
### Get all students
Request:
```bash
curl -X POST http://localhost:3000/students \
-H "Content-Type: application/json" \
-d '{"name":"John Doe","age":21,"course":"Software Engineering"}'

{
  "id": 3,
  "name": "Ignatious.T",
  "age": 21,
  "course": "Software Engineering"
}


  "error": "Student not found"
}
