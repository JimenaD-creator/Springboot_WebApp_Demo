# Spring Boot Web Application

This project is a basic Java web application built with **Spring Boot**.
---

## Key Characteristics
* **Inversion of Control (IoC)**: Spring manages the object lifecycle via annotations like `@Service` and `@RestController`.
* **Dependency Injection**: Services are injected through constructors, promoting decoupled code.
* **Simplified Configuration**: Minimal XML; configuration is handled via Java annotations and `application.properties`.

---

## Project Structure

```text
src/main/java/com/example/mywebapp/
├── controller/
│   └── HelloController.java  # Handles REST requests
├── service/
│   └── MessageService.java   # Business logic (IoC Component)
└── MywebappApplication.java  # Main entry point
```

## Configuration (Port Management)
The application is configured to run on port **8082**.

**File:** `src/main/resources/application.properties`

```properties
server.port=8082
```
