HireVai

HireVai is a full-stack Job Portal built with a React frontend and a Node.js + Express backend.

It supports two roles – Candidates and Recruiters – and covers the full hiring flow: posting jobs, applying, managing applications, and tracking results in a modern, responsive UI.

✨ Features
👨‍💼 Candidate

Register / login with secure authentication

Complete and update candidate profile

Browse and search jobs with filters

View detailed job descriptions

Apply to jobs directly

View all applications in a dedicated Applications page

Saved Jobs functionality

Recommended Jobs based on profile

🧑‍💻 Recruiter

Register / login

Update recruiter & company profile

Post, update, delete jobs

Manage posted jobs

View applicants for each job

Recruiter Dashboard for quick statistics

🌐 General

Modern, responsive UI

REST API architecture

Role-based access

Clean frontend-backend separation

🏗️ Tech Stack
Frontend

React

React Router

Axios

Modern CSS

Backend

Node.js

Express

JavaScript

MongoDB / PostgreSQL (or your DB)

CORS support

📁 Project Structure
HireVai/
├── backend/
│   └── jobportal/
│       ├── server.js / app.js
│       ├── routes/
│       ├── controllers/
│       ├── models/
│       ├── middleware/
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

API permission middleware in backend

JWT / session-based authentication

📜 Useful Scripts
Backend
npm install
npm start

Frontend
npm install
npm start
# or if using Vite
npm run dev
npm run build

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/surajharogoppa/HireVai.git
cd HireVai

2️⃣ Start the Backend (Node.js)
cd backend/jobportal
npm install


Create a .env file inside backend:

PORT=5000
DB_URI=<your_database_connection_string>
JWT_SECRET=<your_secret_key>


Start the backend server:

npm start


Backend runs at: http://localhost:5000/

3️⃣ Start the Frontend (React)

Open a new terminal:

cd frontend/jobportal
npm install
npm start   # or `npm run dev` if using Vite


Frontend runs at: http://localhost:3000/

✔️ Project is Running!
You now have full access to Candidate features, Recruiter features, Job Posting, Applications, and Dashboards.

🤝 Contributing

Fork the repository

Create a new branch

Commit changes

Push and create a PR

📄 License

No license provided yet — all rights reserved.

✉️ Contact

For any queries, open an issue on GitHub or contact surajharogoppa@gmail.com
