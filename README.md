# Hospital Management System

## About
Hospital Management System is a web application developed using **Spring Boot**, **MySQL**, **JDBC**, and **Thymeleaf**, deployed on **Tomcat Server**. The system is designed to handle multiple functionalities across different sections, making it efficient and user-friendly.

## Features
- Built using **Spring Boot** for rapid development.
- Uses **MySQL** as the database for storing records.
- **Thymeleaf** for dynamic and interactive web pages.
- Organized into the following modules:
  - **Admin**: Manages users, permissions, and system settings.
  - **Admission**: Handles new user registrations.
  - **Reception**: Manages appointments and inquiries.
  - **Doctor**: Provides medical records and prescriptions.
  - **Pharmacy**: Manages medicines and stock.
  - **Diagnostic**: Handles test results and medical diagnostics.
  - **Billing**: Generates invoices and tracks payments.
  - **Others**: Additional functionalities as required.

## Prerequisites
- **Java 11** or higher
- **Maven** (for dependency management)
- **MySQL Database**
- **Tomcat Server**

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/hospital-management-system.git
   cd hospital-management-system
   ```
2. Configure the MySQL database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/hospital_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
3. Build and run the application:
   ```sh
   mvn spring-boot:run
   ```
4. Access the application in the browser at:
   ```
   http://localhost:8080
   ```

## Technologies Used
- **Spring Boot**
- **MySQL**
- **JDBC**
- **Thymeleaf**
- **Bootstrap & jQuery** (for frontend styling and interaction)
- **Jetty** (for additional utilities)

## License
This project is open-source and available under the [MIT License](LICENSE).

