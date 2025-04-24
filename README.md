# Number Guessing Game

A mobile-friendly number guessing game website with multiple betting options and admin controls.

## Features
kavi's
- Number guessing game with 00-99 table
- Inside number (0-9) and outside number (0-9) betting options
- Admin dashboard for managing points and results
- User point management system with UPI/QR code payment integration
- Multiple market options with different result declaration times
- WhatsApp integration for user support
- Real-time updates and notifications

## Tech Stack

- Frontend: React.js, Material-UI
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT
- Payment Integration: UPI/QR Code

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Create a .env file in the backend directory with the following variables:
   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```

4. Start the development servers:
   ```bash
   # Start backend server
   cd backend
   npm run dev

   # Start frontend server
   cd ../frontend
   npm start
   ```

## Project Structure

```
├── frontend/           # React frontend application
├── backend/            # Node.js backend application
└── README.md          # Project documentation
``` 

REACT_APP_API_URL=http://localhost:5000 