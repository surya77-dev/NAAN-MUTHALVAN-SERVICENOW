NAAN-MUDHALVAN Smart Interns Project
🎯 Project Overview

This project is developed as part of the NAAN MUDHALVAN initiative, aiming to give interns hands-on experience in building a real-world full-stack application. The “Smart Interns” system enables students and interns to register, select projects, submit deliverables, and track progress, while mentors/admins can monitor, evaluate and offer feedback.

🧩 Features

User roles: Student Intern, Mentor/Reviewer, Admin

Intern registration & login

Project listing & selection by interns

Submission of project deliverables (e.g., code, report, video)

Mentor review panel with status updates (Pending → In Review → Approved/Rejected)

Dashboard views for each role (intern sees own projects; mentor sees assigned interns; admin sees overview)

Notifications & email/status updates for key events (project selected, submission reviewed)

Analytics for admins: number of interns, projects, approvals, rejections

🛠 Technologies Used

Frontend: React (or Angular/Vue) with HTML, CSS, JavaScript

Backend: Node.js + Express (or Python Django/Flask)

Database: MongoDB (or PostgreSQL/MySQL)

Authentication & Authorization: JWT / OAuth2

Deployment / DevOps: Docker, CI/CD pipeline (optional)

Misc: Nodemailer for emails, Multer for file uploads, Charts library for analytics

📁 Project Structure
/client                # frontend application
  /src
    /components
    /pages
    /assets
    App.jsx
    index.js
/backend               # backend application
  /controllers
  /models
  /routes
  app.js
  .env
README.md

🚀 Getting Started
Prerequisites

Node.js (v14+) and npm

MongoDB or other chosen database

Git

Installation

Clone this repository:

git clone https://github.com/athinathan11/NAAN-MUDHALVAN-smart-interns-.git
cd NAAN-MUDHALVAN-smart-interns-


Setup environment variables:

In /backend/.env, define DB_URI, JWT_SECRET, EMAIL_USER, EMAIL_PASS, etc.

Install dependencies:

# Backend
cd backend
npm install  

# Frontend
cd ../client
npm install


Start the development servers:

# Backend
cd backend
npm run dev   # or `node app.js`  

# Frontend
cd ../client
npm start     # opens app at http://localhost:3000  


Open browser at http://localhost:3000
 and use the application.

✅ Usage

As Intern: Signup → Browse Projects → Apply/Select → Submit Deliverables → View Feedback

As Mentor: Login → View Assigned Interns → Review Submissions → Provide Feedback & Update Status

As Admin: Dashboard → Manage Users & Projects → View Analytics → Export Reports

🧪 Testing

Unit tests for backend routes (Jest/Mocha)

Frontend component tests (React-Testing-Library)

End-to-end tests (Cypress/Selenium)

🔧 Deployment

Build frontend: npm run build

Dockerize backend and frontend

Deploy to cloud provider (AWS/GCP/Heroku)

Setup environment variables in production

Use HTTPS, SSL certs, and auto-scaling (optional)

📌 Contributions

Contributions are welcome!

Fork the repository.

Create a feature branch: git checkout -b feature/YourFeature

Commit your changes: git commit -m 'Add new feature X'

Push to branch: git push origin feature/YourFeature

Open a Pull Request and describe your change.

📝 License

This project is licensed under the MIT License. See the LICENSE file for details.
