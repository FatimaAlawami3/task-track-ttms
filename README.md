# Task Track — Task Tracker Management System (Java & MySQL)

## Overview

Task Track is a **Task Tracker Management System (TTMS)** developed as a university course project. The system helps users manage daily tasks in a simple and organized way by allowing them to create, view, sort, complete, and delete tasks.

The application is implemented as a **Java desktop application** and uses a **MySQL database** for persistent storage of user accounts and tasks. It supports both **registered users** and **guest users**, offering flexibility in how the system is used.

---

## Problem Statement

Managing tasks manually or across multiple tools can reduce productivity and lead to missed deadlines. Users need a simple system that allows them to track tasks efficiently while keeping data organized and secure.

This project addresses this problem by providing a centralized task management system with user authentication, database-backed persistence, and a clear workflow for handling tasks.

---

## System Features

### Registered User Features

* User registration with username and password
* Secure login functionality
* Create new tasks with associated dates
* View a list of existing tasks
* Mark tasks as completed
* Sort tasks by date
* Delete tasks
* Persistent storage of tasks using a database

### Guest User Features

* Access the system without creating an account
* Create and manage tasks during the session
* Tasks are not saved after the application is closed

---

## Database Design

The system uses a relational database to store user and task information.

### Main Tables

* **Users**: stores registered user credentials
* **Tasks**: stores task details linked to a specific user

The database schema and table definitions are provided as SQL scripts.

---

## Technologies Used

* **Java** – application development
* **Java Swing** – graphical user interface
* **MySQL** – database management system
* **JDBC** – database connectivity

---

## Project Structure

```
task-track-ttms/
├── app/
│   └── Task-Manager-Java.zip
│
├── database/
│   └── db.sql
│
├── docs/
│   ├── SRS.pdf
│   ├── SDS.pdf
│   ├── SPMP.pdf
│   └── STP.pdf
│
├── README.md
└── requirements.txt
```

---

## How to Run

1. Download and extract `Task-Manager-Java.zip` from the `app/` folder.
2. Open the project in a Java IDE such as NetBeans.
3. Create a MySQL database and execute the SQL script located at:

   * `database/db.sql`
4. Update database connection settings in the Java source code if required.
5. Build and run the project from the IDE.

---

## Documentation

The project includes full IEEE-style documentation:

* **SRS** – Software Requirements Specification
* **SDS** – Software Design Specification
* **SPMP** – Software Project Management Plan
* **STP** – Software Test Plan

These documents describe the system requirements, design decisions, project planning, and testing strategy in detail.

---

## Learning Outcomes

* Applying software engineering documentation standards
* Designing and implementing database-backed applications
* Integrating Java applications with MySQL databases
* Developing and testing a complete software system

---

## Future Improvements

* Add task priority levels and categories
* Implement reminders and notifications
* Improve user interface design
* Extend the system to support team-based task sharing
