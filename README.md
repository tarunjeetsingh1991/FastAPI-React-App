# 🧩 FastAPI + React Full Stack Application

This is a full-stack CRUD application built using **FastAPI** as the backend and **React.js** (Vite) as the frontend.  
The project demonstrates how to perform Create, Read, Update, and Delete operations via REST APIs and a modern React interface.

---

## 🚀 Tech Stack

### Backend
- **Python 3.11+**
- **FastAPI**
- **SQLAlchemy**
- **PostgreSQL / SQLite**
- **Pydantic**
- **Uvicorn**

### Frontend
- **React.js (Vite)**
- **Axios** for API calls
- **Bootstrap** / Custom CSS for UI styling



---

## ⚙️ How to Run Locally

### 🖥️ Backend (FastAPI)
```bash
cd backend
python -m venv venv
source venv/bin/activate     # On macOS/Linux
venv\Scripts\activate        # On Windows
pip install -r requirements.txt
uvicorn main:app --reload


The FastAPI backend will start at
👉 http://127.0.0.1:8000

You can test APIs here:
🔗 http://127.0.0.1:8000/docs

💻 Frontend (React)
cd frontend
npm install
npm run dev

react front end runs at : http://localhost:3000