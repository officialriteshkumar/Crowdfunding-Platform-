# 🌟 Crowdfunding Platform

A full-stack web application that allows users to raise funds for personal projects, charitable causes, or business ideas. Built with **Next.js** (frontend), **Django REST Framework** (backend), **MySQL**, and integrated with **Stripe** for secure payments.

---

## 📌 Features

- 🔐 User Registration & Login (JWT Auth)
- 📢 Create & Manage Campaigns
- 💳 Donate to Campaigns (Stripe Integration)
- 📊 Track Campaign Progress (Goal vs Raised)
- 💬 Comment on Campaigns
- 👨‍💻 Admin Panel for Moderation

---

## 🛠️ Tech Stack

### Frontend
- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Axios](https://axios-http.com/)
- [Stripe JS](https://stripe.com/docs/js)

### Backend
- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- [MySQL](https://www.mysql.com/) or SQLite (dev)

---

## 📁 Project Structure


---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.8+
- Node.js v18+
- MySQL or SQLite
- pip / npm / yarn
- Virtualenv (optional)

---

## ⚙ Backend Setup (Django)

```bash
# Step 1: Go to backend
cd backend

# Step 2: Create virtual environment
python -m venv venv

# Step 3: Activate venv
venv\Scripts\activate  # Windows
# or
source venv/bin/activate  # macOS/Linux

# Step 4: Install dependencies
pip install -r requirements.txt

# Step 5: Migrate DB
python manage.py makemigrations
python manage.py migrate

# Step 6: Create admin user
python manage.py createsuperuser

# Step 7: Run server
python manage.py runserver
# Step 1: Go to frontend
cd frontend

# Step 2: Install packages
npm install
# or
yarn install

# Step 3: Start dev server
npm run dev
# or
yarn dev
const API = axios.create({
  baseURL: 'http://127.0.0.1:8000/api/',
});
# Step 1: Go to frontend
cd frontend

# Step 2: Install packages
npm install
# or
yarn install

# Step 3: Start dev server
npm run dev
# or
yarn dev
const API = axios.create({
  baseURL: 'http://127.0.0.1:8000/api/',
});
