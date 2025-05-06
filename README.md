# Fullstack Chat Application

A real-time chat application built with modern web technologies.

## Technologies Used

- **Frontend**:
  - React
  - TypeScript
  - Tailwind CSS
  - Socket.io-client

- **Backend**:
  - Node.js
  - Express
  - MongoDB
  - Socket.io

## Features

- Real-time messaging
- User authentication
- Message history
- Online user status
- Modern and responsive UI

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd fullstack-chat-app
```

2. Install dependencies:
```bash
# Install root dependencies
npm install

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

3. Set up environment variables:
Create a `.env` file in the backend directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the application:
```bash
# Start backend (from backend directory)
npm run dev

# Start frontend (from frontend directory)
npm run dev
```

