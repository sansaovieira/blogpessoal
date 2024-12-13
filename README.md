# Personal Blog - Posts API

👋 Welcome to the **Personal Blog - Posts API** repository!

![Spring Logo](https://upload.wikimedia.org/wikipedia/commons/4/44/Spring_Framework_Logo_2018.svg)

This project is part of **Generation Brasil's** **Bootcamp**, which was a challenge presented after the backend block, and is focused on developing a fully functional personal blog application. The backend provides a robust API for managing blog posts and serving as a learning platform to implement best practices in software development, architecture, and teamwork.

---

## 📋 Overview
The **Posts API** allows CRUD (Create, Read, Update, Delete) operations for blog posts, ensuring a scalable and secure content management system. Designed with modern tools and technologies, this project demonstrates the practical application of Java and Spring Framework features.

---
## 🛠️ Features

- **Create Posts**: Add new posts to the blog.

- **Read Posts**: Retrieve all available posts or filter specific ones.
- **Update Posts**: Modify and update existing content.
- **Delete Posts**: Removes messages that are no longer allowed.
- **Secure API**: Authentication and breakout authorization using JWT.

---
## 🏗️ Technologies used

### Languages ​​and frameworks
- **Java**: core programming language.
- **My SQL**: to save the date.
- **Spring Boot**: framework for building microservices.
- **Spring Data JPA**: integration with Hibernate for database interactions.
- **Spring Security**: ensures secure access to the API.
- **JWT (JSON Web Tokens)**: token-based authentication.

### Tools and libraries
- **Hibernate**: ORM (Object-Relational Mapping) for database operations.
- **Maven**: dependency management and construction tool. - **H2 Database** (for development): test-grade database.

---

## 📑 Documentation

The API documentation includes all available endpoints, request/response formats, and request requirements. See the `docs/` folder or the dedicated [API Documentation](#) (link placeholder) for detailed information.

---

## 🚀 Getting Started

### Prerequisites

-Java 17+
- Maven

### Installation

1. Clone the repository:
```bash
clone from git https://github.com/sansaovieira/blogpessoal.git
cd blogpessoal
```
2. Create the project:
```bash
mvn clean install
```
3. Run the application:
```bash
mvn spring-boot:execute
```

### Default endpoints
- `GET /posts`: Retrieves all posts.
- `POST /posts`: Creates a new post.
- `PUT /posts/{id}`: Updates a post by ID.
- `DELETE /posts/{id}`: Deletes a post by ID.

---

## 🔒 Security

An API is secured using **Spring Security** and **JWT**. Authentication is required to access secured endpoints.

### Steps for authentication
1. Use the `/auth/login` endpoint to obtain a JWT token.
2. Include the token in the `Authorization` header as `Bearer <token>` for subsequent transactions.

---

## 🤝 Contribution guidelines

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
```bash
git checkout -b feature/your-feature-name
```
3. Commit your changes and push them to your branch.
4. Open a pull request.

---

## 📧Contact

For any questions or feedback, feel free to contact us via [https://www.linkedin.com/in/sansaovieira/](https://github.com/sansaovieira/blogpessoal/issues) or contact the repository maintainer.

---
Thanks for exploring **Blog Pessoal - Posts API**! Happy trading! 🎉


This project is part of Generation Brasil's Bootcamp, where we are developing a complete personal blog application with a dedicated API for posts. Here, you will find the source code, the API structure and all the documentation needed to understand and collaborate on the project.
