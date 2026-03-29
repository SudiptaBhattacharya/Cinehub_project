# 🎬 CineHub – Movie Discovery & Recommendation Platform

## Overview
CineHub is a full-stack web application that allows users to discover, track, and manage movies and TV shows with personalised recommendations and social features.

## Contributors
- Galloni
- Ahnaf
- Pahul
- Sudipta(ME)

## 🚀 Features
- 🔍 Real-time movie & TV search using TMDB API
- 👤 User authentication (Email + Google/Facebook OAuth)
- 📚 Personal library to save and manage content
- 🧠 AI-powered recommendations (planned)
- 🌓 Dark mode toggle & responsive UI
- 👥 User profiles and activity tracking

## 🛠️ Tech Stack
- Frontend: Vue.js, HTML, CSS
- Backend: Node.js, Express
- Database: MySQL
- APIs: TMDB API
- Auth: Passport.js, OAuth
- Tools: Axios, dotenv

## 🧠 Architecture
- Modular Vue components (Home, Profile, Info pages)
- REST API backend for handling user data and external API calls
- Server-side proxy for external APIs to handle CORS securely
- Relational database with structured schema (users, reviews, tags)

## ⚙️ Key Challenges & Solutions
- ❌ CORS issues when calling TMDB API  
  ✅ Solved by routing requests through backend server  
- ❌ Session persistence issues on reload  
  ✅ Improved session handling with Express-session  
- ❌ Merge conflicts in team development  
  ✅ Standardised structure and modular components  

## ▶️ Run Locally
```bash
npm install
npm run dev
