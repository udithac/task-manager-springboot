# Task Manager Application - Backend

## Overview

This is the backend for the Task Manager web application, built using Spring Boot Webflux.

## How to Run the Application

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/udithac/task-manager-backend.git
   cd task-manager-backend


2. **Build and Run:**

   - Make sure that you have Java 11 and Maven Installed.
   - Build the application and run.
   ```bash
      mvn spring-boot:run
   
   - Verify the application running status at  <http://localhost:8080>

3. **API Endpoints**

- To get all tasks
   ```bash
  GET http://localhost:8080/api/tasks

  ```bash
   GET <http://localhost:8080/api/tasks>

- Create a new task
  ```bash
    POST <http://localhost:8080/api/tasks>

- Request Body:
  ```bash
    {
    "name": "Task Name",
    "dueDate": "2023-12-31",
    "completed": false
    }

- Response:
    ```bash
    {
    "id": 1,
    "name": "Task Name",
    "dueDate": "2023-12-31",
    "completed": false
    }

- Mark Task as completed
  ```bash
    PUT <http://localhost:8080/api/tasks/{taskId}/complete>

- Delete task:
  ```bash
  DELETE <http://localhost:8080/api/tasks/{taskId}>

4. **Dependencies**
    - Spring Boot 2.5.x
    - Java 11
    - Maven

5. **Contributing**
    - Feel free to share your comments and report any issues or send us new requirements.
    - Your voice is very important to us.

6. **License:**

- the Task Manager project is licensed under the MIT License.


Thank you very much for your support!, Uditha C. WICK, 23/11/2023, Berlin, GE.
