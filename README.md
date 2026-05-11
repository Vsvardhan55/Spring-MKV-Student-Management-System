# Student Management System

A web-based Student Management System developed using Spring Boot and MySQL to manage student records efficiently with CRUD operations and REST API integration.

---

## Features
- Add new student details  
- View all students  
- Update student information  
- Delete student records  
- Search student by ID  
- Responsive user interface  
- Database integration using MySQL  

---

## Technologies Used
- Java  
- Spring Boot  
- Hibernate  
- MySQL  
- HTML  
- CSS  
- Bootstrap  
- Thymeleaf  
- REST APIs  

---

## Project Structure

```bash
src/
 ├── main/
 │    ├── java/
 │    │     ├── controller/
 │    │     ├── service/
 │    │     ├── repository/
 │    │     ├── model/
 │    ├── resources/
 │          ├── templates/
 │          ├── static/
 │          ├── application.properties
```

---

## Setup Instructions

### Clone Repository

```bash
git clone <repository-url>
```

### Configure Database

Update `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/studentdb
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

## Run the Application

Using Maven:

```bash
mvn spring-boot:run
```

Application runs at:

```bash
http://localhost:8080
```

---

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /students | Get all students |
| POST | /students | Add new student |
| PUT | /students/{id} | Update student |
| DELETE | /students/{id} | Delete student |

---

## Learning Outcomes
- Understanding MVC Architecture  
- CRUD Operations using Spring Boot  
- REST API Development  
- Database Connectivity with MySQL  
- Backend Development using Java  

---

## Future Enhancements
- Student Login Authentication  
- Role-Based Access  
- Attendance Management  
- Course Management System  
- Cloud Deployment  

---

## Author
**Sethu Vardhan Valluri**
