# 🎨 Whiteboard Telepathy

A real-time collaborative whiteboard application where multiple users can draw together, save their canvases, and collaborate seamlessly.



## 🎥 Project Video
https://github.com/user-attachments/assets/abdb8a61-3dd2-4c27-b48e-ee0b99a462d4


## 🚀 Features

- ✏️ Freehand Drawing
- 🎨 Multiple Colors
- 📏 Adjustable Brush Size
- 🧹 Eraser Tool
- ↩️ Undo / Redo
- 🗑️ Clear Canvas
- 💾 Save Canvas
- 🔐 User Authentication (JWT)
- 👥 Multi-user Support
- ⚡ Real-time Updates using Socket.io

## 🛠️ Tech Stack

### Frontend
- React.js
- CSS Modules
- Axios
- React Router
- Perfect Freehand
- Socket.io Client

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Socket.io

---

## 📂 Project Structure

```text
whiteboard-telepathy/
│
├── backend/                          # Express.js backend
│   ├── config/
│   │   └── db.js                     # MongoDB connection
│   │
│   ├── controllers/
│   │   ├── canvasController.js       # Canvas-related APIs
│   │   └── userController.js         # Authentication logic
│   │
│   ├── middlewares/
│   │   └── authMiddleware.js         # JWT authentication middleware
│   │
│   ├── models/
│   │   ├── canvasModel.js            # Canvas schema
│   │   └── userModel.js              # User schema
│   │
│   ├── routes/
│   │   ├── canvasRoutes.js           # Canvas API routes
│   │   └── userRoutes.js             # User API routes
│   │
│   ├── server.js                     # Backend entry point
│   ├── package.json
│   ├── vercel.json
│   └── .env
│
├── whiteboard-tutorial/              # React frontend
│   ├── public/
│   │   ├── index.html
│   │   ├── favicon.ico
│   │   └── ...
│   │
│   ├── src/
│   │   ├── components/
│   │   │   ├── Board/                # Drawing canvas
│   │   │   ├── Login/                # Login page
│   │   │   ├── Register/             # Registration page
│   │   │   ├── Sidebar/              # Sidebar controls
│   │   │   ├── Toolbar/              # Drawing tools
│   │   │   └── ...
│   │   │
│   │   ├── App.js                    # Main React component
│   │   ├── index.js                  # React entry point
│   │   └── ...
│   │
│   ├── package.json
│   └── README.md
│
├── .gitignore
└── README.md
```
## 🌐 Deployment Links

🚀 **Frontend (Vercel)**  
https://whiteboard-tutorial-eight.vercel.app/

⚙️ **Backend API (Render)**  
https://api-whiteboard-az.onrender.com/


👨‍💻 Author

Krishna Goyal
