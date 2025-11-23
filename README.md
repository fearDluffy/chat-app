# 💬 Full Stack Realtime Chat App  
A modern, beautifully designed **Realtime Chat Application** built with the **MERN Stack**, **Socket.io**, **TailwindCSS**, and **Zustand** — featuring authentication, cloud uploads, online status, and production-ready performance.

<p align="center">
  <img width="1918" height="967" alt="sign-up" src="https://github.com/user-attachments/assets/544274a1-09da-4dcd-ba17-19be94e0df64" />
</p>

---

## 🏷️ Badges

<p align="center">

  <img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-Node.js-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Database-MongoDB-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Realtime-Socket.io-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/github/stars/fearDluffy/chat-app?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/fearDluffy/chat-app?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge" />

</p>

---


## 🚀 Features

- ⚡ **Realtime messaging** using Socket.io  
- 🔐 **JWT auth** (login/signup with secure tokens)  
- 👤 **Live online/offline user status**  
- 🧠 **Global state** using Zustand  
- 🎨 **TailwindCSS + DaisyUI UI**  
- ☁️ **Cloudinary image upload for profile images**  
- 🛡️ **Client + server side validation & error handling**  
- 📦 **Production-ready build process**  
- 🧰 **Clean project structure with reusable components**  

---

## 🌙 Dark Mode Preview  
<p align="center">
  <img width="1900" height="968" alt="themes" src="https://github.com/user-attachments/assets/f1181255-ef8a-407a-b365-af9edf2c5d66" />
<img width="1910" height="962" alt="home" src="https://github.com/user-attachments/assets/9ae32d53-35ea-424e-b579-7b1693fadd40" />
</p>

---

## 📁 Folder Structure

chat-app/
│── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── socket/
│ ├── utils/
│ └── server.js
│
│── frontend/
│ ├── public/
│ ├── src/
│ ├── index.html
│ └── tailwind.config.js
│
│── package.json
│── README.md

yaml
Copy code

---

## ⚙️ Environment Variables

Create a `.env` file inside your **backend** folder:

```env
MONGODB_URI=your_mongo_connection
PORT=5001
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
📦 Installation
Clone the repository
bash
Copy code
git clone https://github.com/your-username/chat-app.git
cd chat-app
🔹 Backend Setup
bash
Copy code
cd backend
npm install
npm run dev
Runs on: http://localhost:5001

🔹 Frontend Setup
bash
Copy code
cd frontend
npm install
npm run dev
Runs on: http://localhost:5173

🏗️ Building the App (Production)
Frontend build
bash
Copy code
npm run build
🚀 Start App in Production
bash
Copy code
npm start
📸 Screenshots
<p align="center"> <img src="frontend/public/screenshot-for-readme.png" width="85%" /> </p>
🤝 Contributing
Pull requests and suggestions are welcome!

⭐ Show Some Love
If this helped, please ⭐ star the repository — it motivates me to build more ❤️

👨‍💻 Author
Ankit Kumar — Full Stack Web Developer
Built with passion, coffee & clean code ☕💛
