<div align="center">

<img src="https://img.shields.io/badge/EduSense_AI-v4.0.0-6366F1?style=for-the-badge&logo=brain&logoColor=white"/>
<img src="https://img.shields.io/badge/MEGAVERSE_2026-Hackathon-EC4899?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Muthayammal_Engineering_College-AIDS_Dept-A855F7?style=for-the-badge"/>

<br/>
<br/>

# 🧠 EduSense AI
### *Learn Smarter. Score Higher.*

**An elite AI-powered personalized learning platform that detects exactly what you don't know — and builds a roadmap to fix it.**

<br/>

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Site-6366F1?style=for-the-badge)](https://edusense-ai.netlify.app)
[![Built with React](https://img.shields.io/badge/React-18.2-61DAFB?style=flat-square&logo=react)](https://reactjs.org)
[![Powered by Groq](https://img.shields.io/badge/Groq-Llama_3.3_70B-F97316?style=flat-square)](https://groq.com)
[![Firebase](https://img.shields.io/badge/Firebase-Auth_+_Firestore-FFCA28?style=flat-square&logo=firebase)](https://firebase.google.com)
[![Netlify](https://img.shields.io/badge/Netlify-Deployed-00C7B7?style=flat-square&logo=netlify)](https://netlify.com)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Screenshots](#-screenshots)
- [Getting Started](#-getting-started)
- [Firebase Setup](#-firebase-setup)
- [Project Structure](#-project-structure)
- [Team](#-team)
- [Hackathon](#-hackathon)

---

## 🎯 Overview

**EduSense AI** is a next-generation adaptive learning platform built for students who want to study smarter, not harder. Using the power of **Groq's Llama 3.3 70B** (the world's fastest open-source LLM), EduSense AI:

- 🔍 **Pinpoints your exact knowledge gaps** through adaptive quizzes
- 🗺️ **Builds personalized day-wise study plans** tailored to your weaknesses
- 💬 **Provides 24/7 AI tutoring** that explains any concept in any subject
- 📊 **Visualizes your progress** with beautiful, real-time analytics
- 🏆 **Gamifies your learning** with XP, levels, streaks, and badges

> Built in under 48 hours for **MEGAVERSE 2026** by the AIDS Department team at **Muthayammal Engineering College, Rasipuram**.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎯 **Adaptive Quiz Engine** | AI-generated quizzes with timed mode, difficulty levels, and XP rewards |
| 💬 **AI Tutor (24/7)** | Context-aware chat powered by Llama 3.3 70B via Groq API |
| 📅 **Smart Study Planner** | Day-wise AI study plans with progress tracking |
| 🃏 **Flashcard System** | Active recall flashcards with spaced repetition |
| 📊 **Progress Analytics** | Beautiful charts showing performance trends over time |
| 🔬 **Weakness Analysis** | AI-powered root-cause analysis of knowledge gaps |
| 🏆 **Gamification** | XP system, level progression, streaks, and achievement badges |
| 🥇 **Leaderboard** | Compete with peers on a real-time leaderboard |
| 🌙 **Dark / Light Mode** | Full theme switching with persistent preferences |
| 🔐 **Auth System** | Google OAuth + Email/Password via Firebase Auth |
| ☁️ **Cloud Sync** | User profiles and data synced via Firestore |

---

## 🛠️ Tech Stack

```
Frontend        React 18.2 (via Babel standalone, no bundler needed)
UI / Styling    Pure CSS with CSS Variables, Plus Jakarta Sans, JetBrains Mono
Charts          Chart.js 4.4.1
AI Engine       Groq API — Llama 3.3 70B (fastest free LLM)
Auth            Firebase Authentication (Google + Email/Password)
Database        Firebase Firestore
Hosting         Netlify (auto-deploy from GitHub)
```

---

## 🚀 Getting Started

### Option 1 — Open Directly (No Firebase)

1. Download `index.html`
2. Serve locally — do **not** open as `file://` (Firebase won't work)

```bash
# Python
python -m http.server 5500

# Node.js
npx serve .
```

3. Open `http://localhost:5500` in your browser
4. Sign up with email/password
5. Add your **Groq API key** in Settings → AI features activate instantly

> Get a free Groq API key at [console.groq.com/keys](https://console.groq.com/keys) — no credit card needed.

### Option 2 — Deploy to Netlify (Recommended)

1. Fork this repository
2. Go to [netlify.com](https://netlify.com) → **Add new site → Import from GitHub**
3. Select this repo, leave build settings blank, click **Deploy**
4. Done — live in ~30 seconds 🎉

---

## 🔥 Firebase Setup

To enable **Google login** and **cloud sync**, configure Firebase:

1. Go to [console.firebase.google.com](https://console.firebase.google.com)
2. Create a project → **Authentication** → Enable **Google** + **Email/Password**
3. **Firestore Database** → Create in test mode
4. **Project Settings** → Your apps → Web → Copy `firebaseConfig`
5. In `index.html`, find line ~377 and replace:

```js
const FB_CFG = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

6. In Firebase Console → **Authentication → Settings → Authorized domains** → Add your Netlify URL

---

## 📁 Project Structure

```
edusense-ai/
│
├── index.html          # Entire application (single-file React app)
│
└── README.md           # You are here
```

> EduSense AI is intentionally built as a **single HTML file** — zero build tools, zero dependencies to install, instant deployment anywhere.

---

## 👨‍💻 Team

<div align="center">

| Role | Name |
|---|---|
| 👑 **Team Leader** | Prathip M |
| 💻 **Developer** | Sujitha S |
| 🎨 **Designer / Developer** | Rubika Devi P |
| 🔬 **Developer** | Vijanthar MC |

**Department:** Artificial Intelligence & Data Science (AIDS)
**Institution:** Muthayammal Engineering College, Rasipuram

</div>

---

## 🏆 Hackathon

<div align="center">

```
 ███╗   ███╗███████╗ ██████╗  █████╗ ██╗   ██╗███████╗██████╗ ███████╗███████╗
 ████╗ ████║██╔════╝██╔════╝ ██╔══██╗██║   ██║██╔════╝██╔══██╗██╔════╝██╔════╝
 ██╔████╔██║█████╗  ██║  ███╗███████║██║   ██║█████╗  ██████╔╝███████╗█████╗  
 ██║╚██╔╝██║██╔══╝  ██║   ██║██╔══██║╚██╗ ██╔╝██╔══╝  ██╔══██╗╚════██║██╔══╝  
 ██║ ╚═╝ ██║███████╗╚██████╔╝██║  ██║ ╚████╔╝ ███████╗██║  ██║███████║███████╗
 ╚═╝     ╚═╝╚══════╝ ╚═════╝ ╚═╝  ╚═╝  ╚═══╝  ╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝
                                   2 0 2 6
```

**Event:** MEGAVERSE 2026 Hackathon
**Category:** AI / EdTech
**Team:** AIDS Dept · Muthayammal Engineering College

</div>

---

## 📄 License

This project was built for **MEGAVERSE 2026 Hackathon**. All rights reserved by the team.

---

<div align="center">

Made with 💜 by **Team EduSense AI** · AIDS Dept · MEC Rasipuram

*"The best investment you can make is in yourself."* — Warren Buffett

</div>
