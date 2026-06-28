# API Gateway

A Spring Cloud Gateway application that serves as the single entry point for all client requests in a microservices architecture. It provides centralized routing, filtering, security, and load balancing for backend services.

## 🚀 Features

- Centralized API routing
- Dynamic route configuration
- Integration with Eureka Service Registry
- Load balancing
- Global request and response filters
- Authentication and authorization support
- CORS configuration
- Fault tolerance and resilience
- Easy integration with Spring Boot microservices

## 🛠️ Tech Stack

- Java 17+
- Spring Boot
- Spring Cloud Gateway
- Spring Cloud Netflix Eureka Client
- Spring Security (Optional)
- Maven

## 📁 Project Structure

```
src
├── main
│   ├── java
│   ├── resources
│   │   ├── application.yml
│   │ 
│   └── ...
└── test
```

## 📌 Prerequisites

- Java 17 or later
- Maven 3.8+
- Eureka Server
- Config Server (Optional)

## ⚙️ Configuration

Example `application.yml`

```yaml
server:
  port: 3333

spring:
  application:
    name: API-GATEWAY

  cloud:
    gateway:
      discovery:
        locator:
          enabled: true
```

## ▶️ Running the Application

Clone the repository:

```bash
git clone https://github.com/gaikwad-siddharth/api-gateway.git
```
