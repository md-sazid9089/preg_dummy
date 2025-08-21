# Pregnancy Companion Web App

This project now has separate folders for the frontend and a beginner-level backend.

- **frontend/** – React + Vite application.
- **backend/** – Node.js server with MongoDB Atlas connection.

## Getting Started

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
npm install
# replace the placeholder in index.js with your MongoDB Atlas connection string
npm start
```
The backend connects to MongoDB Atlas and listens on port 3000, responding with a greeting at the root URL.
