# 🛒 E-Commerce Microservices Application

This is a distributed **E-Commerce Application** built using a **Microservices Architecture**. Each major business capability is broken down into a dedicated service to ensure scalability, fault tolerance, and independent deployment.


## 🧩 Microservices Overview

Each microservice is hosted in its own repository for independent development and deployment. Click the links below to access each service:

| Service Name         | Description                               | Repository Link |
|----------------------|-------------------------------------------|------------------|
| 🛍️ Product Service   | Manages product catalog and inventory      | [ProductService](https://github.com/NithinBommerla/ProductService) |
| 👤 User Service      | Handles user registration and authentication | [UserService](https://github.com/NithinBommerla/UserService) |
| ✉️ Email Service     | Sends transactional and marketing emails   | [EmailService](https://github.com/NithinBommerla/EmailService) |
| 💳 Payment Service   | Manages payment processing and gateways    | [PaymentService](https://github.com/NithinBommerla/PaymentService) |
| 🔍 Service Discovery | Enables service registration and discovery | [ServiceDiscovery](https://github.com/NithinBommerla/ServiceDiscovery) |
| 📈 API Gateway       | Entry point and request routing for clients | [APIGateway](https://github.com/NithinBommerla/APIGateway) |


## 📐 Architecture

This system is built using:

- Spring Boot (Java)
- REST APIs
- Eureka (Service Discovery)
- API Gateway (e.g., Spring Cloud Gateway / Kong / NGINX)
- Kafka (for async communication)
- PostgreSQL (and RDBMS)
- Docker + Docker Compose
- Redis (caching)
- JWT (authentication)

## 🚀 Getting Started

1. Clone the repositories listed above.
2. Start **Service Discovery** and **API Gateway** first.
3. Start core services: Product, User, Order, etc.
4. Run supporting services: Email, Payment, etc.
5. Access the application via `http://localhost:8080` (API Gateway).


## 🧪 Testing

Each service has its own set of:

* Unit Tests
* Integration Tests

---

## 📬 Contact

For questions, contact [nithinbommerla99@gmail.com](mailto:nithinbommerla99@gmail.com)

