# 🛒 E-Commerce Microservices Backend

This is a **production-grade e-commerce backend** built using **Java Spring Boot** and **microservices architecture**. It manages orders, users, inventory, product reviews, and notifications, and is designed for scalability, maintainability, and observability.

> 🔗 **Live Swagger Docs**: `http://localhost:8080/swagger`  
> 📦 **PostgreSQL | Kafka | Dockerized | CI/CD | Observability Ready**

---

## 🧩 Microservices Overview

| Microservice         | Description                                    |
|----------------------|------------------------------------------------|
| **API Gateway**      | Routes external requests to appropriate services |
| **Eureka Server**    | Service discovery and registration              |
| **User Service**     | Manages user information and roles              |
| **Auth Service**     | Handles JWT-based authentication                |
| **Inventory Service**| Tracks product stock and availability           |
| **Order Service**    | Processes customer orders                       |
| **Review Service**   | Manages product reviews and ratings             |
| **Notification Service** | Sends user notifications                  |

---

## ⚙️ Technologies Used

- Java 17, Spring Boot (MVC, Security, Data JPA)
- PostgreSQL, Kafka, Docker, Maven
- RESTful APIs, JWT Authentication
- Eureka, API Gateway Pattern
- JUnit, Mockito, TestContainers
- Prometheus, Grafana, Loki, Zipkin, OpenTelemetry
- GitHub Actions (CI/CD)

---

## 🧪 Testing

- ✅ Unit Tests (JUnit, Mockito)
- ✅ Integration Tests (TestContainers)
- ✅ CI/CD runs tests before Docker image builds

---

## 🚀 CI/CD & Deployment

- **GitHub Actions**: Automates build, test, Docker image creation, and push to Docker Hub
- **Docker Compose**: Launch all services and infrastructure (PostgreSQL, Kafka, etc.)
- **Kubernetes / Jenkins** (optional): Planned for future enhancements

---

## 📦 Running the Project Locally

### Option 1: Quick Start with Docker Compose

```bash
git clone https://github.com/your-username/e-commerce-microservices.git
cd e-commerce-microservices/deployment
docker-compose up -d
