# Personal-Portfolio-Tracker


# 🧑‍💼 Personal Portfolio Tracker

A full-stack web application to manage and track personal portfolios — including profile information, project history, and activity charts.

## 🔥 Features

- 🧾 User Authentication (Register/Login)
- 📄 Manage Personal Profile (Image, DOB, Email, Phone)
- 📊 Dashboard with Charts & Metrics
- 📁 Project Portfolio Management
- 🖼️ Profile Image Upload
- 🛡️ JWT-based Secure APIs (Backend)

---

## 🛠️ Tech Stack

| Layer       | Technology                       |
|-------------|----------------------------------|
| **Frontend** | Angular 15, HTML, SCSS, TypeScript |
| **Backend**  | NestJS, TypeORM, PostgreSQL, JWT |
| **Database** | PostgreSQL                       |
| **Deployment** | GitHub (code), Render/Vercel/Netlify (hosting) |

---

# backend/.env
DATABASE_URL=postgres://postgres:postgres@localhost:5432/postgres
JWT_SECRET=your-super-secret
JWT_EXPIRES_IN=1d

cd backend
npm install
npm run start:dev

cd frontend
npm install
ng serve


📮 API Endpoints (NestJS)


POST /auth/register

POST /auth/login

GET /users/me (secured)


