🛒 E-Commerce Backend (Spring Boot)

This repository contains the backend implementation of an e-commerce web application built using Spring Boot.
It provides RESTful APIs for managing products, handling image uploads, maintaining stock availability, and supporting cart operations.

🚀 Tech Stack

Java

Spring Boot

Spring Data JPA

Hibernate

H2 In-Memory Database

Maven

Lombok

📌 Features

Product CRUD operations (Create, Read, Update, Delete)

Image upload and retrieval for products

Stock quantity and availability management

REST APIs consumed by React frontend

In-memory H2 database for development and testing

🔗 Frontend Repository

The frontend for this project is developed using React and is available here:
👉 (Add frontend repo link here later)

⚙️ Project Setup
1️⃣ Clone the repository
git clone https://github.com/USERNAME/ecom-backend.git

2️⃣ Open in IntelliJ IDEA

Open IntelliJ

Select Open

Choose the project folder

3️⃣ Run the application
mvn spring-boot:run


or run EcomProjectApplication.java directly.

🌐 API Base URL
http://localhost:8080/api

🧪 H2 Database Console

URL: http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:pawandb

Username: sa

Password: (leave empty)

📂 Project Structure
src/main/java
 ├── controller
 ├── service
 ├── repository
 └── model

📝 Notes

This backend is designed to work with a React frontend

H2 database resets data on application restart

Suitable for academic projects and learning full-stack development

👨‍💻 Author

Pawan Bhandari

⭐ Future Enhancements

User authentication & authorization

Persistent database (MySQL/PostgreSQL)

Order & payment integration
