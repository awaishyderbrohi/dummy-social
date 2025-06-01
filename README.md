# 📱 dummy-social

dummy-social is a full-stack mock social media platform built with **Spring Boot** and **Angular**. It offers basic social media functionalities including authentication, posting, liking, and commenting.
**Still underDevelopment**

---

## 🛠️ Tech Stack

### 🚀 Backend
- Java 17+
- Spring Boot (Spring MVC, Spring Security, JPA)
- PostgreSQL
- JWT (JSON Web Tokens) for authentication
- Maven

### 🌐 Frontend
- Angular 16+
- TypeScript
- Nebular UI / Tailwind CSS / Bootstrap (choose your UI framework)
- Angular HTTPClient

---

## ✨ Features

- ✅ User Registration & Login
- 🔐 JWT-based Authentication
- 👤 Profile Management
- 📝 Create, Edit, Delete Posts
- ❤️ Like/Unlike Posts
- 💬 Add Comments
- 🔍 Search Users or Posts
- 📁 Upload Profile and Post Images

---

## 🧩 Project Structure
│
├── backend/ # Spring Boot API
│ ├── src/main/java/... # Java source code
│ ├── resources/
│ │ ├── application.properties
│
├── frontend/ # Angular App
│ ├── src/
│ ├── angular.json
│
├── README.md


---

## 🧪 Prerequisites

- Java 17+
- Node.js & npm
- Angular CLI
- PostgreSQL
- Maven

---

## 🚀 Setup Instructions

### 🔧 Backend Setup (Spring Boot)

1. **Create PostgreSQL Database**

``sql
CREATE DATABASE dummy_social;

```sql
## Configure application.properties
spring.datasource.url=jdbc:postgresql://localhost:5432/dummy_social
spring.datasource.username=your_db_user
spring.datasource.password=your_db_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

spring.security.jwt.secret=your_jwt_secret
