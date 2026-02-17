# 📝 To-Do List API

A RESTful To-Do List API built using Spring Boot .  
This project demonstrates clean architecture, DTO mapping, service-layer design, and proper REST API practices.

---

## 🚀 Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database (In-Memory)
- Maven
- REST APIs
- UUID for Task Identification

---

## 📂 Architecture

Controller → DTO → Mapper → Service → Repository → Database

### 🔹 Layers

- **Controller** – Handles HTTP requests
- **DTO** – Data transfer between client & server
- **Mapper** – Converts DTO ↔ Entity
- **Service** – Business logic
- **Repository** – Database interaction
- **Exception Handling** – Custom Runtime Exceptions

---

## 🔥 Features

- ✅ Create To-Do
- 📋 List All To-Dos
- ✏ Update To-Do
- ❌ Delete To-Do
- 📌 Enum-based Status (OPEN / COMPLETED)
- 🆔 UUID-based IDs
- 🧠 Clean Layered Architecture

---

## 📌 API Endpoints

### ➕ Create To-Do
POST `/api/v1/tasks`

```json
{
  "title": "Learn Spring Boot",
  "description": "Build To-Do API project",
  "dueDate": "2026-02-20",
  "priority": "HIGH"
}
```

---

### 📋 Get All To-Dos
GET `/api/v1/tasks`

---

### ✏ Update To-Do
PUT `/api/v1/tasks/{id}`

```json
{
  "title": "Updated Title",
  "description": "Updated Description",
  "dueDate": "2026-02-25",
  "priority": "MEDIUM",
  "status": "COMPLETED"
}
```

---

### ❌ Delete To-Do
DELETE `/api/v1/tasks/{id}`

---

## 🧠 Enum Values

**TaskStatus**
- OPEN
- COMPLETED

---

## ⚙ How to Run

1. Clone repository
```
git clone https://github.com/annattiwary12/task-.git
```

2. Go inside project
```
cd task-
```

3. Run application
```
mvn spring-boot:run
```

4. Open in browser:
```
http://localhost:8080
```

---

## 📌 Database

Using H2 in-memory database for development.

---

## 👨‍💻 Author

Anant Tiwary  
Java Backend Developer

---

## 🔮 Future Improvements

- Pagination
- Global Exception Handling
- Swagger Documentation
- JWT Authentication
- Docker Support
- PostgreSQL Integration

---

⭐ If you found this useful, consider giving it a star!


<img width="1913" height="889" alt="image" src="https://github.com/user-attachments/assets/116c7f06-3823-4c91-aebf-2ef814fdeb21" />

