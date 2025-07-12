📝 Blog Website
This is a full-stack blog website where users can sign up, log in, and write blog posts. It has both frontend and backend.

🧠 What It Uses
🛠️ Backend
Node.js + Express

MongoDB (for saving users and blogs)

JWT (for login sessions)

Bcrypt (for password hashing)

🎨 Frontend
React.js

Tailwind CSS

Axios (to talk to backend)

✨ What You Can Do
Create a new account

Log in securely

Write new blog posts

Edit or delete your own blogs

Read all public blogs

🔐 How Login Works
Your password is hashed (secured) using bcrypt

After login, a token is given (JWT)

This token is stored in the browser

It’s sent with every request to access private actions like posting blogs
