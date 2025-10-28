# Event Reminder App

A full-stack application for managing and reminding users about upcoming events.

## Features

- Create, read, update, and delete events
- Set reminder times for events
- Automatic reminder scheduling (backend)
- Responsive React frontend

## Tech Stack

- **Backend**: Node.js, Express, MongoDB, Mongoose
- **Frontend**: React, Axios
- **Scheduling**: Node-cron

## Setup

### Prerequisites

- Node.js
- MongoDB

### Backend Setup

1. Navigate to the backend directory:
   ```
   cd event-reminder-app/backend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file based on `.env.example` and set your MongoDB URI.

4. Start the server:
   ```
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```
   cd event-reminder-app/frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a `.env` file based on `.env.example` if needed.

4. Start the development server:
   ```
   npm start
   ```

## Usage

- Access the frontend at `http://localhost:3000`
- Backend API at `http://localhost:5000`

## API Endpoints

- `GET /api/events` - Get all events
- `POST /api/events` - Create a new event
- `GET /api/events/:id` - Get a specific event
- `PUT /api/events/:id` - Update an event
- `DELETE /api/events/:id` - Delete an event
