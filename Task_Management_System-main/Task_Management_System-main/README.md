# Task Management System

## Table of Contents:
1. [Introduction](#introduction)
2. [Features](#features)
3. [Key Functionalities](#key-functionalities)
4. [Requirements](#requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [How to Use](#how-to-use)
8. [Code Structure](#code-structure)
9. [Authors](#authors)
10. [Screenshots](#screenshots)
11. [Commit History](#commit-history)

## Introduction
The Task Management System is a comprehensive web application built with Spring Boot, a relational database, and front-end markup. It provides a platform for efficient task management within an organization, featuring different account types such as worker, manager, and director.

## Features
- User account management (worker, manager, director)
- Task creation, assignment, and tracking
- Role-based access control
- Database integration for persistent data storage
- Responsive front-end design

## Key Functionalities
1. **User Authentication:**
   - Implement a secure authentication system to allow users (workers, managers, and directors) to log in with their credentials.

2. **Task Creation:**
   - Enable users, particularly managers and directors, to create tasks by providing detailed descriptions and specifying relevant details such as due dates.

3. **Task Assignment:**
   - Implement the functionality to assign tasks to specific workers, allowing managers and directors to distribute workload efficiently.

4. **Role-Based Access Control:**
   - Set up role-based access control to ensure that each user has access only to features and data relevant to their role (worker, manager, or director).

5. **Task Tracking:**
   - Provide a mechanism for tracking the status and progress of tasks, allowing workers, managers, and directors to monitor ongoing activities.

6. **Database Integration:**
   - Integrate a relational database (e.g., MySQL, PostgreSQL) to persistently store user account information, task details, and other relevant data.

7. **Responsive Front-End Design:**
   - Implement a responsive and user-friendly front-end design to ensure a seamless user experience across different devices and screen sizes.

8. **Documentation:**
   - Create comprehensive documentation for developers, including setup instructions, API documentation, and any other relevant information needed for future maintenance.

9. **Logging and Auditing:**
   - Implement logging mechanisms to record user actions and changes in the system. This is essential for tracking system behavior and troubleshooting.

10. **Error Handling:**
   - Develop robust error-handling mechanisms to gracefully manage unexpected scenarios, providing meaningful error messages to users and logging errors for system administrators.

## Requirements
- Java Development Kit (JDK) 8 or higher
- Spring Boot framework
- Relational database (e.g., MySQL, PostgreSQL)
- Front-end markup (HTML, CSS, JavaScript)

## Installation
1. Clone the repository: `https://github.com/kimgalina/Task_Management_System.git`
2. Navigate to the project directory: `cd task-management-system`
3. Configure the database settings in `application.properties`.
4. Build and run the application: `./mvnw spring-boot:run`

## Usage
- Access the application through a web browser.
- Log in with your account credentials.
- Explore the dashboard, create tasks, and manage your workload.

## How to Use
1. **Account Types:**
   - Worker: Manages and completes assigned tasks.
   - Manager: Creates tasks, assigns them to workers, and monitors progress.
   - Director: Has access to overall task and account management.

2. **Task Management:**
   - Create tasks with detailed descriptions.
   - Assign tasks to specific workers or leave unassigned for managers to distribute.
   - Track task status and completion.

3. **Role-Based Access:**
   - Workers can view and manage their tasks.
   - Managers can create tasks, assign them, and monitor progress.
   - Directors have access to all aspects of task and account management.

## Code Structure
The project follows a modular structure to enhance maintainability and readability. Key classes include:
- **Application:** Main class for initializing and running the Spring Boot application.
- **Controller:** Manages HTTP requests, handles user input, and interacts with services.
- **Service:** Contains business logic, interacts with the database, and handles task-related operations.
- **Repository:** Manages data access and database interactions.

