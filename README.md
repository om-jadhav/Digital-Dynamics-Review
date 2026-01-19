# 📝 Digital Dynamics Review

**Digital Dynamics Review** is a full-stack blog platform built to demonstrate practical backend development, secure authentication, and database-driven content management using modern web technologies. The project focuses on clean architecture, scalability, and real-world development practices rather than heavy UI design.

---

## 🚀 Project Overview

Digital Dynamics Review allows users to register, authenticate securely, and publish blog posts with media support. The application follows the **MVC (Model–View–Controller)** architecture, ensuring clear separation of concerns, maintainability, and structured code organization.

This project highlights strong backend fundamentals including authentication workflows, database integration, and server-side rendering using EJS.

---

## 🎯 Key Objectives

- Build a secure and scalable backend application
- Implement JWT-based authentication using cookies
- Perform full CRUD operations on blog content
- Integrate MongoDB using Mongoose ODM
- Follow MVC architecture for clean code structure
- Support media uploads in a structured manner
- Apply environment-based configuration and security best practices

---

## 🛠️ Technology Stack

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Cookie-Parser
- dotenv

### Frontend
- EJS (Server-Side Rendering)
- HTML5
- CSS3

### Tools & Utilities
- Nodemon
- MongoDB Shell (mongosh)
- Git & GitHub
- Visual Studio Code

---

## ✨ Core Features

- Secure user authentication using JWT and HTTP cookies
- Create, read, update, and manage blog posts
- Persistent data storage with MongoDB
- MVC-based backend architecture
- Media upload support via `public/uploads`
- Environment variable–based configuration
- Centralized middleware and error handling
- Dynamic server-side rendering with EJS

---

## 📂 Project Structure

Digital-Dynamics-Review/
│
├── models/ # Database schemas
│ ├── blog.js
│ └── user.js
│
├── routes/ # Application routes
│ ├── blog.js
│ └── user.js
│
├── middlewares/ # Authentication middleware
│ └── authentication.js
│
├── views/ # EJS templates
│ ├── home.ejs
│ ├── login.ejs
│ ├── register.ejs
│ └── addBlog.ejs
│
├── public/
│ ├── css/
│ └── uploads/ # Uploaded blog images/media
│
├── .env
├── app.js
├── package.json
└── README.md


---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository
git clone https://github.com/your-username/digital-dynamics-review.git
### 2️⃣ Install Dependencies
npm install

### 3️⃣ Configure Environment Variables

Create a .env file in the root directory:

PORT=7000
MONGO_URL=mongodb://127.0.0.1:27017/blogDB
JWT_SECRET=your_secret_key

### 4️⃣ Run the Application
npm run dev

### 5️⃣ Open in Browser
http://localhost:7000

## 📈 What This Project Demonstrates

- Backend API development using Express.js
- Secure authentication and authorization workflows
- MongoDB schema design with Mongoose
- Server-side rendering using EJS templates
- Middleware-based request handling
- File upload and static asset management
- Real-world debugging and configuration handling

## 🧠 Skills Highlighted

- Backend Development
- RESTful Architecture
- Authentication & Security
- Database Design
- MVC Pattern
- Node.js Ecosystem
- Version Control with Git

## 👤 Author

Om Jayasing Jadhav
