# Connect 4 Online

A real-time two-player online Connect 4 game built with modern web technologies. This application allows players to compete live with matchmaking, authentication, and seamless gameplay experience.

---

## Features

-  User Authentication (Signup/Login)
-  Real-time Multiplayer Gameplay using Socket.IO
-  Matchmaking System
-  Automatic Win Detection (6×7 board)
-  Score Tracking System
-  Disconnection Handling & Reconnection Support
- Responsive UI (4 Pages)
  - Player Dashboard
  - Game Room
  - Match Setup (Duration Selection)
  - Result/Score View

---

## Tech Stack

### Frontend
- TypeScript
- React.js

### Backend
- Node.js
- Express.js
- Socket.IO

### Database
- MongoDB

### Tools
- Docker
- Visual Studio Code

---

## System Design Overview

- Client connects to server via WebSockets (Socket.IO)
- Server manages:
  - Player matchmaking
  - Game state synchronization
  - Win detection logic
- MongoDB stores:
  - User data
  - Match history
  - Scores

---

## Installation & Setup

### Clone the repository
```bash
git clone https://github.com/your-username/connect4-online.git
cd connect4-online
