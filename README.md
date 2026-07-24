# Spring Boot Demo

A simple Spring Boot application demonstrating the basics of building REST APIs using Spring Boot.

## 🚀 Features

- Spring Boot 3.x
- REST API using `@RestController`
- Simple GET endpoint
- Maven project structure
- Easy to extend for larger applications

## 🛠️ Technologies Used

- Java 17 (or your installed version)
- Spring Boot
- Maven
- Spring Web
- VS Code / IntelliJ IDEA

## 📁 Project Structure

```
src
├── main
│   ├── java
│   │   └── com.example.demo
│   │       ├── DemoApplication.java
│   │       └── HelloController.java
│   └── resources
│       └── application.properties
└── test
```

## ▶️ Getting Started

### Clone the repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```

### Run the application

Using Maven Wrapper:

```bash
./mvnw spring-boot:run
```

Windows:

```bash
mvnw.cmd spring-boot:run
```

Or using Maven:

```bash
mvn spring-boot:run
```

## 🌐 API Endpoint

### GET `/hello`

**Request**

```
GET http://localhost:8080/hello
```

**Response**

```text
Hello World
```

## 📦 Build the Project

```bash
mvn clean install
```

## 🧪 Run Tests

```bash
mvn test
```

## 👨‍💻 Author

**Utkarsh Sharma**

- GitHub: https://github.com/utkarshh55
- LinkedIn: https://www.linkedin.com/in/utkarsh-sharma-1252622a8

## 📄 License

This project is licensed under the MIT License.
