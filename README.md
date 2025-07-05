# 🛒 E-Commerce Website

A full-stack e-commerce web application built using Django. It includes essential features like user authentication, product listings, a shopping cart, and payment gateway integration.

## 🚀 Features

- User registration & login
- Product catalog with search
- Shopping cart functionality
- Order placement and checkout flow
- Admin panel for managing inventory
- MySQL backend database

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS (basic)
- **Database:** MySQL
- **Tools:** VS Code, Git, GitHub, Postman

## 🔧 Setup Instructions

> ⚠️ *This was a college project built and tested locally. Source code is currently not uploaded.*

1. Clone the repository (once code is uploaded):
   ```bash
   git clone https://github.com/bhagyalaxmithakre/ecommerce-django.git

2.Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # or use `env\\Scripts\\activate` on Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4.Run database migrations and start the server:
  ```bash
  python manage.py migrate
  python manage.py runserver
  ```
