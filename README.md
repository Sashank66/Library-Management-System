# Library Management System

A beginner-friendly Java + JDBC + MySQL console application to manage books, members, issue records, and return records.

## Tech Stack
- Java
- JDBC
- MySQL
- Maven

## Features
- add a new book
- view all books
- add a member
- view all members
- issue a book
- return a book
- view issued books

## Project Structure
```text
library-management-system/
├── src/
│   ├── DBConnection.java
│   ├── BookService.java
│   ├── MemberService.java
│   ├── IssueService.java
│   └── LibraryManagementSystem.java
├── sql/
│   ├── schema.sql
│   └── sample_data.sql
├── pom.xml
└── README.md
```

## Database Setup
### 1) Create database
```sql
CREATE DATABASE library_management;
USE library_management;
```

### 2) Run schema
Execute:
- `sql/schema.sql`

### 3) Optional sample data
Execute:
- `sql/sample_data.sql`

## Update Database Credentials
Open `src/DBConnection.java` and update:
- database URL
- username
- password

## Maven Dependency
This project already includes the MySQL JDBC dependency in `pom.xml`.

## How to Run
### Compile using Maven
```bash
mvn compile
```

### Run the program
```bash
mvn exec:java -Dexec.mainClass="LibraryManagementSystem"
```

## Resume-Friendly Description
Developed a Java-based library management system using JDBC and MySQL to manage books, members, issue/return transactions, and record handling through a console-based application.

## Beginner Note
This is a console project, which is very useful for showing Java, OOP, JDBC, and SQL concepts in interviews.
