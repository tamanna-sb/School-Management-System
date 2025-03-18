# School Management System

## Overview
The **School Management System** is a full-stack web application designed to manage school operations efficiently. It enables administrators, teachers, and students to interact seamlessly through an intuitive interface, supporting essential functions such as student records, attendance tracking, grading, and feedback management.

## Features
### Authentication & Authorization
- User roles: **Admin, Teacher, Student**
- Secure Sign-up & Sign-in (JWT-based authentication)

### Student & Teacher Management
- Admin can **add, delete, update** students & teachers
- Assign students to classes & subjects

### Attendance & Grading
- Teachers can **mark attendance** for students
- Add and track **grades & marks** for each student

### Scheduling & Subjects
- Manage **class schedules & subjects**
- Assign teachers to specific subjects

### Feedback System
- Teachers can provide **performance feedback** to students
- Students can submit **queries & feedback**

## Tech Stack
### Frontend:
- **React, Redux** (UI components & state management)
- **JavaScript** (ES6+)
- **CSS/Bootstrap** (Styling & responsiveness)

### Backend:
- **Node.js** (REST API)
- **MongoDB** (NoSQL database for storing records)


## Installation
### Prerequisites:
- Node.js installed
- MongoDB installed & running

### Steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/school-management-system.git
   cd school-management-system
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the backend server:
   ```sh
   npm run server
   ```
4. Start the frontend:
   ```sh
   npm start
   ```
5. Open the app in the browser at `http://localhost:3000`

## Contributing
Contributions are welcome! Fork the repo and submit a pull request.

## License
This project is licensed under the **MIT License**.

