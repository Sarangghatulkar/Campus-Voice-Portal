# 🎓 Campus Voice Portal


### Advanced Grievance & Complaint Management System
Campus Voice is a full-stack web application designed to simplify college grievance management. It enables students to submit complaints, track their status, provide feedback, and access academic review workflows. Faculty members and administrators can manage complaints through role-based dashboards and a structured escalation system.


## 📸 Application Screenshots

### Login Page
Login Page <img width="1600" height="819" alt="login_page" src="https://github.com/user-attachments/assets/a3eb43b0-1288-477c-8572-2432abae9588" />


### Student Dashboard
<img width="1600" height="803" alt="complaint" src="https://github.com/user-attachments/assets/b5c0126b-3ba3-425c-86d4-7731bf9e237d" />



### Feedback Assign
<img width="1600" height="811" alt="feedback section" src="https://github.com/user-attachments/assets/b7fb9473-7f3e-4b53-863d-55f58d1077b8" />

<img width="1600" height="810" alt="feedback assign section" src="https://github.com/user-attachments/assets/ceb9a6b8-31e0-4911-befc-83c48efaef08" />



### Admin Dashboard
<img width="1600" height="817" alt="admin dashboard" src="https://github.com/user-attachments/assets/dcf12c0f-b7fc-46fb-9374-03ff1eef1b44" />


## 🎯 Problem Statement

Traditional college complaint systems can make it difficult for students to submit grievances, track progress, and know whether their issues have been resolved.

Campus Voice provides a centralized digital platform for complaint submission, tracking, escalation, and administrative management.

## ✨ Key Features

- **Role-Based Access Control:** Separate access for students, teachers, TGs, class in-charges, HODs, and administrators.
- **Complaint Management:** Submit complaints and track their status.
- **Automated Escalation:** Four-tier complaint escalation workflow with SLA-based handling.
- **Real-Time Notifications:** Socket.IO-based notifications for supported application events.
- **AI-Based Complaint Assistance:** Complaint triaging and duplicate detection.
- **Analytics Dashboard:** Visual insights and complaint statistics using Recharts.
- **Anonymous Feedback:** Feedback submission functionality.
- **Academic Review Workflow:** Academic re-evaluation requests and scanned-copy uploads.
- **Audit Trail:** Records of complaint-related activities for improved traceability.

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| Frontend | React 18, Vite |
| Styling | Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Authentication | JWT, bcrypt |
| Real-Time Communication | Socket.IO |
| File Uploads | Multer |
| Scheduled Tasks | Node-Cron |
| Data Visualization | Recharts |
| Forms | React Hook Form |
| Icons | Lucide Icons |

## 🏗️ Application Architecture

```text
Campus Voice Portal
        |
        v
 React Frontend (Vite)
        |
        v
 Express.js REST API
        |
        +------> JWT Authentication
        |
        +------> Complaint Management
        |
        +------> Escalation & Notifications
        |
        +------> AI Complaint Processing
        |
        v
 MongoDB Database
```

## 🚀 Getting Started

### Prerequisites

Install the following before running the project:

- Node.js and npm
- MongoDB Atlas account or a local MongoDB installation
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/Sarangghatulkar/Campus-Voice-Portal.git
cd Campus-Voice-Portal
```

### 2. Configure the Backend

```bash
cd backend
npm install
```

Configure the required environment variables using the project's `.env.example` file. Add your own database connection string, authentication secrets, and any other configuration required by the backend.

Do not upload your actual `.env` file or API keys to GitHub.

Start the backend using the development command configured in `backend/package.json`. If its script is `dev`, run:

```bash
npm run dev
```

### 3. Configure the Frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL printed by Vite in your terminal.

> **Note:** The backend environment variables and frontend API URL must match your project's actual configuration. Refer to `.env.example` and the project source code for the required settings.

## 📁 Project Structure

```text
Campus-Voice-Portal/
├── backend/
├── frontend/
├── .env.example
├── .gitignore
├── package.json
├── README.md
├── vite.config.ts
└── screenshots/
    ├── login.png
    ├── student-dashboard.png
    └── admin-dashboard.png
```

The `screenshots/` folder is where you should add your real application screenshots.

## 🔐 Security

- Role-based access control for different user types.
- JWT-based authentication.
- Password hashing using bcrypt.
- Environment variables for sensitive configuration.
- File upload handling through Multer.

Security features should be verified against the actual application configuration before deploying to production.

## 🔮 Future Improvements

- Improve mobile responsiveness and accessibility.
- Expand complaint analytics and reporting.
- Add more automated notifications and status updates.
- Enhance AI-based complaint classification.
- Improve deployment, monitoring, and automated testing.

## 👨‍💻 Project Information

**Project Name:** Campus Voice Portal  
**Category:** Full-Stack Web Development  
**Domain:** Education Technology

**Repository:** [Campus Voice Portal on GitHub](https://github.com/Sarangghatulkar/Campus-Voice-Portal)

## 📄 License

Add a suitable open-source license if you intend to distribute this project under specific reuse permissions. Without a license, standard copyright restrictions generally apply.

---

*Built to make campus grievance management more transparent, organized, and accessible.*
