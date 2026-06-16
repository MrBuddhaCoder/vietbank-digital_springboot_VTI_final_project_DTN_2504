# VietBank Digital - Spring Boot Project

A modern Spring Boot application for VietBank digital banking services, developed as a final project for VTI (Vietnam Talent Initiative).

## 📋 Project Overview

This project is a comprehensive Spring Boot-based backend application for VietBank's digital platform, implementing modern banking features and best practices.

**Project Details:**
- **Organization:** VTI (Vietnam Talent Initiative)
- **Project Type:** Final Project - DTN 2504
- **Tech Stack:** Spring Boot, Java
- **Language:** 100% Java

## 🚀 Features

- Digital banking services
- RESTful API architecture
- Secure transaction processing
- User authentication and authorization
- Banking operations management

## 🛠️ Technology Stack

- **Language:** Java
- **Framework:** Spring Boot
- **Build Tool:** Maven/Gradle
- **Database:** (Configured in project)
- **Version Control:** Git

## 📝 Prerequisites

Before running this project, ensure you have the following installed:

- Java JDK 11 or higher
- Maven 3.6+ or Gradle 6.0+
- Git
- Your preferred IDE (IntelliJ IDEA, Eclipse, VS Code, etc.)

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/MrBuddhaCoder/vietbank-digital_springboot_VTI_final_project_DTN_2504.git
cd vietbank-digital_springboot_VTI_final_project_DTN_2504
```

### 2. Build the Project

**Using Maven:**
```bash
mvn clean install
```

**Using Gradle:**
```bash
gradle build
```

### 3. Configure Application Properties

Edit `src/main/resources/application.properties` or `application.yml` to set up:
- Database connection
- Server port
- Logging levels
- Other application-specific configurations

### 4. Run the Application

**Using Maven:**
```bash
mvn spring-boot:run
```

**Using Gradle:**
```bash
gradle bootRun
```

The application will start on the configured port (default: 8080).

## 📁 Project Structure

```
vietbank-digital_springboot_VTI_final_project_DTN_2504/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── [Your package structure]
│   │   └── resources/
│   │       ├── application.properties
│   │       └── application.yml
│   └── test/
├── pom.xml (or build.gradle)
└── README.md
```

## 🔧 Configuration

### Application Properties

Configure the application behavior through `application.properties`:

```properties
spring.application.name=vietbank-digital
server.port=8080
server.servlet.context-path=/api
```

### Database Setup

Configure your database connection in application properties or environment variables.

## 🧪 Testing

Run tests using:

**Maven:**
```bash
mvn test
```

**Gradle:**
```bash
gradle test
```

## 📚 API Documentation

API endpoints and documentation can be found in the project documentation or accessed through Swagger/SpringFox if integrated.

## 🔒 Security

- Spring Security integration for authentication and authorization
- Secure password handling
- HTTPS support (configure as needed)
- CSRF protection enabled by default

## 📦 Dependencies

Key dependencies include:
- Spring Boot Web
- Spring Data JPA
- Spring Security
- Database driver (MySQL/PostgreSQL/etc.)
- Other utilities as configured in pom.xml/build.gradle

## 🤝 Contributing

1. Create a new branch: `git checkout -b feature/your-feature`
2. Make your changes and commit: `git commit -m 'Add your message'`
3. Push to the branch: `git push origin feature/your-feature`
4. Submit a pull request

## 📄 License

This project is created as part of VTI's final project program.

## 👨‍💻 Author

**MrBuddhaCoder**

## 📧 Support & Contact

For questions or support regarding this project, please reach out through GitHub issues or contact the project maintainer.

## 🎓 Learning Resources

- [Spring Boot Official Documentation](https://spring.io/projects/spring-boot)
- [Java Documentation](https://docs.oracle.com/javase/)
- [Maven Documentation](https://maven.apache.org/)
- [VTI Program Information](https://www.vti.com.vn/)

## ✅ Checklist for Getting Started

- [ ] Clone the repository
- [ ] Install required dependencies
- [ ] Configure application properties
- [ ] Build the project
- [ ] Run the application
- [ ] Test the endpoints

---

**Last Updated:** 2026-06-16

Happy coding! 🚀
