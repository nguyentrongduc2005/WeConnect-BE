# WeConnect - Bridge the Gap 🌐

**WeConnect** is a modern social networking platform designed for seamless connection and knowledge sharing. This project features a decoupled architecture with a robust **Java Spring Boot** backend and a high-performance **React** frontend.

---

## 🚀 Key Features

* **Secure Authentication:** Stateless authentication using **JWT (JSON Web Token)** and **Spring Security**.
* **Dynamic Newsfeed:** Optimized CRUD operations for sharing posts and interacting with content.
* **Social Connectivity:** Efficient friend request system and user relationship management.
* **Real-time Interaction:** (In Development) Instant messaging and notifications using **WebSockets**.
* **Responsive Design:** Fully optimized UI for mobile, tablet, and desktop views.

---

## 🛠 Tech Stack

### Backend (Core Expertise)
* **Java 17 & Spring Boot 3**: High-performance RESTful API development.
* **Spring Security**: Role-Based Access Control (RBAC) and JWT integration.
* **Spring Data JPA**: Efficient database abstraction and query optimization.
* **MySQL**: Relational database management for structured data.
* **Maven**: Dependency management and build automation.

### Frontend
* **React.js (Vite)**: Modern component-based UI development.
* **Tailwind CSS**: Utility-first styling for responsive and modern interfaces.
* **Axios**: Handling API requests with interceptors for JWT management.

### DevOps & Tools
* **Docker**: Containerization for consistent deployment environments.
* **Postman**: Comprehensive API testing and documentation.

---

## 🏗️ System Architecture

The project follows a **Micro-monolith** approach with a clear separation of concerns:
* **Controller Layer**: Handles REST requests and DTO mapping.
* **Service Layer**: Encapsulates business logic.
* **Repository Layer**: Manages data persistence with Hibernate/JPA.
* **Security Layer**: Filters and validates incoming requests via JWT tokens.

---

## 📦 Installation & Setup

### 1. Backend Setup
```bash
# Clone the repository
git clone [https://github.com/nguyentrongduc2005/WeConnect-BE.git](https://github.com/nguyentrongduc2005/WeConnect-BE.git)
cd WeConnect-BE

# Configure Database
# Edit src/main/resources/application.properties with your MySQL credentials

# Run the application
./mvnw spring-boot:run
```
### 1. Frontend Setup
```bash
# Clone the repository
git clone [https://github.com/nguyentrongduc2005/WeConnect-FE.git](https://github.com/nguyentrongduc2005/WeConnect-FE.git)
cd WeConnect-FE

# Install dependencies
npm install

# Start the development server
npm run dev
```
