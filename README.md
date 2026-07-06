# jobTrackerApp
An application for job tracking for personal use  --

📋 Job Tracker App

A full-stack app to track job applications, manage statuses, and visualise your job search — built while actually using it during my own job hunt.

React + Vite
.NET 8
PostgreSQL
Tailwind CSS
🚧 In Progress

🔗 Live Demo: coming soon

✨
Features
✅ Register and login with JWT authentication
✅ Add, edit, delete job applications
✅ Track status — Applied / Interview / Offer / Rejected
✅ Notes per application
✅ Dashboard with status breakdown chart (Recharts)
⬜ Email reminders for upcoming interviews

Move ✅ / ⬜ as you complete each feature

🛠️
Tech Stack
Frontend: React, Vite, Tailwind CSS, Axios, React Hook Form, Recharts
Backend: ASP.NET Core 8, Dapper, ADO.NET, JWT Auth, BCrypt
Database: PostgreSQL
Testing: xUnit (backend unit tests)
DevOps: GitHub Actions CI/CD · Vercel (frontend) · Render (backend + DB)
🚀
Getting Started
# Clone
git clone https://github.com/yourusername/job-tracker
cd job-tracker

# Backend
cd backend
dotnet restore
dotnet run

# Frontend
cd frontend
npm install
npm run dev
🔐
Environment Variables
# Backend
CONNECTION_STRING=your_postgres_connection_string
JWT_SECRET=your_secret_key

# Frontend
VITE_API_URL=http://localhost:5000

Never commit these to GitHub — add to .gitignore

📖
Build Log — What I Learned

Updated as I build each phase. Real learnings, not polished marketing.

Phase 1 — Database Setup
📌 Add your learning here when you complete this phase
Phase 2 — Auth (JWT)
📌 e.g. "Spent 2 hours on CORS — one missing header in middleware config"
Phase 3 — Job CRUD APIs
📌 Add as you go
Phase 4 — React Frontend
📌 Add as you go
Phase 5 — Deployment
📌 Add as you go
🐛
Real Challenges I Hit

This section matters most — it shows you actually built this, not copied a tutorial

📌 Add real bugs and blockers as you hit them
📌 e.g. "JWT token not persisting on page refresh — fixed by storing in httpOnly cookie"
📌 e.g. "Dapper not mapping nullable columns correctly — had to use nullable types in C# model"
🔭
What I'd Do Differently

Fill this after v1 ships — honest reflection is what seniors look for

📌 Add after completion
🗺️
Roadmap
⬜ Email reminders for upcoming interviews
⬜ Export applications to CSV
⬜ Dark mode toggle
👤
Author
Karan Raj
LinkedIn: linkedin.com/in/karanraj45
GitHub: github.com/yourusername
