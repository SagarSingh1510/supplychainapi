# 🚚 Enterprise Supply Chain API

This repository is an adapted copy of [tom-coder-blip/supply-chain-api-spring-java](https://github.com/tom-coder-blip/supply-chain-api-spring-java). See the upstream repository for original project history and attribution.

A scalable backend system built with **Java** and **Spring Boot** to manage complex logistics for enterprise environments.

---

## 📖 Overview
This project is a large-scale Supply Chain API designed for enterprise use cases.  
It enforces **role-based access control (RBAC)**, ensuring Admins, Suppliers, Warehouse Managers, and Customers each operate within clearly defined permissions.  
The system streamlines supply chain operations with layered security, scalable architecture, and real-world business logic.

---

## ✨ Features
- Role-based access control (RBAC) with secure JWT authentication  
- Product and inventory management  
- Order placement and fulfillment workflows  
- Real-time stock tracking across warehouses  
- Flyway-managed schema migrations  
- Interactive API testing via Swagger UI  

---

## 🔐 Roles & Permissions
- **Admin**: Manage users and oversee all transactions  
- **Supplier**: Maintain product catalog and stock  
- **Warehouse Manager**: Handle inventory and order fulfillment  
- **Customer**: Place and track orders  

---

## ⚙️ Tech Stack
- Java 21  
- Spring Boot  
- Spring Security  
- PostgreSQL + Flyway  
- Swagger UI  
- Docker & Docker Compose  

---

## 🚀 Live Demo & Resources
- [Project Documentation](docs/project-overview.md)  
- [Swagger Testing Guide](docs/swagger-guide.md)  

---

## 🧰 Getting Started

### Prerequisites
- Java 21 
- Docker  
- PostgreSQL  

### Setup
```bash
git clone https://github.com/tom-coder-blip/supply-chain-api-spring-java.git
cd supply-chain-api-spring-java
docker-compose up
