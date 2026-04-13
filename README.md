# 💬 SyncUp – Real-Time Chat Application

SyncUp is a full-stack real-time chat application that enables seamless peer-to-peer messaging with instant delivery.  
It supports text & image sharing, online presence tracking, notifications, and sound effects for an immersive chat experience.

---

## 🚀 Features

💬 Real-Time Messaging – Instant delivery using Socket.io WebSockets  
🟢 Online Presence – Live user status indicators showing who is online  
🖼️ Media Sharing – Send images and text in chat, with Cloudinary handling media storage  
👤 Profile Pictures – Upload and update profile photos stored on Cloudinary  
🔐 Authentication – Secure signup/login with protected routes and session handling  
📧 Email on Signup – Automated welcome emails sent to new users via Resend  
🛡️ Rate Limiting – Backend endpoint protection using Arcjet to prevent abuse  
🔔 Sound Effects – Notification sounds and keyboard audio feedback for immersive UX  
⚡ Global State – Efficient client-side state management using Zustand  

---

## 🛠️ Tech Stack

Frontend: React.js, Zustand  
Backend: Node.js, Express.js  
Real-Time: Socket.io  
Database: MongoDB  
Media Storage: Cloudinary  
Email Service: Resend  
Security: Arcjet  

---

## 📂 Project Setup

### Clone the Repository
```bash
git clone https://github.com/your-username/syncup.git

