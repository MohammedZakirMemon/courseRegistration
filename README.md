# 🎓 CampusFlow – Smart Course Management Platform

CampusFlow is a full-stack course enrollment platform designed to streamline student-instructor interactions, enhance scheduling efficiency, and support data-informed academic planning through scalable infrastructure and real-time insights.

## 🚀 Key Features

- 🔐 **Secure Authentication** – User login & registration with JWT-based session management  
- 📚 **Course Discovery** – Search and filter courses with real-time updates on availability, timing, and instructor info  
- 🗓️ **Personal Schedule Manager** – Add or drop courses with automatic conflict checks and live seat tracking  
- 📈 **Enrollment Analytics** – Track enrollment trends and student engagement via admin dashboards (planned)  
- 📢 **Event Notifications** – Receive alerts on registration deadlines, course waitlists, and system-wide updates (planned)

## 🧠 Tech Stack

| Layer          | Technology                         |
|----------------|------------------------------------|
| Frontend       | **React**, Vite, JavaScript, HTML, CSS |
| Backend        | **Java**, Spring Boot              |
| Authentication | JWT (JSON Web Tokens)              |
| Database       | **MongoDB**                        |
| Deployment     | Run locally via terminal or deploy on any cloud stack |

## 🔧 Architecture Overview

- **Frontend** served via Vite for optimized dev experience and fast HMR
- **Backend** REST APIs built with Spring Boot (`CourseRegistrationMain.java`) for modular service separation
- **JWT tokens** securely handle session management across routes
- **MongoDB schema** models users, courses, and enrollment records for dynamic retrieval

## 🧭 Getting Started

### 🖥️ Frontend
```bash
cd frontend/
npm install
npm run dev
```

### ☕ Backend
Open the project in your IDE and run:
```java
CourseRegistrationMain.java
```

Ensure both services are running in parallel.

## 📹 Demo Video

▶️ [Watch the live walkthrough](https://drive.google.com/file/d/1AfeaZwWEJWxWGNoTrtQcB7CuJmRClXtC/view)

## 📌 Future Enhancements

- ⏰ Course drop logic with deadline constraints and approval workflows  
- 📬 Email/SMS notifications for registration, waitlists, and drop confirmations  
- 📊 Data dashboards for faculty to assess course popularity and forecast demand  
- 📅 Timetable optimization and clash detection for students during enrollment

## 👨‍💻 Author

**Mohammed Zakir Memon**  
> Full-stack engineer with focus on scalable backend systems and React-based UI.  
> Reach out for collaboration or deployment consulting.
