# 🔐 User Authentication System
## 📌 Description
This project is a **secure user authentication system** built using **Node.js**, designed to demonstrate modern web security practices including password encryption, JWT-based session management, and protected routing.
> ⚙️ This is an advanced-level cybersecurity project suitable for portfolios, demonstrations, and learning secure web development.
---
## 🚀 Features
* User **Registration** & **Login**
* **Password encryption** using crypto
* **JWT Token** generation and verification
* Middleware for **Protected Routes**
* Modular **Controllers**, **Routes**, and **Models**
* MongoDB-ready user model
* Basic error handling and session checks
---
## 🛠️ Tech Stack

| Layer    | Technology          |
| -------- | ------------------- |
| Backend  | Node.js, Express.js |
| Security | JWT, Crypto         |
| Database | MongoDB (Mongoose)  |
| Auth     | Token-based (JWT)   |
---
## 📂 Folder Structure
```
User-Authentication-System/
├── app.js                   # Entry point
├── authenticate.js          # JWT Middleware
├── encryption.js            # Password encryption logic
├── controllers/
│   ├── loggedin.js
│   └── user.js
├── models/
│   └── user.js              # User schema
├── routes/
│   ├── protected.js
│   └── user.js
├── package.json
└── .env                     # Environment secrets (Not included)
```

## 🧪 Setup & Run
### 🔧 Prerequisites
* Node.js & npm installed
* MongoDB (local or Atlas)
* Create a `.env` file with:
  ```env
  JWT_SECRET=your_jwt_secret_key
### ▶️ Run the Project

```bash
npm install
node app.js
## 📬 API Endpoints

| Method | Route        | Description                           |
| ------ | ------------ | ------------------------------------- |
| POST   | `/register`  | Register a new user                   |
| POST   | `/login`     | Log in with JWT                       |
| GET    | `/protected` | Access protected route (JWT required) |
