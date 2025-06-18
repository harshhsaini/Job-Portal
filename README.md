# 🧰 Job Portal Web Application (Spring Boot 3)

A modern, role-based job portal web application built with Spring Boot 3 and Spring MVC. This project enables recruiters to post jobs and job seekers to search and apply for them — all through a secure, responsive, and user-friendly interface. It showcases clean code architecture, MVC patterns, and full CRUD operations backed by a MySQL database.

---

## 🔧 Features

- User registration and login  
- Role-based access (Admin, Recruiter, Job Seeker)  
- Post and apply for jobs  
- View job listings and application status  
- Form validation  
- CRUD operations for jobs and applications  
- MySQL database integration  

---

## 🛠 Tech Stack

- **Backend**: Java 17, Spring Boot 3, Spring MVC  
- **Frontend**: Thymeleaf, HTML/CSS, Bootstrap  
- **Database**: MySQL, Hibernate/JPA  
- **Security**: Spring Security (BCrypt)  

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
```

### 2. Configure the database

Update `src/main/resources/application.properties`:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/job_portal
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update
```

### 3. Run the application
```bash
./mvnw spring-boot:run
```

Then go to: `http://localhost:8080`

---
