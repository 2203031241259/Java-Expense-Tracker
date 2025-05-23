# Expense Tracker (Java)

A simple console-based Expense Tracker written in Java. It supports expense management with database storage and basic reports.

## Features
- Add, update, delete expenses
- Store and retrieve from SQLite database
- Generate expense reports

## Technologies
- Java
- SQLite (via JDBC)

## How to Run

### Prerequisites
- Java JDK 8 or above
- SQLite JDBC driver (if needed)

### Compile & Run

```bash
javac -cp ".;lib/sqlite-jdbc.jar" src/*.java
java -cp ".;lib/sqlite-jdbc.jar;src" Main
