# Spring Boot Web Application

This project is a modern Java web application built with **Spring Boot**. Unlike traditional Servlet applications, this project uses an **embedded Tomcat server**, meaning it runs as a standalone application without the need for manual deployment to an external server.



---

## Key Characteristics

* **Embedded Server**: Includes an internal Tomcat instance.
* **Inversion of Control (IoC)**: Spring manages the object lifecycle via annotations like `@Service` and `@RestController`.
* **Dependency Injection**: Services are injected through constructors, promoting decoupled code.
* **Simplified Configuration**: Minimal XML; configuration is handled via Java annotations and `application.properties`.

---

## 📁 Project Structure

```text
src/main/java/com/example/mywebapp/
├── controller/
│   └── HelloController.java  # Handles REST requests
├── service/
│   └── MessageService.java   # Business logic (IoC Component)
└── MywebappApplication.java  # Main entry point
