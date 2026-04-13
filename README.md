💬 SyncUp – Real-Time Chat Application
SyncUp is a full-stack real-time chat application that enables seamless peer-to-peer messaging with instant delivery. It supports text and image sharing, online presence tracking, and a rich user experience with notification and keyboard sounds.
🚀 Features

💬 Real-Time Messaging – Instant message delivery using Socket.io WebSockets
🟢 Online Presence – Live user status indicators showing who is online
🖼️ Media Sharing – Send images and text in chat, with Cloudinary handling media storage
👤 Profile Pictures – Upload and update profile photos stored on Cloudinary
🔐 Authentication – Secure signup/login with protected routes and session handling
📧 Email on Signup – Automated welcome emails sent to new users via Resend
🛡️ Rate Limiting – Backend endpoint protection using Arcjet to prevent abuse
🔔 Sound Effects – Notification sounds and keyboard audio feedback for immersive UX
⚡ Global State – Efficient client-side state management using Zustand

🛠️ Tech Stack

Frontend – React.js, Zustand
Backend – Node.js, Express.js
Real-Time – Socket.io
Database – MongoDB
Media Storage – Cloudinary
Email Service – Resend
Security – Arcjet

📂 Project Setup & Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/syncup.git
2️⃣ Navigate to the Project Directory
cd syncup
3️⃣ Install Dependencies
npm install
4️⃣ Set Up Environment Variables
Create a .env file in the root directory and add:
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
RESEND_API_KEY=your_resend_api_key
ARCJET_API_KEY=your_arcjet_api_key
▶️ Running the Development Server
npm run dev
🏗️ Building the Project
npm run build
👩‍💻 Author
Aarohi Sukhija – Feel free to connect and contribute 🚀
⭐ If you like this project, don't forget to give it a star on GitHub!
