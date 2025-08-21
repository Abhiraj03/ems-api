# Employee Management System (EMS)

A simple Employee Management System built with **Spring Boot** and **PostgreSQL**.  
This project demonstrates backend CRUD operations for managing employees.

---

## Tech Stack
- **Java 17**  
- **Spring Boot** (Spring Web, Spring Data JPA)  
- **PostgreSQL**  
- **Maven**  

---

## Setup & Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ems-api.git
cd ems-api
```
### 2. Configure Database
Create a PostgreSQL database named ems.
Copy the file src/main/resources/application.properties.example to:
```bash
src/main/resources/application.properties
```
Update it with your local database username and password.

### 3. Run the App

Using Maven wrapper:
```bash
./mvnw spring-boot:run
```
Or from IntelliJ IDEA, run the EmsApplication main class.

### Usage
The app starts on http://localhost:8080/
It exposes basic REST APIs for managing employees (add, update, delete, list).

