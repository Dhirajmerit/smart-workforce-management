# 🎓 Smart Campus Feedback System

A full-stack web application developed to streamline the student feedback process within educational institutions. The system enables students to submit anonymous feedback while allowing administrators and faculty to analyze responses through a centralized dashboard.

---

## 📌 Overview

The Smart Campus Feedback System digitizes the traditional feedback collection process by providing a secure, centralized, and user-friendly platform. It improves transparency, simplifies data management, and helps institutions make data-driven decisions based on student feedback.

---

## ✨ Features

### 👨‍🎓 Student Module
- Secure Login & Registration
- Submit Course Feedback
- Anonymous Feedback Submission
- View Submission Status
- User-Friendly Dashboard

### 👨‍🏫 Faculty Module
- View Feedback Summary
- Department-wise Analytics
- Performance Insights

### 👨‍💼 Admin Module
- Manage Students & Faculty
- Manage Courses & Departments
- Generate Feedback Reports
- Dashboard with Analytics
- Secure Role-Based Authentication

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- Spring Boot
- Spring Security
- REST APIs

### Database
- MySQL

### Tools
- Git
- GitHub
- IntelliJ IDEA
- VS Code
- Postman

---

## 📂 Project Structure

```
Smart-Campus-Feedback-System
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── application.properties
│
├── database/
│   └── schema.sql
│
├── screenshots/
│
├── README.md
│
└── .gitignore
```

---

## 🗄️ Database

Database: **MySQL**

Main Tables:

- Student
- Faculty
- Admin
- Department
- Course
- Feedback
- User Roles

---

## 🔐 Authentication

The application implements secure authentication using Spring Security with role-based access control.

Available Roles:

- Admin
- Faculty
- Student

Each role has access only to the features assigned to it.

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/Dhirajmerit/Smart-Campus-Feedback-System.git
```

### Backend

```bash
cd backend
```

Configure MySQL in

```
application.properties
```

Run

```bash
mvn spring-boot:run
```

---

### Frontend

```bash
cd frontend
```

Install dependencies

```bash
npm install
```

Run

```bash
npm start
```

Application will open at

```
http://localhost:3000
```

---

## 📊 System Workflow

```
Student Login
        │
        ▼
Submit Feedback
        │
        ▼
Spring Boot REST API
        │
        ▼
MySQL Database
        │
        ▼
Admin Dashboard
        │
        ▼
Reports & Analytics
```

---

## 📷 Screenshots

> Add screenshots in the `screenshots` folder.

Suggested screenshots:

- Login Page
- Student Dashboard
- Feedback Form
- Faculty Dashboard
- Admin Dashboard
- Analytics Page

---

## 📈 Future Enhancements

- Email Notifications
- AI-Based Sentiment Analysis
- Mobile Responsive Design
- PDF Report Generation
- Charts & Data Visualization
- Export Reports to Excel
- Multi-Institution Support

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Full Stack Web Development
- REST API Development
- Spring Boot
- React.js
- MySQL Database Design
- Authentication & Authorization
- Git & GitHub
- Software Architecture
- CRUD Operations

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Dhiraj Yogesh Patil**

B.Tech Computer Science Engineering  
VIT Bhopal University

📧 Email: dhiraj.patil207@gmail.com

🔗 LinkedIn: https://linkedin.com/in/dhiraj-patil-234169320

💻 GitHub: https://github.com/Dhirajmerit

---

⭐ If you found this project helpful, please consider giving it a star!
