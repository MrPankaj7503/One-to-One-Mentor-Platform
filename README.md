# One-to-One-Mentor-Platform
Full-stack mentor-student platform with real-time video calling, chat, and live Python code execution using WebRTC and Spring Boot.
## Overview

This project is a **full-stack web application** that enables real-time interaction between a mentor and a student.
It integrates video calling, live chat, and Python code execution into a single platform.

---

## Features

* Real-time Video Call (WebRTC)
* Mic ON/OFF & Camera ON/OFF
* Real-time Chat (WebSocket)
* Python Code Execution (Pyodide)
* Screen Sharing
* Clean UI (Google Meet style)

---

## Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Java (Spring Boot)
* WebSocket

### Other Technologies

* WebRTC (Video Communication)
* Pyodide (Python in Browser)

---

## Project Structure

```
mentor-app/
│
├── src/main/java/com/mentor/
│   ├── MentorAppApplication.java
│   └── config/
│       ├── WebSocketConfig.java
│       └── SignalHandler.java
│
├── src/main/resources/static/
│   └── index.html
│
└── pom.xml
```

---

## How to Run

### 1. Clone the repository

```
git clone https://github.com/your-username/mentor-app.git
```

### 2. Run Spring Boot

```
mvn spring-boot:run
```

### 3. Open in browser

```
http://localhost:8080
```

---

## Testing

* Open the app in **2 tabs**
* Allow camera & microphone
* Wait a few seconds
* Video call will start automatically

---

## Future Improvements

* Login & Authentication system
* Mentor / Student roles
* Room-based session links
* Database integration
* Deployment to cloud
* Screen recording

---

## Use Cases

* Online teaching platform
* Coding interview system
* Remote mentorship sessions

---

## Author

Pankaj Kumar

---
