<h1 align="center">💼 JobHook - Job Portal Application</h1>

<p align="center">
  A modern full-stack job portal with role-based login, job listings, applications, and user profiles.  
  <br/>
  <strong>Spring Boot + React + MongoDB</strong>
</p>

<p align="center">
  <a href="https://lnkd.in/gqXtYJQV" target="_blank"><img src="https://img.shields.io/badge/🔗%20Live%20Demo-Click%20Here-blue?style=for-the-badge"></a>
  <img src="https://img.shields.io/badge/Backend-SpringBoot-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Database-MongoDB-lightgreen?style=for-the-badge">
</p>

---

## 🚀 Overview

**JobHook** is a full-stack job portal application with a **Spring Boot backend** and a **React frontend**.  
It empowers users to:

- 🔍 Search and apply for jobs  
- 🧑‍💼 Post job listings as a recruiter  
- 📝 Manage resumes, skills, experience  
- 🔐 Login with role-based access (Applicant/Recruiter)  

---


## 📁 Project Structure
```
JobHook/
├── backend/ # Spring Boot backend
└── frontend/ # React.js frontend

```

---

## ✨ Key Features

- 🔐 **JWT-based Authentication**
- 🎭 **Role-based Access Control**
- 📢 **Job Posting & Application System**
- 📝 **Dynamic Profile Management**
- 🔔 **Notification System**
- 📱 **Fully Responsive UI (Material UI)**
- 🌐 **RESTful API Integration**

---

## 🛠️ Prerequisites

Before running the project, ensure you have:

- **Java 17+**  
- **Maven 3.6+**  
- **Node.js 16+**, **npm/yarn**  
- **MongoDB** (Local/Cloud)  
- *Optional:* Docker (for containerization)

---

## 🧰 Technologies Used

### 🔧 Backend:
- Spring Boot  
- Spring Security  
- JWT  
- MongoDB  
- Maven  

### 🎨 Frontend:
- React  
- TypeScript  
- Redux Toolkit  
- Material UI  
- Axios  

### 🧱 Others:
- Docker *(optional)*  
- RESTful API Design

---

## ⚙️ Backend Setup

```bash
# 1. Navigate to backend directory
cd backend

# 2. Configure MongoDB connection
# Edit src/main/resources/application.properties or application.yml
spring.data.mongodb.uri=mongodb://localhost:27017/jobhook_db

# 3. Build and run backend
./mvnw clean install
./mvnw spring-boot:run

```
Or run directly from your IDE.

---

💻 Frontend Setup

```
# 1. Navigate to frontend directory
cd ../frontend

# 2. Install dependencies
npm install

# 3. Start the development server
npm start
```

🔗 Now visit: http://localhost:3000

---

🤝 Contribution
Contributions are welcome! 🚀
Feel free to fork the repo, create a branch, and submit a pull request.

📌 For feature requests or bug reports, open an issue.

---

## 📬 Contact

**Created by:** Nitesh Singh  
📧 **Email:** [niteshchauhan1717@gmail.com](mailto:niteshchauhan1717@gmail.com)

