# Ecommerce-Microservices-SpringBoot


##  Overview
This project is a fully functional **E-commerce application** built using **Spring Boot** and **Spring Cloud** following a **microservices architecture**.  
It was developed during my internship at **Ejada Systems Ltd. – Egypt Branch** as part of my **Computer Science and Engineering** studies at GUC.

The application is split into multiple microservices that communicate through REST APIs, with service discovery, centralized configuration, and fault tolerance mechanisms.

---

## Technologies Used
- **Java 17**
- **Spring Boot**
- **Spring Cloud**
  - Eureka Server (Service Discovery)
  - Feign Client (Inter-service Communication)
  - Spring Config Server (Centralized Configuration)
  - Spring Cloud Gateway (API Gateway)
- **Spring Data JPA**
- **MySQL**
- **Resilience4j** (Circuit Breakers)
- **Maven**
- **Postman** (API Testing)
- **GitHub** (Version Control)

---

##  Microservices Overview

### 1. **Wallet Service**
- User registration & login
- Wallet creation & management
- Deposit and withdrawal functionality
- Transaction history API

### 2. **Shop Service**
- Product creation & management
- Shopping cart management
- Order creation & checkout
- Payment processing integration

### 3. **Inventory Service**
- Product creation & stock management
- Inventory tracking
- REST APIs for stock validation

---

##  Additional Components
- **Eureka Server**: Registers all microservices for discovery
- **API Gateway**: Routes client requests to the appropriate service
- **Config Server**: Manages externalized configuration files
- **Circuit Breaker (Resilience4j)**: Ensures fault tolerance when a microservice is down

---

##  How to Run the Project

### 1. **Clone the Repository**
```bash
git clone https://github.com/YOUR-USERNAME/Ecommerce-Microservices-SpringBoot.git
cd Ecommerce-Microservices-SpringBoot

