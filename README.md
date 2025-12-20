# HireVai 🚀

HireVai is a **full-stack Job Portal application** built with a **React frontend** and a **Python Backend**. It supports two primary roles — **Candidates** and **Recruiters** — and enables an end-to-end hiring workflow including job posting, job applications, applicant management, and dashboards, all wrapped in a modern and responsive UI.

---

## ✨ Features

### 👨‍💼 Candidate Features
- Secure registration and login  
- Create, view, and update candidate profile  
- Browse and search jobs with filters  
- View detailed job descriptions  
- Apply to jobs directly  
- Track applied jobs in a dedicated **Applications** page  
- Save jobs for later  
- Get **Recommended Jobs** based on profile  

### 🧑‍💻 Recruiter Features
- Secure recruiter registration and login  
- Create and update recruiter/company profile  
- Post new jobs  
- Edit and delete existing job postings  
- Manage all posted jobs  
- View applicants for each job  
- Recruiter Dashboard with quick statistics  

### 🌐 General Features
- Modern and responsive UI  
- RESTful API architecture  
- Role-based access control  
- Clean separation of frontend and backend  

---

## 🏗️ Tech Stack

### Frontend
- React  
- React Router   
- Tailwind CSS  

### Backend
- Python    
- MongoDB / PostgreSQL  

---

## 📁 Project Structure

```text
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
    └── jobportal/
        ├── public/
        └── src/
            ├── api/
            ├── components/
            ├── pages/
            ├── context/
            ├── App.jsx
            └── main.jsx
```

---

## 🔐 Authentication & Roles
- Separate **Candidate** and **Recruiter** accounts  
- Role-specific dashboards and protected routes  
- JWT-based authentication  
- Backend permission middleware for APIs  

---

## 📜 Useful Scripts

### Backend
```bash
npm install
npm start
```

### Frontend
```bash
npm install
npm start      # or `npm run dev` if using Vite
npm run build
```

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/surajharogoppa/HireVai.git
cd HireVai
```

### 2️⃣ Start the Backend (Node.js)
```bash
cd backend/jobportal
npm install
```

Create a `.env` file inside `backend/jobportal`:

```env
PORT=5000
DB_URI=<your_database_connection_string>
JWT_SECRET=<your_secret_key>
```

Start the backend server:
```bash
npm start
```

Backend runs at:
```
http://localhost:5000/
```

---

### 3️⃣ Start the Frontend (React)
Open a new terminal:

```bash
cd frontend/jobportal
npm install
npm start      # or `npm run dev` if using Vite
```

Frontend runs at:
```
http://localhost:3000/
```

---

## ✔️ Project Status
The project is fully running with:
- Candidate workflows  
- Recruiter workflows  
- Job posting & applications  
- Dashboards  


---

## 📄 License
This project currently has **no license** — all rights reserved.

---

## ✉️ Contact
- **GitHub:** https://github.com/surajharogoppa  
- **Email:** surajharogoppa@gmail.com  
