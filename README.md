# 💬 Full Stack Realtime Chat Application

A modern, production-ready **Realtime Chat App** built using the **MERN stack**, **Socket.io**, and sleek styling with **TailwindCSS + Daisy UI**.

---

![Demo App](/frontend/public/screenshot-for-readme.png)

## 🚀 Features

- ⚡ **Real-time Messaging** using [Socket.io](w)  
- 🔒 **JWT Authentication & Authorization**  
- 🧑‍💻 **Online User Presence Detection**  
- 💾 **MongoDB** for robust data storage  
- 🌐 **Zustand** for global state management  
- 🎨 **TailwindCSS** + **Daisy UI** for a beautiful, responsive UI  
- ☁️ **Cloudinary** integration for image uploads  
- 🧰 Comprehensive **Error Handling** on both client & server  
- 🌍 Ready for **Free Deployment** (Render, Vercel, etc.)

---

## 📁 Tech Stack

- **Frontend**: [React](w), [Tailwind CSS](w), [Daisy UI](w), Zustand  
- **Backend**: [Node.js](w), [Express](w), [MongoDB](w), [Socket.io](w)  
- **Cloud**: [Cloudinary](w)  
- **Authentication**: [JWT](w)

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/realtime-chat-app.git
cd realtime-chat-app
```

### 2. Configure Environment Variables

Create a `.env` file in the root directory and add the following:

```env
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

> 💡 **Tip**: Keep your `.env` file private and never push it to version control.

### 3. Install Dependencies

#### Backend:

```bash
cd backend
npm install
```

#### Frontend:

```bash
cd ../frontend
npm install
```

---

## 🧪 Development Scripts

### Run Backend

```bash
cd backend
npm start
```

### Run Frontend

```bash
cd frontend
npm run dev
```

> App runs at: `http://localhost:5173` (Frontend) and `http://localhost:5001` (Backend)

---

## 🏗️ Build for Production

```bash
npm run build
```

---

---

## ✅ To-Do (Optional Enhancements)

- 🔔 Add Push Notifications  
- 🧵 Typing indicators  
- 🕹️ Emojis & Reactions  
- 📦 File sharing support  
- 🖼️ Image preview in chat  

---
