# 💳 Online Banking Management System

### 🏦 A Modern Web Application built with **Django**, **HTML**, **CSS**, **Tailwind CSS**, and **MySQL**

![Banking Banner](https://img.shields.io/badge/Online%20Banking%20System-Django%20Project-blue?style=for-the-badge&logo=django)
![Python](https://img.shields.io/badge/Python-3.x-green?style=for-the-badge&logo=python)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange?style=for-the-badge&logo=mysql)
![Tailwind](https://img.shields.io/badge/Frontend-TailwindCSS-blue?style=for-the-badge&logo=tailwindcss)

---

## 📖 Overview

The **Online Banking Management System** is a Django-based web project that allows users to manage their banking operations digitally.  
Users can **create accounts, deposit/withdraw money, view summaries**, and manage all their transactions in a secure environment.  

This project demonstrates the integration of backend logic (Django + MySQL) with a modern, responsive frontend (Tailwind CSS).

---

## 🚀 Features

✅ **Create Account** — Add new customer details easily  
💸 **Deposit & Withdrawal** — Manage transactions securely  
📊 **Account Summary** — View details and track balance  
🔐 **Change PIN** — Update PIN anytime with verification  
📬 **Email Integration (optional)** — For notifications  
🎨 **Modern UI** — Styled using Tailwind CSS & glassmorphism  
🗃️ **Database Management** — Using XAMPP + MySQL  

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML5, Tailwind CSS, JavaScript |
| **Backend** | Django (Python Framework) |
| **Database** | MySQL (via XAMPP) |
| **IDE / Tools** | VS Code, Git, XAMPP, Python 3.x |

---

## 🗂️ Folder Structure

```
OnlineBanking/
│
├── bank/                    # Main Django app
│   ├── templates/           # HTML Templates (home.html, create.html, etc.)
│   ├── static/              # CSS / JS / Images
│   ├── views.py             # App logic
│   ├── urls.py              # URL routes
│   └── models.py            # Database models
│
├── manage.py                # Django management script
├── db.sqlite3 / MySQL       # Database
├── requirements.txt         # Dependencies
└── README.md                # Project documentation
```

---

## ⚙️ Setup & Installation

Follow these steps to set up the project locally 👇  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/your-username/online-banking-system.git
cd online-banking-system
```

### 2️⃣ Create & activate virtual environment  
```bash
python -m venv venv
venv\Scripts\activate   # for Windows
```

### 3️⃣ Install dependencies  
```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Database  
- Start **XAMPP** → Enable *Apache* & *MySQL*  
- Create a new database (e.g., `projectbank`)  
- Update your database settings in `settings.py`

### 5️⃣ Run migrations  
```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Start the server  
```bash
python manage.py runserver
```

Then visit 👉 **http://127.0.0.1:8000/**  

---

## 💡 Future Improvements

✨ Add user authentication & admin roles  
📱 Make it fully responsive for mobile  
📊 Add transaction charts using Chart.js  
🔔 Integrate email or SMS alerts  

---

## 👨‍💻 Developer

**Mayank Rawat**  
🎓 *MCA Student | Python & Web Developer*  
📧 [mayankrawat9211@gmail.com]  
⭐ *If you like this project, give it a star on GitHub!*

---

## 🪪 License

This project is **open-source** and free to use under the MIT License.
