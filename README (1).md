# 🎥 YouTube Clone (MERN Stack Capstone Project)

A full-stack YouTube Clone built using the MERN stack. This project allows users to browse, watch, upload, and interact with videos — just like YouTube!

## 🚀 Features

### Frontend (React)
- 🏠 **Home Page**: Grid of video thumbnails with title, views, and channel
- 🔐 **User Authentication**: Register/Login with JWT-based sessions
- 🎞 **Video Player Page**: Watch videos with title, description, and channel info
- 💬 **Comment Section**: View and add comments to videos
- 📺 **Channel Page**: Shows channel info and its uploaded videos
- 🔍 **Search & Filter (Planned)**: Search videos by title, filter by category
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile

### Backend (Node.js + Express + MongoDB)
- 🔐 JWT authentication & secure user sessions
- 📦 REST APIs for users, videos, comments, and channels
- 🧠 MongoDB for storing video metadata, users, comments, channels
- 🗂 CRUD operations for videos and comments

---

## 🧑‍💻 Tech Stack

- **Frontend**: React, Axios, React Router
- **Backend**: Node.js, Express.js, MongoDB (Mongoose)
- **Authentication**: JWT (JSON Web Tokens)
- **Database**: MongoDB (Atlas/local)
- **Version Control**: Git & GitHub

---

## 📁 Folder Structure

```
youtube-clone/
├── client/           # React frontend
│   └── src/
│       ├── pages/
│       ├── App.jsx
│       └── index.js
├── server/           # Node + Express backend
│   ├── models/
│   ├── routes/
│   └── server.js
```

---

## 🛠 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/youtube-clone.git
cd youtube-clone
```

### 2. Backend Setup

```bash
cd server
npm install
touch .env
```

Create a `.env` file in `/server`:

```env
MONGO_URI=mongodb://localhost:27017/youtube-clone
JWT_SECRET=your_jwt_secret
PORT=5000
```

Run the backend:

```bash
npm start
```

### 3. Frontend Setup

```bash
cd ../client
npm install
npm start
```

Make sure frontend proxy is set to `http://localhost:5000` in `package.json` if needed.

---

## 🔍 Sample Credentials

Register a user via `/register`, then login via `/login`. Example:

```json
{
  "username": "john",
  "email": "john@example.com",
  "password": "123456"
}
```

---

## 📹 Demo Video

🎬 [Demo Video Link Here](#)  
> Replace this with your uploaded YouTube/Drive demo link

---

## 📜 License

This project is part of the **MERN Stack Capstone Assignment** and is intended for educational purposes.

---

## 📧 Contact

For issues or contributions, feel free to open an issue or PR on GitHub.
