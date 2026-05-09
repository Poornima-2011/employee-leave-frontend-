# Employee Leave Management System – Frontend

A modern and responsive frontend application built using **React.js** for managing employee leave requests. This project is designed to work with a **Spring Boot backend API** and **MySQL database**.

---

## 🚀 Features

### 👨‍💼 Employee Features
- Secure Login
- Apply for Leave
- View Leave History
- Track Leave Status (Pending / Approved / Rejected)

### 🧑‍💼 Admin Features
- Admin Login
- View All Leave Requests
- Approve / Reject Leaves
- Dashboard Overview

### 🎨 UI Features
- Responsive Design
- Clean Dashboard Layout
- Material UI / Custom CSS Components
- Professional Login Page

---

## 🛠️ Tech Stack

- React.js
- JavaScript (ES6)
- Axios
- CSS3 / Material UI
- React Hooks

---

## 📁 Project Structure

src/
├── components/
│ ├── Navbar.js
│ ├── Login.js
│ ├── EmployeeDashboard.js
│ ├── AdminDashboard.js
│ ├── ApplyLeave.js
│ └── LeaveHistory.js
│
├── services/
│ └── api.js
│
├── App.js
└── index.js




## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

git clone https://github.com/yourusername/employee-leave-frontend.git
cd employee-leave-frontend

2️⃣ Install Dependencies
npm install

3️⃣ Run Project
npm start

Application runs on
http://localhost:3000

🔗 Backend Connection
Update API URL in:
const BASE_URL = "http://localhost:8084/api";

🔐 Sample Login Credentials
Admin
Username: admin
Password: admin123
Employee
Username: emp1
Password: emp123

📌 Future Enhancements
JWT Authentication
Dark Mode
Leave Analytics Charts
Notifications
Profile Management

👩‍💻 Author
Developed by Poornima P
