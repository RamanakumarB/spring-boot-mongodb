# Spring Boot + MongoDB REST API

A REST API built with Spring Boot and Spring Data MongoDB, utilizing Docker for local database hosting. This is a learning project acting as the backend foundation for an upcoming React full-stack integration.

## Tech Stack
* **Backend:** Java 21, Spring Boot 4.1.1, Spring Data MongoDB 5.1.1, Maven
* **Database:** MongoDB 9.0.4 (via Docker)
* **Tools:** Docker Desktop (WSL 2), Lombok, IntelliJ IDEA

## Prerequisites
* **JDK 21** (Microsoft OpenJDK 21.0.12 or similar)
* **Docker Desktop** (with WSL 2 enabled)
* **Maven**

## Local Setup Instructions

### 1. Database Configuration
This project uses environment variables for database credentials.
Create a `.env` file in the project root and add your credentials:

```env
MONGO_USER=admin
MONGO_PASSWORD=your_secure_password