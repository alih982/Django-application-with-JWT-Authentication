# Django-application-with-JWT-Authentication

# Hybrid MVC & Clean Code Project

## Overview
This project combines **MVC architecture** with **Clean Code principles** to build a maintainable, scalable, and clear web application. It features multiple apps, including `myapp`, `chatapp` (with partial WebSocket), and `otpauth`.

---

## Architecture

### MVC
- **Model:** Database models and ORM
- **View:** Templates and frontend UI
- **Controller:** Request handling, business logic

### Clean Code
- Single Responsibility Principle per module
- Clear, meaningful naming conventions
- Minimal duplication
- Small, focused functions/methods

---

## Features
- User authentication with OTP
- Basic chat functionality (WebSocket partial)
- Modular app design for easy expansion

---

## Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/alih982/Django-application-with-JWT-Authentication
cd test1

Create a virtual environment:
python3 -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

pip install -r requirements.txt
or for python3:
pip3 install -r requirements.txt

Run migrations:

python3 manage.py makemigrations
python3 manage.py migrate

Run the application:

python3 manage.py runserver

project_root/
│
├── myapp/        # Core app (MVC + business logic)
├── chatapp/      # Chat app (WebSocket partial)
├── otpauth/      # OTP Authentication
├── templates/    # HTML templates (Views)
├── static/       # Static files
├── manage.py
└── requirements.txt

Notes:

WebSocket implementation in chatapp is incomplete.

OTP authentication is integrated via otpauth.

Follows MVC for clear separation and Clean Code for maintainability.





