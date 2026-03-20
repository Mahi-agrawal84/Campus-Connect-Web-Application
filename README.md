# 🌐 CampusConnect Web Application

CampusConnect is a full-stack web application designed for Students, HR, and Admin to manage campus activities including internships, placements, notes, notices, profiles, and events.

👩‍💻 **My Contribution:** Developed and designed the complete **Frontend (React.js)** of the application, focusing on responsive UI, user experience, and role-based dashboards.

🔗 Live Links  
Frontend: https://campusconnect-web.vercel.app  
Backend API: https://campusconnect-backend-3s6m.onrender.com  

---

## 🚀 Features

### 👩‍🎓 Student
- View internships  
- Apply for internships  
- View notes, notices, and events  
- Access personalized dashboard  
- View placements  
- Update profile (except name & role)  

### 👩‍💼 HR
- Add internships & placements  
- Manage internship data  
- View student applications  

### 🛠️ Admin
- Full control panel  
- Add/Edit/Delete:
  - Internships  
  - Placements  
  - Notes  
  - Users  
  - Events  
- Manage entire application data  

---

## 🧩 Tech Stack

### **Frontend (My Contribution)**
- React.js  
- HTML, CSS, JavaScript  
- React Router  
- AOS.js (Animations)  

### **Backend**
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JSON Web Token (JWT)  

---

## 💡 Frontend Highlights (Developed by Me)

- Designed responsive UI for mobile and desktop  
- Implemented role-based dashboards (Student / HR / Admin)  
- Integrated REST APIs with backend services  
- Created reusable components and structured UI  
- Added animations using AOS for enhanced UX  
- Managed routing using React Router  

---

## 📁 Folder Structure

campusconnect-react/ → Frontend (Developed by Me)  
campusconnect-backend/ → Backend  

---

## ⚙️ Installation & Setup

### 🖥️ Clone Repository
```bash
git clone https://github.com/Mahi-agrawal84/Campus-Connect-Web-Application.git

🎨 Frontend Setup
cd campusconnect-react
npm install
npm start


🛠️ Backend Setup
cd campusconnect-backend
npm install
node server.js


🔐 Authentication (JWT)

Login & Register with role-based access

Secret keys for Admin & HR

Students have normal registration flow


🎯 Role-Based Access Control

| Feature           | Student | HR | Admin |
| ----------------- | ------- | -- | ----- |
| View Internships  | ✔       | ✔  | ✔     |
| Apply Internship  | ✔       | ✖  | ✖     |
| Add Internship    | ✖       | ✔  | ✔     |
| Edit Internship   | ✖       | ✖  | ✔     |
| Delete Internship | ✖       | ✖  | ✔     |
| Notes Upload      | ✔       | ✔  | ✔     |
| Notes Delete      | ✖       | ✖  | ✔     |


📸 UI Overview

Modern responsive UI

Clean layout with animations

Dashboard-based navigation for each role


⭐ Show Your Support

If you like this project, please ⭐ the repository!
