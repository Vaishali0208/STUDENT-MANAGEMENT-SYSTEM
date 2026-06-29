# 🎓 Student Management System

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application for managing students, teachers, classes, attendance, exams, and notices through separate admin, teacher, and student portals.

---

## 🚀 Features

### 👨‍💼 Admin
- Admin Login
- Dashboard
- Manage Students
- Manage Teachers
- Manage Classes
- Manage Subjects
- Manage Notices
- View Attendance
- View Marks
- Profile Management

### 👨‍🏫 Teacher
- Teacher Login
- Dashboard
- Mark Student Attendance
- Add Student Marks
- View Student Details
- Manage Profile

### 👨‍🎓 Student
- Student Login
- Dashboard
- View Attendance
- View Exam Results
- View Notices
- Manage Profile

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Material UI (MUI)
- Axios
- React Router DOM

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js

---

## 📁 Project Structure

```
Student-Management-System/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── index.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Vaishali0208/STUDENT-MANAGEMENT-SYSTEM.git
```

Move into project folder

```bash
cd STUDENT-MANAGEMENT-SYSTEM
```

---

## Backend Setup

```bash
cd backend
npm install
```

Create a **.env** file inside the backend folder.

Example:

```env
MONGO_URL=mongodb://127.0.0.1:27017/school
PORT=5000
```

Start Backend

```bash
npm start
```

Server runs at

```
http://localhost:5000
```

---

## Frontend Setup

Open another terminal.

```bash
cd frontend
npm install
```

Run frontend

```bash
npm start
```

or

```bash
npm run dev
```

depending on the project configuration.

---

## Database

MongoDB

Local Database

```
mongodb://127.0.0.1:27017/school
```

or

MongoDB Atlas

```
Replace the connection string in .env
```

---

## Screenshots

Add screenshots here.

### Login

![Login](screenshots/login.png)

### Admin Dashboard

![Dashboard](screenshots/dashboard.png)

### Student Management

![Students](screenshots/students.png)

---

## Future Improvements

- Email Notifications
- Fee Management
- Parent Portal
- Online Assignments
- Timetable Module
- Report Card Generation
- Password Reset
- Dark Mode

---

## Author

**Vaishali B**

GitHub

https://github.com/Vaishali0208

---

## License

This project is developed for educational purposes.
