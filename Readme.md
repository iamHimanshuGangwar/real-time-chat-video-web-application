# Real-time Chat and Video Calling

A full-stack web application for real-time chat and video calling, built with a modern tech stack.

## Features
- Real-time 1:1 and group chat
- Video and audio calling
- User authentication (sign up, login, logout)
- Friend requests and notifications
- Responsive and modern UI
- Theme selection (light/dark)

## Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- WebSocket (for real-time communication)

### Frontend
- React.js (Vite)
- Tailwind CSS
- Axios

## Project Structure

```
/Real-time-Chat-and-vedio-calling-
├── backend
│   ├── src
│   │   ├── controllers
│   │   ├── lib
│   │   ├── middleware
│   │   ├── models
│   │   └── routes
│   └── package.json
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── constants
│   │   ├── hooks
│   │   ├── lib
│   │   ├── pages
│   │   └── store
│   ├── public
│   └── package.json
└── Readme.md
```

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm
- MongoDB (local or cloud)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/iamHimanshuGangwar/Real-time-Chat-and-vedio-calling-.git
   cd Real-time-Chat-and-vedio-calling-
   ```

2. **Install backend dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies:**
   ```bash
   cd ../frontend
   npm install
   ```

### Running the Application

1. **Start the backend server:**
   ```bash
   cd backend
   npm start
   ```

2. **Start the frontend app:**
   ```bash
   cd frontend
   npm run dev
   ```

3. **Open your browser:**
   Visit `http://localhost:5173` (or the port shown in your terminal)

## Screenshots

![Screenshot](frontend/public/screenshot-for-readme.png)

## License

This project is licensed under the MIT License.
