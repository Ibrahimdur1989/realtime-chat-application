# Real-Time Chat Application

A full-stack real-time chat application built with Node.js, Express, MongoDB Atlas, and Socket.io.
The application supports real-time group messaging, private messaging, user authentication, and persistent message storage.

---


## Features

- Real-time group chat
- Private one-to-one messaging
- Room-based chat system
- User authentication
- Typing indicator
- Persistent message storage using MongoDB
- Session handling using localStorage
- Multiple predefined chat rooms


---

## Tech Stack

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Socket.io
- HTML5
- CSS3
- JavaScript

---

## Project Structure

- server/         Backend API and Socket.io server
- public/         Static frontend files
- view/           Application pages
- screenshots/    Application screenshots

---

## Installation & Setup 

### 1. Clone the repository
git clone https://github.com/Ibrahimdur1989/realtime-chat-application.git
### 2. Navigate to server folder
cd server
### 3. Install dependencies
npm install
### 4. Add MongoDB connection string

Create a .env file and add:

MONGO_URI=your_mongodb_connection_string
### 5. Start the server
node server.js
### 6. Open in browser
http://localhost:8081/signup.html

---

## Screenshots

### Login Page
![Login](screenshots/login.png)

### Chat Room
![Chat Room](screenshots/chat_room.png)

### Private Message
![Private Chat](screenshots/private_chat.png)

### Signup Page
![Signup](screenshots/signup.png)


### MongoDB Users Collection
![MongoDB Users](screenshots/mongo_users.png)


### Group Messages Stored in MongoDB
![Group Messages](screenshots/group_messages_mongodb.png)

### Private Messages Stored in MongoDB
![Private Messages](screenshots/private_messages_mongodb.png)

---

## Future Improvements
* JWT authentication
* Responsive mobile design
* Online user status
* File sharing support
* Notifications system
* User profile management


## Author

### Ebrahim Al-Serri
Computer Programming & Analysis - Graduate 2026

George Brown College
