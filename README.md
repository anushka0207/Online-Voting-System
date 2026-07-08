# Online Voting System
Website --> https://online-voting-w306.onrender.com

A secure, web-based voting platform that allows users to cast votes digitally, with an admin dashboard for managing elections and viewing results in real time.

## Features
- User authentication for secure voter login
- Real-time vote counting with dynamic charts
- Admin dashboard to manage candidates/elections and monitor results

## Tech Stack
- **Backend:** Python, Flask
- **Database:** SQLite
- **Frontend:** HTML, CSS, Bootstrap
- **Visualization:** Chart.js (Pie and Line Charts)
- **Security:** Session management, CAPTCHA authentication
- **Version Control:** Git & GitHub

## How It Works
1. Users register/log in through a secure authentication system.
2. Once logged in, users can view candidates and cast their vote.
3. Votes are stored in an SQLite database and tallied in real time.
4. Admins can log in to a separate dashboard to view live results, manage candidates, and oversee the election process.

# Setup & Installation

Clone the repository

git clone https://github.com/anushka0207/Online-Voting-System.git

cd Online-Voting-System

Install dependencies

pip install -r requirements.txt

Run the application
python app.py

Then open `http://localhost:5000` in your browser.

Future Improvements

Adding facial recognition or OTP-based verification, deploy on cloud, add blockchain-based vote integrity
