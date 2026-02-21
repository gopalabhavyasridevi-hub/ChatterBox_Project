ChatterBox - Real-time WebSocket Chat Application
📌 Project Description

ChatterBox is a real-time chat application built using FastAPI and WebSockets. It allows multiple users to communicate instantly in a browser.

🚀 Features

Real-time messaging using WebSockets

Multiple user support

Clean and simple UI

FastAPI backend

User authentication with encrypted passwords

Chat history storage

🛠 Technologies Used

Python

FastAPI

WebSockets

HTML

CSS

JavaScript

SQLite (Database)

📂 Project Structure
ChatterBox/
│
├── main.py              # FastAPI main application file
├── database.py          # Database connection and configuration
├── models.py            # Database models (User, Messages)
├── auth.py              # Authentication logic (Login, Register, JWT)
├── websocket.py         # WebSocket connection handling
│
├── static/              # CSS and JavaScript files
│   ├── style.css
│   └── script.js
│
├── templates/           # HTML templates
│   ├── index.html
│   ├── login.html
│   └── register.html
│
├── requirements.txt     # Required Python packages
├── README.md            # Project documentation
└── LICENSE              # MIT License

(If your file names are slightly different, tell me — I’ll adjust it exactly to your project.)

🔄 User Workflow
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

▶️ How to Run the Project
1️⃣ Install Required Packages
pip install fastapi uvicorn
2️⃣ Run the Server
uvicorn main:app --reload
3️⃣ Open in Browser
http://127.0.0.1:8000
👩‍💻 Developed By

Bhavya Sri Devi Gopala 
