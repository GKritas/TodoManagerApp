# Todo Manager App

The Todo Manager is a web application built using Java, Spring Boot, and MySQL. It allows users to create, read, update, and delete their tasks or to-dos. The application has a login system that ensures only authenticated users can access their to-dos.

This project is part of the "Master Spring Boot 3 & Spring Framework 6 with Java" course by in28minutes on Udemy.

## Features

- User login and authentication system
- Create new tasks
- View existing tasks
- Edit task details
- Delete tasks

## Technologies used

- Java
- Spring Boot
- MySQL
- Spring Data JPA

## Getting started

1. Clone the repository `git clone https://github.com/GKritas/TodoManagerApp.git`

2. Create a MySQL database named `todos`

  `mysql -u <username> -p`
  
  `create database todos;`
  
3. Open the project in your IDE and update the `application.properties` file with your MySQL username and password.

4. Build and run the project

  `./mvnw spring-boot:run`

5. Open your web browser and go to http://localhost:8080

## How to use

1. Register or login to your account
2. Create new tasks by clicking on "Add Task" button
3. Edit or delete tasks using the "Edit" and "Delete" buttons respectively
4. Logout from your account once done
