📅 Shift Scheduling Reminder App

A web-based Shift Scheduling Reminder system built using Flask, MongoDB, HTML/CSS, and automated scheduling via GitHub Actions.
It helps teams/operators stay updated with upcoming shifts by automatically sending reminder emails.

🚀 Features

✔️ User-friendly interface for uploading/managing shift schedules

✔️ Stores data in MongoDB

✔️ Automated email reminders (via scheduling)

✔️ GitHub Actions triggers daily schedule checks

✔️ Secure credential management via GitHub Secrets

✔️ Flask-based backend API & UI

🛠️ Tech Stack
Component	Technology
Backend	Flask (Python)
Database	MongoDB
Frontend	HTML, CSS, JS
Email Service	SMTP / yagmail 

Install dependencies
pip install -r requirements.txt

Setup environment variables
MONGO_URI=your_mongodb_connection_link
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password_or_app_password

MongoDB Setup

Create a cluster in MongoDB Atlas

Whitelist IP (0.0.0.0/0 or server IP)

Create DB & collection for schedules

Add Mongo URI to GitHub Secrets
