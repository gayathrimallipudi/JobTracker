# 🧭 Job Tracker

A Flask-based web application to help job seekers manage, track, and analyze their job applications with ease.


## 🚀 Live Demo
🔗 [https://jobtracker-8kmt.onrender.com/](https://jobtracker-8kmt.onrender.com/) *(hosted on Render)*


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


## ⚙️ Getting Started (Local Setup)

```bash
# 1. Clone the repo
git clone https://github.com/gayathrimallipudi/JobTracker.git
cd JobTracker

# 2. Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. (Optional) Delete old DB if exists
rm jobs.db

# 5. Run the DB setup script
python3 creating_db_with_tables.py

# 6. Start the Flask app
python3 app.py

