# 📚 Bookstore DRF API

A production-ready **Bookstore REST API** built using **Django** and **Django REST Framework** with **JWT Authentication**.  
This project demonstrates backend development skills including API design, authentication, and secure architecture.

---

## 🚀 Project Overview

The Bookstore API allows users to:

- Manage books (CRUD operations)
- Authenticate using JWT tokens
- Integrate with frontend applications using CORS
- Follow scalable REST architecture

This project is suitable for learning backend development and showcasing in a portfolio.

---

## ✨ Features

- RESTful API design
- Book CRUD operations
- JWT Authentication (Login / Refresh)
- Secure endpoints
- Modular Django apps
- CORS enabled for frontend integration
- Clean and scalable architecture

---

## 🛠️ Tech Stack

- Python
- Django
- Django REST Framework
- Simple JWT (Authentication)
- Django CORS Headers
- SQLite (default database)

---

## 📦 Installation

### 1️⃣ Clone repository

```bash
git clone https://github.com/meghaaji1320/Bookstore-drf.git
cd Bookstore-drf
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate   # Mac/Linux
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
http://127.0.0.1:8000/
POST /api/token/
POST /api/token/refresh/
Authorization: Bearer <access_token>
| Method | Endpoint         | Description   |
| ------ | ---------------- | ------------- |
| GET    | /api/books/      | List books    |
| POST   | /api/books/      | Create book   |
| GET    | /api/books/{id}/ | Retrieve book |
| PUT    | /api/books/{id}/ | Update book   |
| DELETE | /api/books/{id}/ | Delete book   |
pip install drf-yasg
/swagger/
/redoc/
pip install django-cors-headers
Bookstore-drf/
│── bookstore/        # Main project settings
│── books/            # Books app (models, serializers, views)
│── users/            # Authentication / user logic (optional)
│── manage.py
│── requirements.txt
