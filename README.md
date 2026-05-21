# PEP-21-MAY-2026
# Karya - MERN Stack Project Management Application

## 👨‍🎓 Student Details

- Name: Lovesh Roy
- Roll Number: YOUR_ROLL_NUMBER

---

# 📌 Project Description

Karya is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) project management and task tracking application.

The application allows users to:

- Manage projects
- Create and update tasks
- Use Kanban board functionality
- Manage teams
- Authenticate securely using JWT
- Track project workflow efficiently

The project is containerized using Docker and deployed on cloud platforms.

---

# 🛠️ Technologies Used

## Frontend
- React.js
- Vite
- CSS

## Backend
- Node.js
- Express.js

## Database
- MongoDB Atlas

## DevOps & Deployment
- Docker
- Docker Compose
- Render
- GitHub

---

# 📂 Project Structure

```bash
KARYA/
│
├── backend/
│   ├── config/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── Dockerfile
│   └── server.js
│
├── src/
├── public/
├── Dockerfile
├── docker-compose.yml
├── package.json
└── README.md
```

# Environment Variables
Backend .env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NODE_ENV=development
CORS_ORIGIN=http://localhost:5173
# Steps to Run Locally
1️⃣ Clone Repository
git clone https://github.com/loveshroy67/karya-mern.git
cd karya-mern
2️⃣ Install Frontend Dependencies
npm install
3️⃣ Install Backend Dependencies
cd backend
npm install
4️⃣ Start Backend Server
npm start

Backend runs on:

http://localhost:5000
5️⃣ Start Frontend

Open another terminal:

npm run dev

Frontend runs on:

http://localhost:5173
# Docker Commands Used
Build Docker Containers
docker-compose build
Run Docker Containers
docker-compose up
Run Containers in Detached Mode
docker-compose up -d
Stop Containers
docker-compose down
View Running Containers
docker ps

# Deployment Information
GitHub Repository Link

https://github.com/loveshroy67/karya-mern

Deployed Backend URL (Render)

https://karya-mern.onrender.com

# Architecture Explanation
Frontend (React + Vite)
        ↓
Docker Container
        ↓
Backend (Node.js + Express.js)
        ↓
MongoDB Atlas Database
Application Workflow
User interacts with the React frontend.
Frontend sends API requests to Express backend.
Backend processes requests and communicates with MongoDB Atlas.
Database sends response back to backend.
Backend sends JSON response to frontend.
Docker containers manage frontend and backend services.

# Features

✅ JWT Authentication
✅ Project Management
✅ Task Management
✅ Kanban Board
✅ Team Collaboration
✅ User Management
✅ MongoDB Atlas Integration
✅ Dockerized Application
✅ Cloud Deployment

# Screenshots
Running Docker Containers

Add screenshot of:

docker ps
<img width="680" height="92" alt="Docker ps" src="https://github.com/user-attachments/assets/5a47b2ca-f52e-4dd9-828f-0f98df8bfbe6" />



Add screenshots of:

Frontend running
<img width="1280" height="800" alt="Frontend running" src="https://github.com/user-attachments/assets/20fdca18-1f34-422f-8348-430a6287a30e" />


Backend API running
<img width="1070" height="299" alt="Backend running" src="https://github.com/user-attachments/assets/82e94a18-2ba1-44a3-a958-bdb25ee10758" />


MongoDB connection
<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/c0877310-413e-45bf-b220-59b5b700d782" />

Docker Desktop containers
<img width="1280" height="800" alt="Docker containers" src="https://github.com/user-attachments/assets/87982001-cc40-485d-9ee3-7c88284b4607" />

Render deployed backend
<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/a405fd78-f615-4a65-879e-ef5b44fd2b59" />


# API Health Check

Endpoint:

GET /health

Response:

{
  "status": "Backend is running"
}

# Dockerized Services
Backend Container
Node.js
Express.js
MongoDB Connection
Frontend Container
React.js
Vite
Nginx

# Author
Lovesh Roy
