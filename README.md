# 🌟 Quarter 04 Learning Projects – Generative AI & FastAPI Mastery 🚀

Welcome to my **Quarter 4 Learning Repository**, where I explored the cutting edge of technology including **Generative AI** and built several powerful backend projects using **FastAPI**. This repository contains all tasks from my learning journey.  

---

## 📘 Task 01 – What is Generative AI?

> **Generative AI** is a revolutionary branch of artificial intelligence that enables machines to **create original content** — text, images, music, code, and videos.  
> Tools like **ChatGPT**, **DALL·E**, **Midjourney**, and **GitHub Copilot** demonstrate this technology in real life.  
>  
> It's not just a tool — it's a **digital partner in creativity and innovation**. 🌐✨

---

## ⚡ Task 02 – FastAPI Hello World with Uvicorn

✅ Built and ran a minimal FastAPI server  
✅ Created dynamic routes like `/items/{item_id}`  
✅ Explored built-in `/docs` for real-time API testing  
✅ Perfect introduction to Python backend development

---

## 🤖 Task 03 – FastAPI Chatbot using Pydantic Models

🎯 Integrated Pydantic for strict data validation  
🧠 Designed nested models for chatbot messaging and session metadata  
🗂 Created structured request/response schemas for real-world chatbot workflows  
🧪 Tested via Swagger `/docs` UI

---

## 📦 Task 04 – FastAPI Item Management API

A simple yet effective project to learn about:
- Path Parameters  
- Query Parameters  
- Request Bodies  
- Header Handling  
- Built-in API docs with **Swagger** & **ReDoc**

Clean and efficient for beginners starting with modern API development.

---

## 🧩 Task 05 – FastAPI Dependency Injection (DI)

Explored DI in FastAPI:
- Simple and reusable dependencies  
- Query-based authentication  
- Class-based dependencies with validation logic  
- Clean structure for scalable APIs

🧠 **Learned how DI helps make code clean, testable, and modular.**

---

## ✅ Task 06 – Task Tracker API (Final Project)

A fully functional backend system using FastAPI & Pydantic.

### 🚀 Features:
- 🔐 **User creation** with email & username validation  
- 📋 **Task management** with due date validation  
- 🔄 **Status updates** (allowed values only)  
- 🔍 **Fetch tasks by user**

---

## 🛠 Tech Stack

- Python 🐍  
- FastAPI ⚡  
- Pydantic ✅  
- Uvicorn 🔄  

---

## 🔗 API Endpoints Summary

### 👤 Users
- `POST /users/` – Create a new user  
- `GET /users/{user_id}` – Retrieve a user by ID

### ✅ Tasks
- `POST /tasks/` – Create a new task  
- `GET /tasks/{task_id}` – Get a task by ID  
- `PUT /tasks/{task_id}` – Update task status only  
- `GET /users/{user_id}/tasks` – List all tasks for a user

---

## ⚙️ Getting Started (Local Setup)

```bash
# 1. Clone the repository
git clone https://github.com/your-username/task-tracker-api.git
cd task-tracker-api

# 2. Create virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the server
uvicorn main:app --reload

Then open 👉 http://127.0.0.1:8000/docs to explore your live API!

📸 Preview

📄 License
This project is licensed under the MIT License.
Feel free to use, modify, and share!

🙌 Acknowledgements
Special thanks to my amazing instructors and mentors who guided me through this journey. 💙

🚀 Connect with me on LinkedIn to explore more of my work and tech journey.



