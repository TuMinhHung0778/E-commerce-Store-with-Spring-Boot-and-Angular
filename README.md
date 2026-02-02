# ShopApp - Fullstack E-commerce Platform

A comprehensive E-commerce application built with **Java Spring Boot** and **Angular**. This project demonstrates a modern, scalable architecture with a focus on security, performance, and user experience. It features a complete shopping flow from product discovery to order placement, backed by a robust RESTful API.

## 🚀 Key Features

*   **User Authentication & Security**: 
    *   Secure Registration & Login functionality.
    *   **JWT (JSON Web Token)** based authentication.
    *   **OAuth2** support.
    *   Role-based Access Control (User vs Admin).
*   **Product Management**: 
    *   Browse products with pagination and filtering.
    *   Categorized product listings.
    *   Detailed product views with multiple images.
*   **Shopping & Ordering**:
    *   Coupon system for discounts.
    *   Order placement and tracking.
    *   Detailed Order history handling.
*   **User Interaction**:
    *   Product commenting and review system.
*   **Tech Features**:
    *   Server-Side Rendering (SSR) with Angular for better SEO.
    *   Database migrations with Flyway.
    *   API Documentation with OpenAI/Swagger.

## 🛠 Tech Stack

### Backend (Spring Boot)
*   **Core**: Java 17, Spring Boot 3.1.2
*   **Database**: MySQL, Spring Data JPA (Hibernate)
*   **Security**: Spring Security, JWT, OAuth2 Client
*   **Caching & Performance**: Redis
*   **Messaging**: Apache Kafka (Integration ready)
*   **Utilities**: Lombok, ModelMapper, Docker
*   **API Documentation**: SpringDoc OpenAPI (Swagger UI)

### Frontend (Angular)
*   **Framework**: Angular 17
*   **Styling**: Bootstrap 5, FontAwesome
*   **Architecture**: Component-based, RxJS for reactive programming
*   **Rendering**: Angular SSR (Server Side Rendering)

## ⚙️ Project Structure

```bash
Java-Springboot-And-Angular/
├── shopapp-backend/     # Spring Boot API Application
├── shopapp-angular/     # Angular Frontend Application
└── README.md           # Project Documentation
```

## 🔧 Installation & Setup

### Prerequisites
Ensure you have the following installed:
*   **Java JDK 17+**
*   **Node.js LTS** & **npm**
*   **MySQL Server**
*   **Redis** (Optional, for caching)
*   **Kafka** (Optional, if enabling messaging features)

### Backend Setup
1.  Navigate to the backend directory:
    ```bash
    cd shopapp-backend
    ```
2.  Configure Database:
    *   Open `src/main/resources/application.yml` (or `.properties`).
    *   Update `spring.datasource.url`, `username`, and `password` to match your MySQL setup.
3.  Run the application:
    ```bash
    ./mvnw spring-boot:run
    ```
    *The API will be available at `http://localhost:8088` (default).*

### Frontend Setup
1.  Navigate to the frontend directory:
    ```bash
    cd shopapp-angular
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Start the development server:
    ```bash
    npm start
    ```
4.  Access the application at `http://localhost:4200`.

## 📚 API Documentation
Once the backend is running, you can explore the REST APIs via Swagger UI:
*   URL: `http://localhost:8088/swagger-ui/index.html` (Adjust port if configured differently)

## 🤝 Author
*   **Your Name** - *Fullstack Developer*
*   [Email](mailto:your_email@example.com)
*   [GitHub](https://github.com/yourusername)

---
*This repository is part of my portfolio to demonstrate Fullstack Development skills with Java and Angular.*
