# Team Task Manager Backend

A full-stack Team Task Manager backend built with Node.js, Express, MongoDB, and JWT Authentication.

---

## Features

- User Registration & Login
- JWT Authentication
- Role-Based Access Control (Admin / Member)
- Project Management
- Task Management
- Protected REST APIs
- MongoDB Database Integration
- Railway Deployment

---

## Tech Stack

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT
- Railway

---

## Folder Structure

```bash
src/
│
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
└── server.js
```

---

## API Endpoints

### Auth Routes

#### Register User

```http
POST /api/auth/register
```

#### Login User

```http
POST /api/auth/login
```

---

### Project Routes

#### Get Projects

```http
GET /api/projects
```

#### Create Project

```http
POST /api/projects
```

---

### Task Routes

#### Get Tasks

```http
GET /api/tasks
```

#### Create Task

```http
POST /api/tasks
```

---

## Installation

### Clone Repository

```bash
git clone YOUR_GITHUB_BACKEND_REPO
```

### Install Dependencies

```bash
npm install
```

### Create Environment Variables

Create `.env`

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

### Run Server

```bash
npm run dev
```

---

## Deployment

Backend deployed on Railway.

---

## Author

Rizwan