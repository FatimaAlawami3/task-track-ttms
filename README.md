# Task Track (TTMS) — Task Tracker Management System (Java + MySQL)

## Overview
**Task Track** is a **Task Tracker Management System (TTMS)** built as a course project to improve task organization and productivity.  
It provides a simple desktop workflow for creating tasks, sorting them by date, marking tasks as completed, and deleting tasks. Registered users can save tasks persistently in a database, while guest users can use the app temporarily without saving data.

## Problem Statement
Managing tasks manually can be time-consuming and error-prone. TTMS helps users organize tasks in one place with a structured flow (create → view → sort → complete → delete), improving daily productivity through a simple and consistent interface.

## Key Features
### Registered Users
- Register with a username and strong password
- Login with saved credentials
- Create tasks with a name and date
- View tasks and mark them as completed (saved in DB)
- Sort tasks by date
- Delete tasks

### Guest Mode
- Continue as a guest without logging in
- Create/view/complete tasks during the session
- Tasks are **not saved** to the database and are removed when the app is closed

## Database
The system uses a MySQL database to store persistent data for registered users and tasks.
- `users` table: user credentials/accounts
- `tasks` table: task data linked to a user

Database script is available in: `database/db.sql`

## Technology Stack
- Java (Desktop Application)
- Java Swing (UI)
- MySQL (Database)
- JDBC (Database connectivity)

## Project Structure
