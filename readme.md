
# Real-Time Chat Application with Spring Boot & React.js

This repository contains the source code for a real-time chat application built using Spring Boot for the backend and React.js for the frontend. The application features:

- **Public Chat Rooms:** Users can join and chat in public rooms.
- **Private Messaging:** Users can send direct messages to other users.
- **User Registration:** Users can create accounts to access the chat features.
- **WebSocket Communication:** The application utilizes WebSockets for real-time message exchange.
- **Message Broadcasting:** Messages are broadcast to all connected users in the relevant room or conversation.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/sneha31chawla/chatapp
   ```

2. **Install Dependencies:**
   - **Backend (Spring Boot):**
     ```bash
     cd backend
     mvn install
     ```
   - **Frontend (React.js):**
     ```bash
     cd frontend
     npm install
     ```

3. **Run the Application:**
   - **Backend:**
     ```bash
     cd backend
     mvn spring-boot:run
     ```
   - **Frontend:**
     ```bash
     cd frontend
     npm start
     ```

4. **Access the Application:**
   Open your web browser and navigate to `http://localhost:3000` (or the port specified in your `frontend/package.json`).

## Project Structure

```
├── backend
│   ├── src
│   │   ├── main
│   │   │   └── java
│   │   │       └── com
│   │   │           └── example
│   │   │               └── chat
│   │   │                   └── ChatApplication.java
│   │   └── test
│   │       └── java
│   │           └── com
│   │               └── example
│   │                   └── chat
│   │                       └── ChatApplicationTests.java
│   ├── pom.xml
│   └── target
├── frontend
│   ├── src
│   │   ├── App.js
│   │   ├── components
│   │   │   ├── ChatRoom.js
│   │   │   ├── ChatInput.js
│   │   │   ├── MessageList.js
│   │   │   ├── PrivateMessage.js
│   │   │   └── UserList.js
│   │   ├── App.css
│   │   ├── index.css
│   │   ├── index.js
│   │   └── service
│   │       └── WebSocketService.js
│   ├── package.json
│   ├── public
│   │   ├── index.html
│   │   └── favicon.ico
│   ├── .gitignore
│   └── README.md
├── .gitignore
└── README.md
```

## Technologies Used

- **Backend:** Spring Boot, Spring WebSockets, Spring Data JPA, H2 Database (for development)
- **Frontend:** React.js, React Router, WebSocket API, CSS
- **Database:** H2 (for development) - PostgreSQL/MySQL can be used for production


## Author

[sneha chawla] - [snehachawla867@gmail.com] 

