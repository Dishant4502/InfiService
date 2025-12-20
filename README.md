InfiService

InfiService is a full-stack **Design, Consultancy & Marketing Service Platform** built using the **MERN stack**.  
The platform allows users to explore services, view projects and clients, submit contact forms, and subscribe to newsletters, while admins can manage content through an admin panel.

---
Live Demo
- **Frontend:** https://infiservice-2.onrender.com  
- **Backend:** https://infiservice-1.onrender.com  

---

Tech Stack

Frontend
- React.js (Vite)
- Axios
- React Router
- CSS / Custom UI Components

Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- dotenv
- CORS



Features

User Features
- View company services
- Browse projects & clients
- Submit contact form
- Subscribe to newsletter
- Responsive modern UI

Admin Features
- Add / view projects
- Add / view clients
- View contact form submissions
- Manage subscribers
- Image upload using Base64



Project Structure

InfiService/
│
├── client/ # React frontend (Vite)
│ ├── src/
│ ├── public/
│ └── dist/
│
├── server/ # Node + Express backend
│ ├── models.js
│ ├── routes.js
│ ├── index.js
│ └── .env
│
└── README.md

Environment Variables

Backend (`server/.env`)
MONGO_URI=your_mongodb_atlas_connection_string
PORT=5000
Backend =https://infiservice-1.onrender.com

Getting Started (Local Setup)

Clone Repository
git clone https://github.com/Dishant4502/InfiService.git
cd InfiService

Backend Setup
cd server
npm install
npm start

Backend runs on:
http://localhost:5000

Frontend Setup
cd client
npm install
npm run dev

Frontend runs on:
http://localhost:5173


API Endpoints
Projects
GET /api/projects

POST /api/projects

Clients
GET /api/clients

POST /api/clients

Contact
POST /api/contact

GET /api/contacts

Subscribers
POST /api/subscribe

GET /api/subscribers

Deployment
Frontend: Render (Static Site)

Backend: Render (Web Service)

Database: MongoDB Atlas

Author
Dishant Patil
Computer Science Engineering Student
Full Stack Developer (MERN)