# Farabi College Recommendation & Issue Reporting System

A full-stack web platform designed for students and staff of **Farabi College, University of Tehran**, to post, discuss, and track issues or suggestions related to university life.  
This system provides a transparent and structured way for students to voice concerns while helping administrators identify and prioritize improvements.

---

## 🧩 Overview

The **Farabi Recommendation System** consists of two main parts:

- **Frontend:** A Next.js web application for users to interact with the platform.
- **Backend API:** A Django REST Framework service handling authentication, data management, and API endpoints.

The system is built with modularity and scalability in mind, supporting future expansions such as AI-based recommendation categorization, user voting analytics, and integration with university services.

---

## 📁 Project Structure

```
Farabi_REC/
├── .env.example          # Example environment configuration
├── .env                  # User-specific environment variables (not committed)
├── web/                  # Frontend - Next.js app
├── api/                  # Backend - Django REST Framework app
├── tests/                # Automated API endpoint tests
├── .github/workflows/    # CI/CD pipeline configurations
├── LICENSE               # License file
└── README.md             # Documentation (you’re here)
```

---

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Farabi_REC.git
cd Farabi_REC
```

### 2. Configure environment variables

Copy `.env.example` and create your own `.env` file in the root directory:

```bash
cp .env.example .env
```

Then edit `.env` to include your actual database, API, and frontend settings.

### 3. Backend Setup (Django REST Framework)

```bash
cd api
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### 4. Frontend Setup (Next.js)

```bash
cd web
npm install
npm run dev
```

The frontend should now be running at `http://localhost:3000`  
and the API at `http://localhost:8000`.

---

## 🧪 Testing

Automated tests for API endpoints are located in the `tests/` directory.

To run the test suite:

```bash
pytest
```

---

## 🚀 Deployment & CI/CD

This project includes GitHub Actions workflows under `.github/workflows` for continuous integration and deployment.

---

## 🧠 Features

- 🏫 University-specific issue tracking and recommendation posting  
- 💬 Commenting and feedback threads  
- 🔐 User authentication (students and staff)  
- 📊 Administrative dashboard for managing reports  
- 📬 Notifications for updates and responses  
- 🧩 Modular architecture for easy scaling and maintenance  

---

## ✨ Acknowledgements

Developed for **Farabi College, University of Tehran**, with the goal of strengthening student-administration collaboration through technology and transparency.