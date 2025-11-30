---

# 📅 Task Scheduler (Personal Project)

**Task Scheduler** is a smart and modern task management web application designed to help users organize their daily activities, track progress, and manage schedules effortlessly.
This is a **personal full-stack learning project**, built to enhance web development, UI/UX, and productivity-app development skills.

---

## ✨ Features

* 📝 Add, edit, delete tasks
* 📊 Dashboard with statistics
* 📅 Interactive calendar view
* 🔄 Daily task tracking
* 🧠 ML-based task priority prediction (High / Medium / Low)
* 📱 Fully responsive UI
* 🎨 Clean and modern interface
* ⏱️ Built-in task timer
* 🌙 Light/Dark theme support (UI-ready)
* 📦 PWA-ready setup
* 📤 Export schedule (coming soon)

---

## 🧠 ML Task Prioritization

The project includes a simple Machine Learning script that predicts task priority based on:

* Days left before deadline
* Task complexity
* Importance
* Overdue count

### Available Files

* `ml/data.csv` — sample dataset
* `ml/ml_prioritization.py` — ML training & prediction script
* `ml/task_priority_model.pkl` — saved trained model

### Run the ML script

```
cd ml
python ml_prioritization.py
```

---

## 🛠 Tech Stack

### **Frontend**

* React 19
* React Router
* Tailwind CSS
* Vite

### **Machine Learning**

* Python
* Pandas
* Scikit-Learn

### **Other Tools**

* ReportLab / WeasyPrint (PDF – upcoming)
* PostgreSQL / SQLite (backend – upcoming)

---

## 🚀 Getting Started

### 1. Clone the project

```
git clone https://github.com/AnamMalikk/Task-Schedular.git
cd Task-Schedular
```

### 2. Install frontend

```
cd frontend
npm install
```

### 3. Run development server

```
npm run dev
```

Open in browser:
👉 `http://localhost:5173/`

---

## 📁 Project Structure

```
Task-Schedular/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── contexts/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── ml/
│   ├── data.csv
│   ├── ml_prioritization.py
│   └── task_priority_model.pkl
│
└── README.md
```

---

## 🔍 Troubleshooting

### Port already in use?

```
npm run dev -- --port 3000
```

### Dependency issues?

```
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
```

### Check Node version:

```
node --version
```

Must be **v18+**.

---

## 👤 Author

**Anam Malik**

---
