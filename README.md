# 📝 CRUD-Application

A simple **To-Do Web App** built using **Flask**, a lightweight and powerful Python web framework.  
It lets users **Create**, **Read**, **Update**, and **Delete (CRUD)** their daily tasks easily and efficiently.

🔗 **Live Demo:** [Click here to open the app](https://crud-application-4-b1tr.onrender.com/)

---

## ⚙️ Features
- ➕ Add new tasks  
- 📋 View all tasks  
- ✏️ Update existing tasks  
- ❌ Delete tasks  
- 💾 Persistent storage using SQLite  
- 🧱 Minimal, clean UI  
- ☁️ Hosted on Render  

---

## 🧰 Tech Stack
| Component | Technology |
|------------|-------------|
| Backend | Flask (Python) |
| Database | SQLite (via SQLAlchemy) |
| Frontend | HTML, CSS (Jinja2 templates) |
| Hosting | Render |

---

## 🗂️ Project Structure

CRUD-Application/
│
├── app.py # Main Flask application
├── instance/
│ └── test.db # SQLite database
├── templates/
│ ├── index.html # Homepage (Task list + Add task form)
│ └── update.html # Task update page
├── requirements.txt # Dependencies
└── README.md # Project documentation


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/CRUD-Application.git
cd CRUD-Application


python -m venv venv
venv\Scripts\activate       # on Windows
# or
source venv/bin/activate    # on macOS/Linux


pip install -r requirements.txt
python app.py

🧩 How It Works

User enters a task in the form and submits it.

Flask stores it in the SQLite database.

Tasks are displayed dynamically on the homepage.

Each task can be updated or deleted instantly.

👨‍💻 Author

Sourav Singh
🎓 Cybersecurity Student | 💻 Flask Developer | 🧠 Python Enthusiast

