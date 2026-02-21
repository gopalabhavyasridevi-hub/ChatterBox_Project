# ChatterBox - Real-time WebSocket Chat Application

## 📌 Project Description
ChatterBox is a real-time chat application built using FastAPI and WebSockets. 
It allows multiple users to communicate instantly in a browser.

## 🚀 Features
- Real-time messaging using WebSockets
- Multiple user support
- Clean and simple UI
- FastAPI backend

## 🛠 Technologies Used
- Python
- FastAPI
- WebSockets
- HTML
- CSS
- JavaScript
  
  **User Workflow**
    ->Registration: New users create an account; passwords are encrypted immediately.
    ->Login: Validated users receive a unique UUID token.
    ->Chat Interface: The system establishes a WebSocket connection using the token.
    ->History: The server pushes existing chat history from the database to the client.
    ->Live Chat: Messages are sent, saved to the database, and broadcasted to all active users simultaneously.


## ▶️ How to Run the Project

1. Install required packages:
   pip install fastapi uvicorn

2. Run the server:
   uvicorn main:app --reload

3. Open browser:
   http://127.0.0.1:8000

## 👩‍💻 Developed By
Bhavya Sri Devi.Gopala
