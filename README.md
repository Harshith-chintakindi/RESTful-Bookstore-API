# RESTful-Bookstore-API
Create a backend API for managing books and authors
# 📚 Bookstore REST API

A RESTful **Bookstore API** built with **Spring Boot** that manages **Books** and **Authors**.  
Supports CRUD operations, pagination, filtering, and API documentation with Swagger UI.  

---

## 🚀 Features
- ✅ Manage **Books** (Create, Read, Update, Delete)  
- ✅ Manage **Authors** (Create, Read, Update, Delete)  
- ✅ Search books by **title** or **author**  
- ✅ Pagination and sorting support  
- ✅ Integrated **Swagger UI** documentation  
- ✅ Tested with **Postman**  
- ✅ Connected to **MySQL (XAMPP)**  

---

## 🛠️ Tech Stack
- **Java 17+**
- **Spring Boot 3.x**
- **Spring Data JPA**
- **MySQL (XAMPP)** / H2 (in-memory for testing)
- **Swagger / Springdoc**
- **Postman** (for API testing)

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
#//application properties:
git clone https://github.com/your-username/bookstore-api.git
cd bookstore-api
spring.datasource.url=jdbc:mysql://localhost:3306/bookstore
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
#spring boot run
mvn-install
mvn spring-boot:run
# project structure:
bookstore-api/
 ├── src/main/java/com/bookstore/bookstore_api/
 │   ├── controller/   # REST Controllers
 │   ├── model/        # Entities (Book, Author)
 │   ├── repository/   # JPA Repositories
 │   ├── config/       # Swagger Configuration
 │   └── BookstoreApiApplication.java
 ├── src/main/resources/
 │   ├── application.properties
 └── pom.xml
#Api Endpoints//
| Method | Endpoint      | Description       |
| ------ | ------------- | ----------------- |
| GET    | `/books`      | List all books    |
| GET    | `/books/{id}` | Get book by ID    |
| POST   | `/books`      | Create new book   |
| PUT    | `/books/{id}` | Update book by ID |
| DELETE | `/books/{id}` | Delete book by ID |

#Authors//
| Method | Endpoint        | Description         |
| ------ | --------------- | ------------------- |
| GET    | `/authors`      | List all authors    |
| GET    | `/authors/{id}` | Get author by ID    |
| POST   | `/authors`      | Create new author   |
| PUT    | `/authors/{id}` | Update author by ID |
| DELETE | `/authors/{id}` | Delete author by ID |
 ## 🔎 Swagger Documentation
![Swagger UI](images/swagger.png)

## 🧪 Postman Testing
![Postman](images/postman.png)

## 🗄️ Database (XAMPP / MySQL)
![Database](images/database.png)





