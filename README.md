# Job Application Platform Microservices

## Overview
This project implements a **job application platform** using a **microservices architecture** with **Spring Boot**. The application is divided into modular, independent services, each responsible for a specific business function, such as user management, job listings, applications, and notifications. This structure allows for flexible development, easy scaling, and maintainable code, ideal for large-scale deployments.

## Features
- **Modular Microservices**: Independent services for users, jobs, applications, and notifications.
- **RESTful APIs**: Each service provides its own RESTful endpoints for efficient, standardized communication.
- **Service Discovery**: **Eureka** server for dynamic service registration and discovery.
- **API Gateway**: **Spring Cloud Gateway** for routing, load balancing, and API management.
- **Centralized Configuration**: **Spring Cloud Config** for externalized configuration across environments.
- **Fault Tolerance**: Implements **Resilience4J** for circuit-breaking and service resiliency.
- **Distributed Tracing**: **Zipkin** and **Sleuth** for tracing requests across services, with **Grafana** for monitoring.
- **Authentication and Authorization**: OAuth2 and JWT for secure access control.
- **Database Per Service**: Isolated databases per service ensure data consistency and reliability.

## Technology Stack
- **Backend**: Spring Boot, Spring Cloud, Eureka, Spring Cloud Gateway, Spring Security
- **Databases**: MySQL, PostgreSQL, MongoDB
- **Containerization**: Docker
- **Monitoring**: Zipkin, Sleuth, Prometheus, Grafana
- **Security**: OAuth2, JWT
- **Orchestration**: Kubernetes (optional, for deployment)

## Microservices Structure
- **User Service**: Manages user profiles, authentication, and authorization.
- **Job Service**: Handles job postings, categories, and job details.
- **Application Service**: Manages job applications, application status, and history.
- **Notification Service**: Sends real-time notifications for application status updates.

## Getting Started

### Prerequisites
- **Java 17** or higher
- **Maven** (for building the project)
- **Docker** (for containerization)
- **Postman** (for API testing)


