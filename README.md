## ChatterBox - Real-time WebSocket Chat Application
## 📌 Project Description

ChatterBox is a real-time chat application built using FastAPI and WebSockets. It allows multiple users to communicate instantly in a browser.

## 🚀 Features

Real-time messaging using WebSockets

Multiple user support

Clean and simple UI

FastAPI backend

User authentication with encrypted passwords

Chat history storage

## 🛠 Technologies Used

Python

FastAPI

WebSockets

HTML

CSS

JavaScript

SQLite (Database)

## ChatterBox_Project
## 📂 Project Structure
```│
├── __pycache__/
│
├── Frontend/
│   ├── chat.html
│   ├── index.html
│   ├── login.html
│   └── register.html
│
├── auth.py
├── chat_history.py
├── client.py
├── database.db
├── database.py
├── main.py
├── models.py
├── websocket_manager.py
│
├── LICENSE
└── README.md
```



## 🔄 User Workflow
➜ Registration

New users create an account; passwords are encrypted immediately.

➜ Login

Validated users receive a unique UUID token.

➜ Chat Interface

The system establishes a WebSocket connection using the token.

➜ History

The server pushes existing chat history from the database to the client.

➜ Live Chat

Messages are sent, saved to the database, and broadcasted to all active users simultaneously.

## ▶️ How to Run the Project
```
1️⃣ Install Required Packages
pip install fastapi uvicorn
2️⃣ Run the Server
uvicorn main:app --reload
3️⃣ Open in Browser
http://127.0.0.1:8000
```

## 👩‍💻 Developed By

Bhavya Sri Devi Gopala 
