# 🧾 Job Application System

A full-stack job portal to manage job listings, applications, and candidate data. Built with a modular Go backend and a separate frontend for recruiters and applicants.

## 📁 Project Structure

- api_test/ # API integration and unit tests
-  cmd/server/ # Main server entry point for backend
- frontend/ # Frontend app (e.g., React or Vite)
- internal/ # Core internal logic and services
- pkg/utils/ # Shared utility functions
- tmp/ # Temporary files or drafts
- jobportal.db # SQLite database file (local dev)
- .air.toml # Live reload config for Go (Air)
- .gitignore # Git ignored files
- go.mod / go.sum # Go module dependencies


## ✅ Features

- Organization-based job posting system

- Applicant portal to apply and track jobs

- Resume upload and storage integration

- Role-based access for admins and recruiters

- Application status tracking (shortlist, accept, reject)

- Modular Go backend with clean architecture

- API testing setup under api_test/

- React/Vite-based frontend for modern UX



## 🛠 Tech Stack

- **Backend**: Go (with modular structure: `cmd`, `internal`, `pkg`)
- **Frontend**: React / Vite (located in `/frontend`)
- **Database**: SQLite (can be upgraded to PostgreSQL)
- **Dev Tools**: Air for hot reloading the Go server

## 🚀 Running the Project

### Start Backend
```bash
cd cmd/server
air   # or: go run main.go
```

### Start Frontend
```bash
cd frontend
npm install
npm run dev
```



