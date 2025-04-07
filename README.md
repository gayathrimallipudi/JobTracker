# 🧭 Job Tracker

A Flask-based web application to help job seekers manage, track, and analyze their job applications with ease.


## 🚀 Live Demo
🔗 [https://jobtracker-i9df.onrender.com/](https://jobtracker-i9df.onrender.com/) *(hosted on Render)*


## 📌 Features

- 📝 **User Authentication** – Sign up and log in securely
- 📋 **Job Management** – Add, view, and update job applications
- 📊 **Stats Dashboard** – Visual insights into application status and job sources
- 🧰 **Resume & Interview Resources** – Quick access to resume tips and interview prep
- 🔐 **Secure Passwords** – Passwords are hashed using Flask-Bcrypt


## 🛠 Technologies Used

- **Backend**: Python, Flask, Flask-WTF, Flask-Login, Flask-Bcrypt
- **Frontend**: HTML, CSS
- **Database**: SQLite
- **Hosting**: Render.com
- **Containerization**: Docker


## ⚙️ Getting Started (Local Setup)
**1. Clone the repo**
- git clone https://github.com/gayathrimallipudi/JobTracker.git
- cd JobTracker

**2. Build the Docker image**
- docker build -t jobtracker-app .

**3. Run the container**
- docker run -p 5000:5000 jobtracker-app

