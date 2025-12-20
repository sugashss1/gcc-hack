## Multi-Tenant Task & Project Management System

A role-based task and project management web application built with Flask, Google Firestore, and Firebase Authentication concepts.
The system supports CEOs, Managers, and Employees, providing Kanban task tracking, project management, and admin controls.

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

## Tech Stack

Backend: Flask (Python)

Database: Google Firestore

Auth: Session-based (password hashing)

Frontend: Jinja2, HTML, CSS, JavaScript, tailwind

Charts: Chart.js
