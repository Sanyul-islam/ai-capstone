# MERN AI Capstone

A full-stack web application built with the MERN stack and AI-assisted development.

## Tech Stack

- React
- Node.js
- Express.js
- MongoDB
- JavaScript
- Git & GitHub

## Project Goals

- Build a modern full-stack web application
- Practice AI-assisted development
- Follow clean coding and Git conventions
- Build and document the project incrementally

## Features

- Full-stack architecture
- REST API integration
- MongoDB database
- AI-assisted development

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later) and npm
- A MongoDB instance: local install or a [MongoDB Atlas](https://www.mongodb.com/atlas) connection string
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# Install dependencies (adjust folder names to match your project)
cd server && npm install
cd ../client && npm install
```

### Environment Variables

Create a `.env` file in the server directory:

```env
PORT=5000
MONGODB_URI=<your-mongodb-connection-string>
```

Never commit `.env` files. Make sure `.env` is listed in `.gitignore`.

### Running the App

```bash
# Start the backend (from /server)
npm run dev

# Start the frontend (from /client)
npm start
```

The frontend runs on `http://localhost:3000` and the API on `http://localhost:5000` by default.

## Development

This project is developed using AI-assisted development with Claude Code.