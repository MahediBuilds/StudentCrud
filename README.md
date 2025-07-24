# 🧑‍🎓 Student CRUD REST API with Spring Boot

This project is a simple **Student CRUD (Create, Read, Update, Delete)** REST API built using **Spring Boot**, **Spring Data JPA**, and **H2 Database**. It demonstrates basic CRUD operations using RESTful endpoints and can be tested using **Postman**.

---

## 🛠️ Technologies Used
- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 In-Memory Database
- Postman (for testing)

---

## 📂 Project Structure
```
src/
 └── main/
     ├── java/
     │   └── com.test.studentcrud/
     │       ├── controller/      → REST controller
     │       ├── entity/          → Student entity
     │       └── repository/      → JPA repository
     └── resources/
         └── application.properties
```

## ⚙️ API Endpoints

| Method | Endpoint              | Description               |
|--------|-----------------------|---------------------------|
| POST   | `/students`           | Add a new student         |
| GET    | `/students`           | Get all students          |
| GET    | `/students/{id}`      | Get student by ID         |
| PUT    | `/students/{id}`      | Update student by ID      |
| DELETE | `/students/{id}`      | Delete student by ID      |

---

## 🧪 API Testing with Postman

### ✅ Add Student 1
<img width="600" src="https://github.com/user-attachments/assets/93d8b1ec-f3a4-408d-88dc-a9d7c740c81b" />

### ✅ Add Student 2
<img width="600" src="https://github.com/user-attachments/assets/eabb8223-d0c3-4c84-b4a0-f320a3fa7bed" />

### 📥 Get All Students
<img width="600" src="https://github.com/user-attachments/assets/a82da8db-000f-4dca-8c50-cc5df074fe47" />

### 🔍 Get Student by ID
<img width="600" src="https://github.com/user-attachments/assets/108e025c-a09a-43df-853f-461dc4d16f88" />

### 🔁 Update Student 1
<img width="600" src="https://github.com/user-attachments/assets/12d12856-4cac-4324-ab44-9892e8fc468f" />

### ❌ Delete Student 1
<img width="600" src="https://github.com/user-attachments/assets/fe0a0136-d937-433f-b45c-35ed6b9e3359" />

---
