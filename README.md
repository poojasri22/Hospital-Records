# Hospital Patient Records (Flask + SQLite)

A simple, complete CRUD web app to manage Patients, Doctors, and Appointments. Includes search, export to CSV/Excel/PDF, and a small dashboard — ideal for college portfolios.

## Features
- Patients, Doctors, Appointments: Add/View/Delete
- Search with keyword and date range (appointments)
- Export to CSV, Excel, PDF
- Basic Login/Logout
- Dashboard counters

## Tech
- Flask (Python)
- SQLite
- Bootstrap 5
- openpyxl (Excel), reportlab (PDF)

## Setup
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

pip install -r requirements.txt
python app.py
