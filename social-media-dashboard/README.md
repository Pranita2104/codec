# Social Media Dashboard

A MERN stack social media dashboard with real-time messaging and analytics.

## Features

- User Profiles with Media Uploads
- Real-time Messaging (Socket.IO)
- Like, Comment, Follow
- Redis-powered Notification System
- User Engagement Analytics

## Tech Stack

- MongoDB, Express.js, React.js, Node.js
- Socket.IO for real-time communication
- Redis for notifications

## Getting Started

### Backend

```bash
cd backend
npm install
npm start
```

### Frontend

```bash
cd frontend
npm install
npm start
```

### .env (Backend)

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/social-dashboard
REDIS_URL=redis://localhost:6379
JWT_SECRET=yourSecretKey
```

## License

MIT
