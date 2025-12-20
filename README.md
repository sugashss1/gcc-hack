# 🗂️ Multi-Tenant Task & Project Management System

A **role-based, multi-tenant task and project management web application** built using **Flask**, **Google Firestore**, and **Firebase Authentication concepts**.

The platform is designed for **organizational task orchestration**, supporting **CEOs, Managers, and Employees** with secure data isolation, controlled visibility, and centralized oversight.

It includes **Kanban-based task tracking**, **project & goal management**, **analytics dashboards**, and **administrative controls**.

📦 This project uses the **uv Python package manager** for dependency management and execution.

---

## 🚀 Features

- Multi-tenant architecture with tenant-level data isolation  
- Role-based access control (**CEO / Manager / Employee**)  
- **Project → Goal → Task** hierarchy  
- Kanban board for task tracking  
- Admin-level user and project controls  
- Performance analytics with charts  
- Secure backend-enforced authorization  

---

## 🛠 Tech Stack

| Layer        | Technology                          |
|-------------|-------------------------------------|
| Backend     | Flask (Python)                      |
| Database    | Google Firestore                    |
| Auth        | Session-based authentication (password hashing) |
| Frontend    | Jinja2, HTML, CSS, JavaScript       |
| Charts      | Chart.js                            |
| Package Mgmt| uv                                  |

---

## ⚙️ Prerequisites

- Python **3.9+**
- Google Cloud project with **Firestore enabled**
- Firebase service account JSON
- Git

---


## This project uses uv python package manager
```bash
pip install uv
```
this will install uv package

## instruction to run
```bash
git clone https://github.com/sugashss1/gcc-hack
cd gcc-hack
uv sync
uv run app.py
```
You will need a firestore auth json file and a llm key defined inside a .env file like

GOOGLE_APPLICATION_CREDENTIALS=credentials.json

GOOGLE_CLOUD_PROJECT=project_name

llm_api=your_llm_key

## 👥 User Roles & Permissions

### 👑 CEO
- Organization-wide visibility  
- Cross-project analytics & performance insights  

### 🧑‍💼 Manager
- Project & team-level task management  
- Task assignment and progress tracking  

### 👨‍💻 Employee
- Task execution and status updates  
- Kanban-based workflow interaction  


## Tech Stack

Backend: Flask (Python)

Database: Google Firestore

Auth: Session-based (password hashing)

Frontend: Jinja2, HTML, CSS, JavaScript

Charts: Chart.js
