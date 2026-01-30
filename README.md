# Minimal workout planner webapp

A mobile-friendly, offline-first workout planning web app with calendar-based scheduling, local data storage, and completion tracking.  
Designed as a Progressive Web App (PWA) and optimized for smartphone usage.

---

## ✨ Features

- 📅 **Calendar-based workout planning** (monthly view)
- 🏋️ **Create reusable workouts** with notes
- 🔁 **Recurring schedules** via weekdays (e.g. Mon/Wed/Fri)
- 📌 **One-time scheduling** for specific dates
- ✅ **Mark workouts as completed** per day
- 💾 **Offline-first** — all data stored locally on the device
- 📱 **Mobile-first UI**, installable as a PWA
- 🚫 **No backend, no account, no tracking**

---

## 🧠 Concept

This app follows an **offline-first** approach:

- All workout data is stored locally in the browser (IndexedDB / local storage)
- No server, no login, no cloud dependency
- Ideal for personal use, privacy-focused workflows, or as a base for further extensions

The app is intentionally kept **simple and transparent**, focusing on planning and consistency rather than social features or gamification.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** (mobile-first, responsive layout)
- **Vanilla JavaScript**
- **Progressive Web App (PWA) concepts**
  - Service Worker (optional / planned)
  - Offline support
  - Installable on Android

---

## 📦 Data Storage

- Stored **locally on the device** using browser storage
- Data is scoped per browser and domain
- No automatic sync between devices
- Optional manual export/import via JSON (planned)

---

## 🚀 Getting Started

### Run locally
1. Clone the repository
2. Open `index.html` in a modern browser  
   *(or host it on any static web server)*

```bash
git clone https://github.com/your-username/offline-workout-planner.git
cd offline-workout-planner
