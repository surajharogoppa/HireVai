🚀 HireVai

HireVai is a full-stack Job Portal built to connect Candidates and Recruiters through a seamless hiring workflow.
It covers the entire recruitment lifecycle — from posting jobs and applying, to managing applications and assessments — with a modern, responsive UI.

✨ Features
👨‍💼 Candidate

Register / Login with secure authentication

Create and update candidate profile

Browse and search jobs with filters

View detailed job descriptions

Apply to jobs directly

View applied jobs in a dedicated Applications page

Save jobs for later

Recommended jobs based on profile

MCQ Test System per application

Test generated after applying

30-minute countdown timer

Tab-switch & refresh restrictions

Auto-submit on time completion

Scores visible to recruiters

🧑‍💻 Recruiter

Register / Login

Update recruiter & company profile

Post, update, and delete jobs

Manage posted jobs

View applicants for each job

View candidate test results

Recruiter dashboard with quick statistics

🌐 General

Modern and clean UI

Fully responsive design

REST API architecture

Role-based access control

Clean frontend–backend separation

🏗️ Tech Stack
Frontend

React

React Router

Axios

Modern CSS / UI styling

Backend

Django

Django REST Framework

Python

SQLite / PostgreSQL

CORS support

📁 Project Structure
HireVai/
├── backend/
│   └── jobportal/
│       ├── manage.py
│       ├── jobportal/
│       ├── accounts/
│       ├── jobs/
│       ├── applications/
│       ├── tests/
│       └── ...
└── frontend/
    ├── public/
    └── src/
        ├── api/
        ├── components/
        ├── pages/
        ├── context/
        ├── App.jsx
        └── main.jsx

🔐 Authentication & Roles

Candidate and Recruiter accounts

Role-specific dashboards and routes

API permission classes in backend

Token / session-based authentication

🧪 Candidate Test Flow

Candidate applies for a job

Application is created

Test becomes available in Applications page

30-minute countdown starts

Auto-submit on timeout with restrictions

Score visible to recruiters

📜 Useful Scripts
Backend
python manage.py runserver
python manage.py makemigrations
python manage.py migrate
python manage.py test

Frontend
npm install
npm run dev    # Vite
npm start      # CRA
npm run build

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/surajharogoppa/HireVai.git
cd HireVai

2️⃣ Start the Backend (Django)
cd backend
python -m venv venv


Activate virtual environment:

Windows

venv\Scripts\activate


Mac/Linux

source venv/bin/activate


Install dependencies:

pip install -r requirements.txt


Create .env file inside backend/:

SECRET_KEY=your_secret_key_here
DEBUG=True
ALLOWED_HOSTS=127.0.0.1,localhost
FRONTEND_URL=http://localhost:5173
DATABASE_URL=sqlite:///db.sqlite3


Apply migrations:

python manage.py migrate


(Optional) Create superuser:

python manage.py createsuperuser


Run backend server:

python manage.py runserver


Backend runs at:

http://127.0.0.1:8000/

3️⃣ Start the Frontend (React)

Open a new terminal:

cd frontend
npm install


Run frontend:

Vite

npm run dev


CRA

npm start


Frontend runs at:

http://localhost:5173

✅ Project is Running!

Frontend: http://localhost:5173

Backend API: http://127.0.0.1:8000

You now have full access to:

Candidate features

Recruiter features

Job posting

Applications

MCQ tests

Dashboards

🤝 Contributing

Fork the repository

Create a new branch

Commit your changes

Push and open a Pull Request

📄 License

No license provided yet — all rights reserved.

✉️ Contact

Suraj Harogoppa
GitHub: https://github.com/surajharogoppa
Email: surajharogoppa@gmail.com

For queries, open an issue or contact via GitHub.
