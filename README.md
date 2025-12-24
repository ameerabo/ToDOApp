# 📝 ToDOApp – FastAPI Todo Application
Feel free to try the live version below 👇

[![Live Demo](https://img.shields.io/badge/🌍%20Live%20Demo-Click%20Here-brightgreen?style=for-the-badge)](https://todoapp-tml4.onrender.com)

A full-stack **Todo Management Web Application** built with **FastAPI**, featuring user authentication, role-based access control, and a relational database with migrations.

The application supports **JWT authentication**, **admin/user roles**, and a web UI rendered with **Jinja2 templates**.

---

## 🚀 Features

### ✅ Authentication & Authorization
- User registration and login
- JWT-based authentication (OAuth2 password flow)
- Role-based access control (`admin` / `user`)
- Secure password hashing with bcrypt

### 🗂️ Todo Management
- Create, read, update, and delete todos
- Todos are user-specific (ownership enforced)
- Priority levels and completion status
- Admin endpoints for managing all todos

### 🖥️ Web Interface
- Server-side rendered pages (Jinja2)
- Login & registration pages
- Todo list, add, edit, and delete pages
- Automatic redirect to login when unauthorized

### 🗄️ Database
- SQLAlchemy ORM
- Alembic migrations
- Relational database (SQLite by default)

---

## 🧠 Tech Stack

**Backend**
- Python
- FastAPI
- SQLAlchemy
- Alembic
- OAuth2 + JWT (python-jose)
- Passlib (bcrypt)

**Frontend**
- HTML
- CSS
- JavaScript
- Jinja2 Templates

**Database**
- SQLite (can be replaced with PostgreSQL / MySQL)

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/ameerabo/ToDOApp.git
cd ToDOApp
