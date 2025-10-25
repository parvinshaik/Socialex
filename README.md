SocialeX – Social Media App 🚀
Introduction
SocialeX is a modern social media app designed to connect, engage, and explore. This project was developed as a part of my internship at SmartInternz, aiming to create a seamless social media experience.
It offers:

Real-time messaging with friends and followers

Post and story creation (text, images, videos)

Notifications for likes, comments, and mentions

Secure authentication and encrypted data

Follow and discover new communities

The app uses a client-server architecture with React.js frontend, Node.js + Express backend, Socket.io for real-time communication, and MongoDB for database storage.

Features
Real-time Updates: Instant notifications for user interactions
Messaging & Chat: Private/group chats with text, images, and emojis
Posts & Stories: Create, share, and interact with multimedia content
Follow & Discover: Follow other users and explore trending content
Data Privacy & Security: All data encrypted and securely stored

🛠️ Tech Stack
Frontend	Backend	    Database	Realtime
React.js	Node.js	    MongoDB	    Socket.io
Axios	    Express.js	Mongoose	Socket.io-client
Firebase	Bcrypt		

Other libraries: Bootstrap, uuid, body-parser, dotenv, cors

📁 Project Structure
SocialeX/
├── client/          # React frontend
│   ├── public/
│   └── src/
├── server/          # Node.js backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── index.js
├── .env             # Environment variables
└── README.md

⚡ Installation

Clone the repository

git clone https://github.com/parvinshaik/Socialex.git
cd SocialeX


Install dependencies

# Frontend
cd client
npm install

# Backend
cd ../server
npm install


Setup Environment Variables
Create a .env file in /server:

MONGO_URI=your_mongodb_uri
PORT=6001
JWT_SECRET=your_secret_key


Start the App

# Backend
cd server
npm start

# Frontend
cd client
npm start


Access the app: http://localhost:3000



🔑 Features Walkthrough
Authentication

User registration & login

Passwords secured with bcrypt

Authentication state managed via Context API

Real-Time Messaging

Implemented using Socket.io

Supports emojis, images, and text

Group and private chats

Posts & Stories

Create posts and stories (text/images/videos)

Media uploaded to Firebase

Stories disappear after 24 hours

Interact via likes, comments, and shares

Notifications

New followers and chat notifications

Real-time updates with Socket.io

Roles & Responsibilities
User:
Create and manage profile
Share posts and stories
Interact with content (likes, comments, shares)
Connect and chat with other users
