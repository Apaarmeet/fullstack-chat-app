# 🗨️ Full-Stack Chat Application

A real-time chat application built with the MERN (MongoDB, Express, React, Node.js) stack, WebSockets, and JWT authentication. This app enables users to sign up, log in, and engage in **one-on-one** conversations with real-time messaging.

## 🌍 Live Demo  
👉 **[Visit the Chat App](https://fullstack-chat-app-n3mi.onrender.com/)**

## 🚀 Features  
✅ **Real-Time Messaging** – Powered by WebSockets for instant communication  
✅ **User Authentication** – Secure sign-up and login with JWT  
✅ **One-on-One Chats** – Individual messaging between users  
✅ **Modern UI** – Responsive, sleek, and user-friendly interface  
✅ **MERN Stack** – Built with React (frontend), Express & Node.js (backend), and MongoDB (database)  
✅ **Online Status Indicator** – Know when users are online  
✅ **Secure Storage** – Messages and user data stored safely in MongoDB  

## 🛠️ Tech Stack  
- **Frontend**: React, Vite, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Authentication**: JWT (JSON Web Tokens)  
- **Real-time Communication**: WebSockets (socket.io)  


## 🔧 Installation & Setup  
To run the project locally, follow these steps:  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Apaarmeet/fullstack-chat-app.git
cd fullstack-chat-app
```

### 2️⃣ Install Dependencies  
#### Backend Setup  
```bash
cd backend
npm install
```
#### Frontend Setup  
```bash
cd ../frontend
npm install
```

### 3️⃣ Configure Environment Variables  
Create a `.env` file in the `backend` folder and set the following variables:  
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
SOCKET_PORT=your_socket_server_port
```

### 4️⃣ Start the Development Servers  
#### Backend  
```bash
cd backend
npm run dev
```
#### Frontend  
```bash
cd ../frontend
npm run dev
```

The application should now be running on **`http://localhost:3000`** 🎉  

## 📌 Future Enhancements  
🔹 Typing indicators  
🔹 Read receipts  
🔹 Dark mode  
🔹 Message search functionality  

## 🤝 Contributing  
Contributions are welcome! Feel free to fork the repo, submit issues, or make pull requests.  

## 📜 License  
This project is open-source and available under the **MIT License**.  

---

Give it a ⭐ on GitHub if you like it! 😊
