# Medi-trax
MediTracX is a desktop Pharmacy Management System built with Python (PyQt5) and SQLite. It features secure login, real-time inventory tracking, automated billing, and dashboards — designed to streamline pharmacy operations efficiently.

📦 MediTracX – Pharmacy Management System 💊
MediTracX is a modern, desktop-based Pharmacy Management System developed in Python using PyQt5 for the GUI and SQLite as the local database. Designed to automate routine pharmacy operations, it’s ideal for small and medium-sized businesses and also serves as an excellent academic project for students learning full-stack desktop app development.

🛠️ Technologies Used
🧠 Core Technologies:
Python 3.x – Main programming language

PyQt5 – GUI framework for building responsive and native desktop interfaces

SQLite – Lightweight, embedded local database (pharmacy.db)

Qt Designer – For designing GUI layouts visually

Python Standard Libraries – os, sqlite3, datetime, etc.

🧰 Project Structure:
main.py – Entry point of the application

login.py, dashboard.py, etc. – Separated logic for different modules

pharmacy.db – SQLite database file

assets/ – Icons, images, and other static resources

requirements.txt – All dependencies listed for easy setup

✨ Key Features
🔐 Secure Login System

Two roles: Admin and Pharmacist

Role-based access control for menus and features

💊 Medicine Management

Add, edit, and delete medicine records

View detailed stock information

📦 Inventory Tracking

View all medicines in stock

Automatic low-stock alerts

Batch number, expiry date, and pricing included

🧾 Billing System

Generate bills for customers

Real-time calculation of total and discounts

Saves transaction records to the database

📊 Role-Based Dashboards

Admin can manage users, view sales, and inventory

Pharmacist can manage billing and view limited stock data

🔄 Modular Code Structure

Clean and reusable components

Easy to maintain and scale

🛡️ Offline Mode

Fully functional without an internet connection

Data stored locally in SQLite securely

