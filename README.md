# **Spring Boot Microservices**

## Description
This project is a collection of microservices built using Spring Boot. Each microservice is designed to handle a specific aspect of the application.

## Prerequisites
- Java 21 or higher
- Maven 3.6.0 or higher
- Spring Boot 3.3.5 or higher
- PostgreSQL 13 or higher

## Quick Start
1. Clone the repository:
    ```sh
    git clone https://github.com/harvey-jean/microservice-school.git
    ```
2. Navigate to the project directory:
    ```sh
    cd microservice-school
    ```
3. Build the project using Maven:
    ```sh
    mvn clean install
    ```
4. Run the application:
    ```sh
    mvn spring-boot:run
    ```

## Microservices
### Config Server
Handles external configuration for distributed systems.

### Discovery Service
Service registry for locating microservices.

### Student Service
Manages student-related operations.

### School Service
Manages school-related operations.

### Gateway Service
API Gateway for routing requests to appropriate microservices.

## Configuration
Configuration details for the project.

## High-Level Architecture
![Microservice-1.png](..%2F..%2F..%2FPictures%2FMicroservice-1.png)