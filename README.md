# Lumina Instant Messaging 💬 -> Android

A fast, lightweight real-time chat application built with a **Go** backend, a **Next.js (React)** frontend, and **PostgreSQL + Redis** for reliable data storage and instant message delivery.

---

## ✨ Features

- ⚡ **Instant Messaging:** Real-time 1-on-1 and group chat using WebSockets.
- 🟢 **Live Status:** Real-time online/offline presence tracking powered by Redis.
- 💾 **Chat History:** Stores user messages and timestamps safely in PostgreSQL.
- 🔒 **User Authentication:** Secure signup and login with JWT.
- 📱 **Responsive UI:** Clean, modern interface that works on both mobile and desktop.
- 🐳 **Docker Ready:** One command to run the whole app locally with Docker Compose.

---

## 🛠️ Tech Stack

- **Frontend:** Next.js, React, TypeScript, Tailwind CSS
- **Backend:** Go (Golang), Gorilla WebSockets
- **Database:** PostgreSQL (chat history & user data)
- **Cache & Presence:** Redis
- **DevOps:** Docker, Docker Compose

---

## 🚀 Quick Start (Using Docker)

The easiest way to run the whole project locally is with Docker:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/lumina-messaging.git](https://github.com/your-username/lumina-messaging.git)
   cd lumina-instant-android
