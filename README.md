# 📝 Blog Website

A full-stack blog website where users can **sign up**, **log in**, and **write blog posts**. Built with a modern tech stack for both frontend and backend.

---

## 💻 Tech Stack

### 🧠 Backend

- ⚙️ **Node.js + Express.js**
- 🗃️ **MongoDB** (for storing users and blogs)
- 🔐 **JWT** (for login sessions)
- 🧂 **Bcrypt** (for salted password hashing)

### 🎨 Frontend

- ⚛️ **React.js**
- 💅 **Tailwind CSS**
- 🔄 **Axios** (for API requests)

---

## ✨ Features

- ✅ User Sign Up & Log In
- 🔐 Passwords are hashed using bcrypt with salt
- 🔑 JWT tokens for secure authentication
- ✍️ Create, Edit, and Delete blog posts
- 🌍 Public feed to view all blogs
- 🧼 Clean and minimal UI with Tailwind

## 🔑 Auth Flow

1. User signs up with email and password.
2. Password is hashed with bcrypt and stored.
3. On login, server returns a signed JWT.
4. Client stores the JWT and sends it in headers (`Authorization: Bearer <token>`) for protected routes.

   ## 🧑‍💻 Author

Built with ❤️ by Dhiraj Barnwal
