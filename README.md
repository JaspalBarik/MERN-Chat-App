# ⚡ QuickChat — MERN Real-Time Chat Application

*A full-featured, modern, real-time messaging app built with the MERN stack.*

QuickChat is a powerful messaging application with smooth real-time chat functionality, image messaging, online status tracking, read receipts, profile editing, and a modern responsive UI — all powered by **MongoDB, Express, React (Vite), Node, and Socket.io**.

---

## 🖼️ Screenshots

*Stored inside `/screenshots/` folder.*

### 🏠 Main Page

![Main Page](./screenshots/main_page.png)

### 🔐 Login Page

![Login Page](./screenshots/login_page.png)

### 🏡 Home Page

![Home Page](./screenshots/home_page.png)

### 💬 Chat Section

![Chat Section](./screenshots/chat-section_page.png)

### ✉️ Chat Area

![Chat Area](./screenshots/chat-area_page.png)

### 📝 Edit Profile

![Edit Profile](./screenshots/edit-profile_page.png)

---

## 🚀 Core Features

### 💬 Real-Time Chat

* Bi-directional real-time messaging using **Socket.io**
* Supports both **text** and **image messages**
* Smooth and instant updates on both sender & receiver sides

### 👀 Message Delivery Tracking

* **Seen / Unseen indicators**
* **Unread message count** for each chat
* Automatic real-time update when user opens chat

### 🟢 Online Status

* Real-time **online / offline presence**
* Shows last-seen state when a user disconnects

### 🖼️ Media & Chat Data

* Users can send **images in chat**
* Dedicated **Media section** for viewing shared images

### 👤 User Profile Management

* Edit **Full Name**
* Edit **Bio**
* Upload / change **Profile Picture**
* All updates reflected instantly across the app

### 🔐 Authentication

* User signup (name, email, password)
* Secure login (email + password)
* Protected routes using JWT
* Logout functionality

### 📱 Responsive UI

* Fully responsive for mobile, tablet & desktop
* Smooth, clean, modern UX

---

## 🛠️ Tech Stack

### **Frontend**

* React 19 + Vite
* Context API
* React Router
* TailwindCSS
* Socket.io Client
* Axios

### **Backend**

* Node.js
* Express.js
* MongoDB + Mongoose
* Socket.io (real-time layer)
* JWT + bcrypt
* Cloudinary for media

---

## 📦 Project Structure

```
mern-chat-app/
│
├── client/                 # React frontend
│   └── src/
│
├── server/                 # Node backend
│   └── controllers/
│   └── models/
│   └── routes/
│   └── socket/
│
├── screenshots/            # App images used in README
│   ├── main_page.png
│   ├── login_page.png
│   ├── home_page.png
│   ├── chat-section_page.png
│   ├── chat-area_page.png
│   └── edit-profile_page.png
│
└── README.md
```

---

## 🔧 Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/mern-chat-app.git
cd mern-chat-app
```

---

## 🧩 Backend Setup

```bash
cd server
npm install
npm run server
```

### Create `.env` inside `/server`

```
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
PORT=5000
```

---

## 🎨 Frontend Setup

```bash
cd client
npm install
npm run dev
```

### Add `.env` in `/client`

```
VITE_SERVER_URL=http://localhost:5000
```

---

## 🚀 Deployment Guide

### **Frontend → Vercel**

* Import Git repo
* Select `client/`
* Add env: `VITE_SERVER_URL`

### **Backend → Render**

* Select `server/`
* Add env vars:

  * `MONGODB_URI`
  * `JWT_SECRET`
  * `CLOUDINARY_*`
  * `PORT=5000`

Set CORS origin to Vercel frontend URL.

---

## 🤝 Author

**Jaspal Barik**
*MERN Stack Developer*

GitHub: **your-username**

---

## ⭐ Star the Repo

If you liked QuickChat, drop a ⭐ to support the project!

Happy coding ⚡🔥💻
