# Chat App

Features:

- Real-time Messaging powered by Socket.io
- Secure JWT Authentication for user login and signup
- Online User Status Tracking to enhance engagement
- Global State Management using Zustand for smooth UI updates
- Responsive UI designed with TailwindCSS
- RESTful API using Express.js and MongoDB for scalable data storage

Tech Stack:

- Frontend: React, Zustand, TailwindCSS
- Backend: Node.js, Express.js, MongoDB
- Real-time Communication: Socket.io
- Authentication: JWT (JSON Web Token)Installation

### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```
### Start the Application
Backend
```shell
cd backend
npm run dev
```

Frontend
```shell
cd frontend
npm start
```
Open in Browser
Visit http://localhost:5173 to access the chat application.
