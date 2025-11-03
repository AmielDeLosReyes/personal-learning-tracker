# Personal Habit Tracker (Full-Stack)

Lightweight personal habit & journaling app you can build, run and extend.  
Frontend (Angular) + Backend (Spring Boot) + MySQL.  

---

## Quick overview

- **Frontend:** Angular app with dashboard, habit CRUD, journal, and simple charts.  
- **Backend:** Spring Boot REST API with JWT auth, Spring Data JPA, MySQL.  
- **Goal:** Ship an MVP quickly, then add offline sync, reminders, analytics and a monetization tier.

---

## Tech stack

- **Frontend:** Angular, NgRx, TailwindCSS
- **Backend:** Java, Spring Boot, Spring Security (JWT), Spring Data JPA, Spring Scheduler  
- **Database:** MySQL  
- **Optional:** Docker / Docker Compose/ Simple AI service for summaries

---

## Features

- User registration / login (JWT)
- Dashboard with daily habits + progress bar
- CRUD for habits
- Journal entries with notes & tags
- Simple charts (weekly / monthly)
- REST API with standard CRUD endpoints
- PostgreSQL persistence
- CORS and central exception handling

---

# 🧱 2. FEATURE ROADMAP

## Phase 1 — MVP (You can build and use this immediately)

**Frontend:**
- ✅ Register/Login  
- ✅ Dashboard: daily habits + progress bar  
- ✅ Create/Edit/Delete habits  
- ✅ Journal entry with notes/tags  
- ✅ Simple charts (ngx-charts or Chart.js)  

**Backend:**
- ✅ REST API for habits, journal entries, user profile  
- ✅ JWT authentication (login/register)  
- ✅ CRUD endpoints with Spring Data JPA  
- ✅ PostgreSQL persistence  
- ✅ CORS + Exception Handling  

---

## Phase 2 — Smart Habit Tracker

**Frontend:**
- 📆 Calendar view (see completed habits per day)  
- 🧭 NgRx store with:  
  - Auth slice (token, user)  
  - Habits slice (entities)  
  - Journal slice  
- 🧰 Sync state between offline and online  

**Backend:**
- 🕓 Scheduled task to send daily reminder (Spring Scheduler)  
- 📧 Email or push reminder integration  
- 📊 Progress API (aggregate stats per week/month)  

---

## Phase 3 — “Insight” & Monetization Tier

**Frontend:**
- 💡 Analytics tab: streaks, completion rate, focus areas  
- 🔐 Settings page: manage public/private entries  
- 🌐 Share public “learning posts” (via short link)  

**Backend:**
- 📈 Aggregated metrics endpoint  
- 🔒 Premium user flag in DB (simulate subscription)  
- ⚙️ Stripe/PayPal integration (optional)  
- 🤖 Optional AI integration (e.g. “summarize my week”)

---

## Getting started (developer)

### Prerequisites
- Node.js & npm (for Angular)
- Java 17+ (or target used in project)
- Maven or Gradle
- PostgreSQL
- (Optional) Docker & Docker Compose
