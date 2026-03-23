# ⚡ Real-Time Collaboration Tool

## 🚀 Project Overview

This project is a real-time collaboration tool built using Spring Boot and WebSocket. It allows multiple users to edit text simultaneously, with changes instantly reflected across all connected clients.

---

## 🛠 Technologies Used

* Java
* Spring Boot
* WebSocket
* STOMP Protocol
* HTML, JavaScript

---

## 📌 Features

* Real-time text editing
* Multiple user support
* Instant message broadcasting
* Live synchronization across tabs

---

## 🔗 How It Works

* Client connects using WebSocket
* Messages are sent using STOMP
* Server broadcasts updates to all users via `/topic`

---

## ▶️ How to Run the Project

1. Clone the repository
2. Open in Eclipse or any IDE
3. Run `CollabtoolApplication.java`
4. Open browser:
   http://localhost:8081

---

## 🧪 Testing

* Open the application in **multiple browser tabs**
* Type in one tab
* See real-time updates in other tabs

---

## 📂 Project Structure

* config → WebSocket configuration
* controller → Handles messaging logic
* static → Frontend (HTML + JS)

---

## 🎯 Conclusion

This project demonstrates real-time communication using WebSocket and Spring Boot, enabling collaborative editing with instant updates.

---

## 👨‍💻 Author

**Hemanth Kumar**
