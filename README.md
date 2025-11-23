# 🚀 React User Backend API

This is the **backend server** for a React-based user management application.  
It allows you to **fetch, create, update, and delete users** through RESTful API endpoints.

🌐 **Live API:** [https://react-user-backend.vercel.app/users](https://react-user-backend.vercel.app/users)

---

## 🧩 Features

✅ Fetch all users   
➕ Add new users  
✏️ Update user details  
❌ Delete users  
⚙️ Simple REST API built using **Node.js + Express.js**  
🌍 Hosted live on **Vercel**

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| **Node.js** | JavaScript runtime for backend |
| **Express.js** | Web framework for handling routes |
| **CORS** | Middleware for cross-origin requests |
| **Body-parser** | Middleware for parsing request data |
| **Vercel** | Deployment & hosting platform |

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| `GET` | `/users` | Fetch all users |
| `GET` | `/users/:id` | Fetch single user by ID |
| `POST` | `/users` | Create a new user |
| `PUT` | `/users/:id` | Update an existing user |
| `DELETE` | `/users/:id` | Delete a user |

---

## ⚙️ Local Setup Guide

Follow these steps to run the project locally 👇

```bash
# 1️⃣ Clone the repository
git clone https://github.com/BilalUsman1291/react-user-backend.git

# 2️⃣ Go into project directory
cd react-user-backend

# 3️⃣ Install dependencies
npm install

# 4️⃣ Run the server
npm start
