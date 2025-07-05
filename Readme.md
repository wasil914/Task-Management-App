# 📋 Task Management App

A full-stack Task Management web application that helps users efficiently create, update, and manage daily tasks with a clean UI and RESTful APIs.


## 📸 Demo

> [🚀 Live Demo](https://task-management-app-one-taupe.vercel.app)  
> 🛠️ Backend Hosted on [Render](https://task-management-app-bs5l.onrender.com)

[App Screenshot]([Task Manager](https://github.com/wasil914/Task-Management-App/blob/2331a8f0a5c60aa8ad884f43bcc70d4357b07b2b/liveapp.png)



## 🧠 Features

- 📝 Create, update, delete tasks
- ✅ Mark tasks as completed
- 📅 Organize by date and status
- 🌐 Responsive UI
- 🔐 Secure API endpoints
- 📦 Backend + Frontend fully separated


## 🛠️ Tech Stack

**Frontend**  
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel)

**Backend**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render)


## 📂 Folder Structure
Task-Management-App/
├── client/ # React frontend
│ └── src/
│ ├── components/
│ ├── pages/
│ └── App.jsx
├── server/ # Node.js backend
│ ├── controllers/
│ ├── models/
│ └── routes/
├── .env
└── README.md

## ⚙️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/wasil914/Task-Management-App.git

# FRONTEND
cd client
npm install
npm run dev

# BACKEND
cd ../server
npm install
npm run dev

Make sure you have a .env file in server/ with:


MONGO_URI=your_mongodb_uri
PORT=5000

📈 Roadmap
 Task CRUD APIs

 React UI with Tailwind

 Hosted frontend/backend

 Add user authentication 🔐

 Add due dates and reminders ⏰

 Add drag-and-drop UI 🎯

