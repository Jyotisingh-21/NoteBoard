# 📝 NoteBoard

A full-featured note-making web app built with the MERN stack. Create, view, and manage personal notes — all backed by MongoDB and styled with TailwindCSS and DaisyUI.

## 🚀 Live Demo

[![Deploy](https://img.shields.io/badge/deployed-render-blue)](https://noteboard-rqr3.onrender.com/)

## ✨ Features

- 📌 Create and store notes with title + content
- ⚡ Real-time form validation and loading feedback
- 🔐 Backend rate-limiting with Upstash Redis
- 📁 Responsive UI powered by TailwindCSS + DaisyUI
- 🚨 Graceful error handling with toast notifications
- 🌐 Full-stack routing with React Router and Express
- 🔄 Auto-reload on successful note creation

## 🛠️ Tech Stack

| Layer      | Tools/Libs                               |
|------------|------------------------------------------|
| Frontend   | React, React Router DOM, TailwindCSS, DaisyUI, Axios, React Hot Toast |
| Backend    | Express.js, Mongoose, Upstash Redis      |
| Database   | MongoDB Atlas                            |
| Deployment | Render / GitHub                          |

## 📦 Installation

# Clone the repo
git clone https://github.com/Jyotisingh-21/NoteBoard.git

🧩 Project Structure
Project-1/
├── mernBackend/
│   └── src/
│       └── routes/
│       └── middleware/
│       └── controllers/
├── mernFrontend/
│   └── src/
│       └── pages/
│       └── components/
│       └── lib/

🛡️ Rate Limiting
Powered by Upstash Redis using a sliding window algorithm. Limits excessive POST requests to prevent spam creation.

🧠 Author
Jyoti Singh GitHub
