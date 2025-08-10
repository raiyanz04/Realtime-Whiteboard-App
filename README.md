# 🎨 Realtime Whiteboard App  

Collaborate, sketch, and brainstorm **together in real-time** — powered by **React** and **Socket.IO**.  
This project allows multiple users to draw on a shared whiteboard and see updates instantly.  

---

## ⚡ Features  
- ✏ **Live Drawing** – Instantly syncs your sketches with all connected users.  
- 🔌 **WebSocket-Powered** – Uses Socket.IO for smooth, real-time communication.  
- 🎯 **React Frontend** – Modern UI and responsive design.  
- 🗂 **Separate Frontend & Backend** – Clear separation for easier scaling and maintenance.  

---

## 🛠 Prerequisites  
Make sure you have:  
- [Node.js](https://nodejs.org/)  
- [Git](https://git-scm.com/)  
- A code editor like [VS Code](https://code.visualstudio.com/)  
- Basic knowledge of React  
- A modern browser (Chrome, Firefox, etc.)  
- **Yarn** (`npm install -g yarn` if not installed)  

---

## 📦 Installation  

1️⃣ **Clone or Download** this repository  
```
git clone https://github.com/raiyanz04/Realtime-Whiteboard-App.git
```

2️⃣ **Install Backend Dependencies**

```
cd backend
yarn
```
3️⃣ **Install Frontend Dependencies**
```
cd ../frontend
yarn
```
🚀 **Running the App**
**Start Backend Server**
```
cd backend
yarn start
```
**Start Frontend Development Server**
```
cd frontend
yarn dev
```

**How it works:**
- The user draws on the whiteboard in their browser.
- The frontend sends drawing events via Socket.IO to the backend server.
- The backend broadcasts these events to all other connected clients.
- Everyone’s whiteboard updates instantly.

🤝 **Contribution**
Feel free to fork this repo, submit pull requests, or suggest new features.
We welcome all kinds of contributions — from fixing small bugs to adding big new features.
If you're not sure where to start, try improving the UI, optimizing performance, or writing documentation.
