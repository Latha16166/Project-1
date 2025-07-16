This is a simple Spring Boot project that exposes RESTful endpoints to manage student data.

## 📚 Features

- Create a new student
- Get all students
- Get student by ID
- Update student details
- Delete a student

## 🚀 Technologies Used

- Java 17 (or 11+)
- Spring Boot
- Spring Web
- Spring Data JPA (optional if database is used)
- H2 / MySQL (optional for persistence)
- Maven / Gradle

## 📁 Project Structure

Project-1/ ├── src/ │   ├── main/ │   │   ├── java/ │   │   │   └── com/example/student/ │   │   │       ├── controller/ │   │   │       ├── model/ │   │   │       ├── repository/ │   │   │       └── StudentApplication.java │   │   └── resources/ │   │       ├── application.properties ├── pom.xml └── README.md

## 📬 API Endpoints

| Method | Endpoint         | Description             |
|--------|------------------|-------------------------|
| GET    | /students      | Get all students        |
| GET    | /students/{id} | Get student by ID       |
| POST   | /students      | Create a new student    |
| PUT    | /students/{id} | Update student          |
| DELETE | /students/{id} | Delete student          |

## ⚙ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Latha16166/Project-1.git

2. Import into VS Code or IntelliJ


3. Run the main class:

StudentApplication.java


4. Test APIs using Postman or browser (for GET requests)
5.# Project-1
spring boot demo - student Endpoint
