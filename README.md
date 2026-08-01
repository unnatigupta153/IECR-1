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
   2. Install dependencies for both client and server
 cd client && npm install
cd ../server && npm install
3.Set up environment variables
Create a .env file inside the server/ folder:
MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
4.Run the app
Start the backend:
cd server
npm start
Start the frontend (in a separate terminal):
cd client
npm start
5.Open http://localhost:3000 in your browser.
API Overview
Method
Endpoint
Description
GET
/api/content
Fetch all content
GET
/api/content/:id
Fetch single content by ID
POST
/api/content
Add new content (admin only)
PUT
/api/content/:id
Update content (admin only)
DELETE
/api/content/:id
Delete content (admin only)
Future Improvements
Personalized recommendations based on user watch history
User reviews and ratings
Integration with a live IMDb/TMDB API for real-time data sync
Author

Unnati Gupta
GitHub: @unnatigupta153
LinkedIn: Unnati Gupta
License
This project is open source and available under the MIT License.
Remember to update the API routes, folder names, and env variable names if they differ from your actual code.
