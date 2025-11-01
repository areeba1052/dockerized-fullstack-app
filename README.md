# 🧩 Flask + Docker Compose Assignment

**Areeba**  
*(Private university assignment – not for public use)*

---

## 📘 Overview

This project demonstrates a simple **containerized full-stack application** using **Flask**, **SQLite**, and **Docker Compose**.  
It includes a backend API that stores form data and a basic frontend interface served separately through Docker containers.

---

## 🧠 Components

- **Backend:** Flask app using SQLAlchemy and SQLite database  
- **Frontend:** Simple HTML interface for data submission  
- **Containerization:** Dockerfiles for both frontend and backend with `docker-compose.yml` for orchestration

---

## 🗂️ Project Structure

├── backend/
│ ├── app.py
│ ├── mydatabase.db
│ ├── requirement.txt
│ ├── dockerfile
│
├── frontend/
│ ├── index.html
│ ├── src/
│ ├── dockerfile
│
├── docker-compose.yml
├── running_containers.PNG
└── venv/

---

## ⚙️ Technologies Used

- Python (Flask, SQLAlchemy, Flask-CORS)  
- SQLite  
- Docker & Docker Compose  
- HTML / JavaScript (Frontend)

---

## 🧾 Notes

- Database and tables are auto-created at runtime.  
- Frontend connects to the backend API to submit data (name, email).  
- Screenshot `running_containers.PNG` shows the containers running successfully.

---

## 🏫 Academic Use

This repository is part of coursework for **DevOps / MLOps Lab**.  
Please do **not** clone, redistribute, or use for production purposes.
