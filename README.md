# Real-Time Chat Application

A full-stack real-time chat application developed using **React.js, Spring Boot, WebSocket, MongoDB, and Tailwind CSS**. This project demonstrates how a frontend and backend can communicate in real time to provide instant messaging functionality.

## Technologies Used

### Frontend
- React.js
- Tailwind CSS
- JavaScript
- HTML
- CSS

### Backend
- Java
- Spring Boot
- WebSocket
- REST APIs

### Database
- MongoDB

### Tools
- Git & GitHub
- VS Code
- Maven

## Features

-  Real-time messaging using WebSocket
-  Instant two-way communication between users
-  REST APIs for application operations
-  Store and manage chat data using MongoDB
-  Maintain conversation/message history
-  Responsive user interface
-  React.js frontend integrated with Spring Boot backend

## Project Architecture
The application follows a basic full-stack architecture:

React.js + Tailwind CSS
          ↓
       REST API
          ↓
     Spring Boot
          ↓
      WebSocket
          ↓
       MongoDB


## Project Structure
Real-Time-Chat-Application/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/
│   │   └── main/
│   └── pom.xml
│
└── README.md

## How It Works

1. The user interacts with the **React.js frontend**.
2. REST APIs are used for normal application operations.
3. **WebSocket** establishes a real-time connection between the client and server.
4. Messages are sent and received instantly through WebSocket.
5. Chat and conversation data are stored in **MongoDB**.
6. React updates the user interface when new messages are received.

## What I Learned

Through this project, I learned:

- How to build a full-stack application using React.js and Spring Boot.
- How frontend and backend applications communicate using REST APIs.
- Basics of real-time communication using WebSocket.
- How to connect Spring Boot with MongoDB.
- How to design a responsive UI using Tailwind CSS.
- How to structure and manage a full-stack project.
- How to use Git and GitHub for version control.

## Future Improvements

- User authentication and authorization
- Private one-to-one chats
- Group chat functionality
- Online/offline user status
- Typing indicators
- Message notifications
- Message read/unread status
- Image and file sharing

## Author

**Aniket Kumar**

This project was developed as a learning project to strengthen my skills in **Java, Spring Boot, React.js, WebSocket, MongoDB, and full-stack development**.
