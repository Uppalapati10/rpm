# RPM – E-Commerce Management System

## 📌 Project Overview
RPM is a full-stack **E-Commerce Management System** designed to provide a seamless online shopping experience. The system enables users to browse products, manage carts, place orders, and make payments, while administrators can manage products, users, and orders efficiently.  
This project was developed as part of a **Distributed Cloud Computing** course and demonstrates real-world cloud-based application design.

---

## 🚀 Features
- User registration and authentication (JWT-based)
- Product listing, search, rating, and reviews
- Shopping cart and checkout process
- Payment gateway integration (test mode)
- User profile with order history
- Admin dashboard for product and order management
- Product recommendation system
- RESTful API architecture

---

## 🛠️ Technology Stack

### Frontend
- ReactJS
- JSX
- Bootstrap
- JavaScript

### Backend
- Django
- Django REST Framework (DRF)
- JWT Authentication

### Database
- SQLite (development)

### Cloud & Deployment
- AWS EC2
- AWS IAM
- PM2 (frontend process manager)

---

## 📂 Project Structure
rpm/
│
├── backend/ # Django backend and REST APIs
├── frontend/ # React frontend application
├── base/ # Core application logic
├── manage.py
├── db.sqlite3
└── README.md


---

## ⚙️ Installation & Setup

### Backend Setup
```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver



---

## 
### Frontend Setup
```bash
cd frontend
npm install
npm start
