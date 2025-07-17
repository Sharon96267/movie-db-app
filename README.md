
# 🎬 Movie Database App by Sharon_Akhilome

## Overview
A full-stack movie database web application that allows users to:
- Browse and search movies
- Add new movies with details
- Rate movies (1–5 stars)
- Register and log in (JWT-based auth)
- View poster images via OMDB API

## Tech Stack
- **Frontend:** Angular
- **Backend:** Node.js + Express
- **Database:** MySQL
- **External API:** OMDB for poster images
- **Authentication:** JWT

## How to Run

### 1. MySQL Setup
- Import the `schema.sql` into your MySQL database
- Create a database named `moviedb`

### 2. Backend
```bash
cd backend
npm install
node server.js
```

### 3. Frontend
```bash
cd frontend
npm install
ng serve
```

Visit `http://localhost:4200` to run the app.

## GitHub Upload
```bash
cd movie-db-app
git init
git remote add origin https://github.com/YOUR_USERNAME/movie-db-app.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.
