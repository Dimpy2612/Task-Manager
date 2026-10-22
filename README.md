# Task Manager

A full-stack MERN application to manage daily tasks with user authentication.

## Features

- User registration and login
- Create, view, update, and delete tasks
- JWT-based authentication
- Protected routes
- MongoDB database integration
- React frontend with Redux state management
- Responsive user interface
- Form validation and notifications

## Technologies Used

- **Frontend:** React, JavaScript, Redux, HTML, CSS, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Other Tools:** Axios, React Router, Mongoose, bcrypt, dotenv

## Project Structure

- `frontend/` — React frontend
- `backend/` — Node.js and Express backend
- `package.json` — Root project scripts and dependencies

## Prerequisites

- Node.js and npm
- MongoDB
- Git

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Dimpy2612/Task-Manager.git
   cd Task-manager
   ```

2. Install dependencies:

   ```bash
   npm run install-all
   ```

3. Configure the required environment variables in the appropriate `.env` file. Never upload API keys, passwords, or database credentials.

4. Start the application:

   ```bash
   npm run dev
   ```

5. Open the local frontend URL displayed in Terminal.

## Backend API

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/auth/signup` | Register a user |
| POST | `/api/auth/login` | Log in |
| GET | `/api/tasks` | Retrieve tasks |
| GET | `/api/tasks/:taskId` | Retrieve a specific task |
| POST | `/api/tasks` | Create a task |
| PUT | `/api/tasks/:taskId` | Update a task |
| DELETE | `/api/tasks/:taskId` | Delete a task |
| GET | `/api/profile` | Retrieve the user profile |

## Acknowledgment

This project is based on an existing MERN Task Manager project. Please retain any attribution and license required by the original author.
