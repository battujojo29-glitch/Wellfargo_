# 🏦 Wells Fargo — Financial Advisor App

> A Java Spring Boot application simulating a financial advisory system with client management, portfolio tracking, and security modules.

---

## 📋 Project Overview

The Wells Fargo Financial Advisor App is a backend simulation of a real-world financial advisory platform. It allows financial advisors to manage clients, track portfolios, and handle secure transactions.

---

## ✨ Features

- 👤 **Client Management** — Add, update, and manage client profiles
- 💼 **Portfolio Tracking** — Monitor and manage client investment portfolios
- 🔐 **Security Module** — Secure authentication and authorization
- 🧑‍💼 **Financial Advisor** — Advisor-client relationship management

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Java | Core programming language |
| Spring Boot | Backend framework |
| Maven | Build and dependency management |
| REST APIs | Client-server communication |
| JUnit | Unit testing |

---

## 🗂️ Project Structure

```
Wellfargo/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/wellfargo/
│   │           ├── Client/
│   │           ├── Portfilo/
│   │           ├── Security/
│   │           └── finanical advisor/
│   └── test/
├── .mvn/wrapper/
├── .gitignore
├── .gitattributes
├── mvnw
├── mvnw.cmd
└── pom.xml
```

---

## 🚀 Getting Started

### Prerequisites
- Java 17+
- Maven 3.8+
- IntelliJ IDEA (recommended)

### Run the project

```bash
# Clone the repository
git clone https://github.com/battujojo29-glitch/Wellfargo_.git

# Navigate into the project
cd Wellfargo_

# Build the project
./mvnw clean install

# Run the application
./mvnw spring-boot:run
```

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/clients` | Get all clients |
| POST | `/api/clients` | Add a new client |
| GET | `/api/portfolio/{id}` | Get portfolio by client ID |
| PUT | `/api/clients/{id}` | Update client details |
| DELETE | `/api/clients/{id}` | Delete a client |

---

## 🧪 Testing

```bash
# Run all tests
./mvnw test
```

---

## 👨‍💻 Author

**Jai Harsha Battu**
- GitHub: [@battujojo29-glitch](https://github.com/battujojo29-glitch)
- Location: Hyderabad, India 🇮🇳

---

## 📄 License

This project is licensed under the MIT License.

---

<p align="center">Built with ❤️ using Java & Spring Boot</p>
