# Real-Time Chat Application – Backend

A real-time chat application backend built with **Node.js, Express.js, MongoDB, and Socket.IO**. This API handles user authentication, real-time messaging, database operations, and communication between connected users.

## Live Demo

[https://chat-app-frontend-gules.vercel.app/](https://chat-app-frontend-gules.vercel.app/)

## Repositories

- **Frontend:** [ChatApp-Frontend](https://github.com/umairamjad2/ChatApp-Frontend)
- **Backend:** [ChatApp-Backend](https://github.com/umairamjad2/ChatApp-Backend)

## Features

### Authentication
- User authentication using JWT.
- Secure login and registration.
- Protected API routes.

### Real-Time Communication
- Real-time messaging using Socket.IO.
- Instant message delivery between connected users.
- Real-time communication between frontend and backend.

### API & Database
- RESTful API development using Express.js.
- MongoDB database integration.
- User and chat data management.
- Structured backend architecture.

### Security
- JWT-based authentication.
- Protected routes and authentication middleware.
- Secure handling of user requests.

## Tech Stack

| Technology | Purpose |
|---|---|
| Node.js | JavaScript runtime |
| Express.js | Backend framework |
| MongoDB | NoSQL database |
| Socket.IO | Real-time communication |
| JWT | Authentication |
| JavaScript | Programming language |

## Architecture

The backend provides REST APIs and real-time communication through Socket.IO.

```text
              React Frontend
                    |
          ----------------------
          |                    |
       REST API             Socket.IO
          |                    |
          ----------------------
                    |
              Node.js Server
               Express.js
                    |
          ----------------------
          |                    |
       MongoDB           JWT Middleware
```

## Getting Started

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- MongoDB (local installation or MongoDB Atlas)
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/umairamjad2/ChatApp-Backend.git

cd ChatApp-Backend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root and configure your database connection, JWT secret, and other required environment variables according to your backend configuration.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Keep your environment variables private and never commit your `.env` file.

### 4. Run the Server

Development mode:

```bash
npm run dev
```

Production mode:

```bash
npm start
```

The server will run on the configured port.

## Project Structure

```text
ChatApp-Backend/
├── controllers/       # Request handling and business logic
├── models/            # MongoDB models
├── routes/            # API routes
├── middleware/        # Authentication middleware
├── config/            # Database configuration
├── server.js          # Server entry point
└── package.json
```

*Note: The structure above is a suggested overview. Adjust it to match the actual repository structure.*

## Frontend Integration

The React frontend communicates with the backend through:

- Axios for HTTP API requests.
- Socket.IO Client for real-time messaging.
- JWT authentication for protected functionality.

## Learning Objectives

This project demonstrates practical experience with:

- Node.js backend development.
- Express.js REST API architecture.
- MongoDB database integration.
- JWT authentication and middleware.
- Real-time communication using Socket.IO.
- Frontend and backend integration.
- Full-stack application development.

## Author

**Umair Amjad**

- GitHub: [@umairamjad2](https://github.com/umairamjad2)

## License

This project is developed for learning and development purposes.
