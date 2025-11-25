# ConnectFlow – Real-time Group Chat App

ConnectFlow is a modern, high-performance real-time chat application built using the MERN stack and Socket.IO. It enables users to register, create or join groups, and chat instantly with real-time updates, typing indicators, and user presence tracking — all within a clean and responsive UI.

---

## Features
### Real-time Group Messaging

- Powered by Socket.IO for instant message delivery
- Messages update live across all connected clients

### Typing Indicators

- See who is typing inside a group in real time

### Online User Presence

- Tracks active users in each group
- Displays online/offline status dynamically

### Secure Authentication

- JWT-based login system
- Passwords hashed for security using bcrypt

### Fully Responsive UI

- Smooth and modern interface built with Chakra UI
- Works seamlessly on mobile, tablet, and desktop

---

## ⚙️ How to Run Locally

### 1. Clone the repo

```bash
git clone https://github.com/panwarshalini/ChatApp.git
cd ChatApp
```

### 2. Run Backend
```bash
cd backend
npm install
node server.js
```

### 3. Run Frontend
```bash
cd frontend
npm install
npm start
```
### 4. Create a .env File in Backend
```bash
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Tech Stack
### Frontend

- React.js
- Chakra UI
- Axios

### Backend

- Node.js
- Express.js

### Database

- MongoDB
- Mongoose

### Real-time Communication

- Socket.IO

### Authentication

- JWT
- bcrypt

---

## Connect. Collaborate. Chat.

Experience seamless, fast, and interactive conversations with ConnectFlow!


