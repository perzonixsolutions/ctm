# CTM — Collaborative Task Management System

**CTM (Collaborative Task Management System)** is a full-stack web application that allows users to create, manage, and share tasks with friends for efficient team collaboration.

This project is designed as an **internship training project** to help interns learn real-world full-stack development.

---

## Project Objective

The goal of CTM is to help users:

- ✅ Create and manage personal tasks  
- 🤝 Share tasks with friends  
- 👥 Collaborate on task updates  
- 🔐 Practice secure authentication  
- 📊 Understand multi-user systems  

---

## What Interns Will Learn

By completing this project, interns will gain hands-on experience with:

- Frontend development using React + Vite  
- Backend API development  
- MongoDB database design  
- JWT authentication  
- REST API design  
- Permission & access control  
- Team collaboration workflows  
- Git & GitHub best practices  
- Deployment to production  

---

## Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- Axios
- React Router

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- bcrypt

### Deployment (later stage)
- Frontend: Vercel  
- Backend: Render / Railway  
- Database: MongoDB Atlas  

---

## Core Features (MVP)

### 👤 Authentication
- User signup  
- User login  
- JWT-based authentication  
- Protected routes  

---

### Task Management

Users can:

- Create tasks  
- Edit tasks  
- Delete tasks  
- Mark tasks as complete  
- Set due dates  

---

### 🤝 Task Sharing (Key Feature)

Users can:

- Share tasks with friends  
- View tasks shared with them  
- Collaboratively update task status  

---

## 🔐 Permission Rules (IMPORTANT)

### Task Owner Can:
- Edit task  
- Delete task  
- Share task  
- Update status  

### Shared User Can:
- View task  
- Update status  

### Shared User Cannot:
- Delete task  
- Change owner  

---

## 🗄️ Database Schema Overview

### User

```json
{
  "_id": "...",
  "name": "string",
  "email": "string",
  "password": "hashed",
  "friends": ["userId"]
}
