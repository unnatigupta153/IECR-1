# IECR — Indian Entertainment Content Recommendation System

A full-stack web application that helps users discover top-rated Indian movies and web series through a dynamic, IMDb-based content filtering and recommendation engine, along with an admin panel for real-time content management.

## Features

- 🎬 Browse and discover Indian movies and web series
- ⭐ Dynamic filtering based on IMDb ratings and other metadata (genre, language, year, etc.)
- 🔍 Search functionality for quick content lookup
- 🛠️ Admin panel to add, update, and manage content in real time
- 📱 Fully responsive UI across devices
- 🔐 Secure authentication for user and admin roles

## Tech Stack

**Frontend:** React.js, HTML5, CSS3, JavaScript (ES6+), Tailwind CSS
**Backend:** Node.js, Express.js
**Database:** MongoDB (MongoDB Atlas)
**Other Tools:** Git & GitHub, Postman (API testing), Vercel (deployment)

## Project Structure
IECR/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page-level components
│   │   ├── context/        # Global state (if any)
│   │   └── App.jsx
│   └── package.json
├── server/                  # Node/Express backend
│   ├── models/              # Mongoose schemas
│   ├── routes/               # API routes
│   ├── controllers/          # Route logic
│   ├── config/                # DB connection, env config
│   └── server.js
├── .env.example
└── README.md
## Getting Started

### Prerequisites

- Node.js (v16 or later)
- MongoDB Atlas account (or local MongoDB instance)
- npm or yarn

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/unnatigupta153/IECR.git
   cd IECR
   
