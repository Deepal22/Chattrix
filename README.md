💬 MERN Real-Time Chat Application

A full-stack real-time chat application built using the MERN stack with secure JWT authentication and Cloudinary image uploads. Users can register, login, send messages in real-time, and share images securely.

🚀 Features

🔐 JWT-based Authentication (Login / Register)

💬 Real-time messaging (Socket.io)

🖼️ Image sharing via Cloudinary

👀 Message seen status

🕒 Timestamps for messages

📱 Responsive UI

🔒 Protected routes

🟢 Online/offline user status

🏗️ System Architecture

Frontend: React.js

Backend: Node.js + Express

Database: MongoDB (Mongoose ODM)

Real-Time Engine: Socket.io

Authentication: JWT + bcrypt

Media Storage: Cloudinary

Messaging Flow

User authenticates via JWT

Socket connection established

Messages emitted to unique chat rooms

Stored in MongoDB for persistence

Delivered instantly to active users

Additional Tools & Libraries

JWT (JSON Web Token) – Authentication

Socket.io – Real-time communication

Cloudinary – Image storage

Mongoose – MongoDB ODM

Axios – API requests

bcryptjs – Password hashing

dotenv – Environment variable management

🔐 Authentication Flow

User registers with email & password

Password is hashed using bcrypt

On login, server generates a JWT token

Token is stored in HTTP-only cookies / local storage

Protected routes verify JWT middleware

☁️ Cloudinary Integration

Images are uploaded to Cloudinary

Only image URL is stored in MongoDB

Ensures optimized and secure storage

Reduces backend server load

💬 Real-Time Messaging Flow

Socket.io establishes WebSocket connection

Users join unique chat rooms

Messages are emitted and received instantly

Messages stored in MongoDB for persistence

🔒 Security Features

Password hashing (bcrypt)

JWT authentication

Protected API routes

Environment variables for sensitive data

CORS enabled properly

📸 Screenshots

<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/8eed4da0-6909-4cf2-a554-294a487e9f7b" />

<img width="1919" height="901" alt="image" src="https://github.com/user-attachments/assets/2bb75b07-9697-455d-87e4-424896b57087" />

<img width="1919" height="901" alt="image" src="https://github.com/user-attachments/assets/2b7f7b65-b28e-4b0a-a6c4-3ce20f5dc2c9" />

<img width="1911" height="901" alt="Screenshot 2026-03-02 205350" src="https://github.com/user-attachments/assets/d3f9c852-7d62-4083-b3bf-091c48f0fa1c" />

<img width="1918" height="907" alt="Screenshot 2026-03-02 205612" src="https://github.com/user-attachments/assets/9692300f-54ce-479e-9dcb-b0c0db0fe2d9" />

Live: http://chattrix-rosy.vercel.app/

🌍 Future Improvements

Group chats

Typing indicators

Push notifications

Message reactions

Read receipts for groups

Deployment on AWS 

📦 Deployment

You can deploy:

Backend → Vercel

Frontend → Vercel

Database → MongoDB Atlas
