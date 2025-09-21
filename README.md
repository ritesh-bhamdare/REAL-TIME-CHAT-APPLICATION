# ✨ REAL-TIME-CHAT-APPLICATION ✨

**COMPANY:** CODTECH IT SOLUTIONS  
**NAME:** RITESH BHAMDARE   
**INTERN ID:** CT08DZ656  
**DOMAIN:** REACT.JS WEB DEVELOPMENT  
**DURATION:** 8 WEEKS  
**MENTOR:** NEELA SANTHOSH KUMAR  

### 🌟 REAL-TIME CHAT APPLICATION

**Tech Stack:** MERN + Socket.io + TailwindCSS + Daisy UI  

A modern **real-time chat application** built with the MERN stack, enabling users to communicate instantly, see online statuses, and manage conversations efficiently. This project demonstrates full-stack development with real-time messaging, authentication, and global state management.

---

## 🚀 Features

- **Authentication & Authorization** with JWT  
- **Real-time Messaging** with Socket.io  
- **Online User Status**  
- **Global State Management** using Zustand  
- **Error Handling** on both server and client  
- **Responsive UI** using TailwindCSS + Daisy UI  
- And much more!

---

### 🔹 Authentication & Authorization
- Secure **registration** and **login** with JWT tokens  
- Passwords are **hashed** before storing in MongoDB  
- Protected routes ensure only authenticated users can access chats  

---

### 🔹 Real-Time Messaging
- Messages are delivered **instantly** without refreshing the page  
- **One-on-one conversations** with message history stored in MongoDB  
- Supports **future extension** for group chats  

---

### 🔹 Online User Status
- Shows which users are **online or offline** in real time  
- Status updates automatically when users connect or disconnect  

---

### 🔹 Global State Management
- Uses **Zustand** for handling user info, messages, and online status  
- Avoids prop drilling and simplifies state management across components  

---

### 🔹 Responsive UI
- Built with **TailwindCSS** and **Daisy UI** for modern and clean interface  
- Fully responsive across desktop and mobile devices  

---

### 🔹 Error Handling
- Handles errors **both on client and server**  
- Displays proper messages for login failures, registration errors, and server issues  

---

## ⚡ Installation

1. **Clone the repository:**
```bash
git clone https://github.com/ritesh-bhamdare/REAL-TIME-CHAT-APPLICATION.git

```

2. **Navigate to the backend folder and install dependencies:**

```bash
cd REAL-TIME-CHAT-APPLICATION/server
npm install
```
3. **Navigate to the frontend folder and install dependencies:**
```bash
cd ../client
npm install
```
4. **Create a .env file in the backend folder with the following variables:**
```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```
5. **Start the development servers:**

- Backend server:
```bash
cd ../server
npm run server
```
- Frontend server:
```bash
cd ../client
npm run dev
```

## OUTPUT:
<p float="left" align="center">
  <img src="https://github.com/user-attachments/assets/2db98de6-2484-4f23-92cb-81b8404aa0c3" width="300"  alt="Image" />
  <img src="https://github.com/user-attachments/assets/aeb3915a-322b-4e63-9c28-f92926707dda" width="300"  alt="Image" />
  <img src="https://github.com/user-attachments/assets/4422b5b8-c0b9-4a57-97e1-d4719e33a080" width="300"  alt="Image" />
</p>
