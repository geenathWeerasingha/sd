
# Haulmatic Application

## Overview

Haulmatic is a full-stack web application designed to manage users. It consists of a client-side built with React and a server-side built with Node.js and Express.

## Directory Structure

- **client/**: Contains the frontend code.
  - **public/**: Static files for the frontend.
  - **src/**: Source code for the React application.
    - **components/**: React components.
    - **context/**: Context API for state management.
    - **hooks/**: Custom React hooks.
    - **styles/**: CSS styles.
    - **App.jsx**: Main App component.
- **server/**: Contains the backend code.
  - **config/**: Configuration files.
  - **controllers/**: Request handlers for various routes.
  - **logs/**: Log files.
  - **middleware/**: Custom middleware functions.
  - **routes/**: Route definitions.
  - **.env**: Environment variables.
  - **server.js**: Entry point for the server.

## Setup Instructions

### Prerequisites

- Node.js (version 14 or above)
- npm (version 6 or above)
- MySQL (for the database)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/geenathWeerasingha/ase-coding-project
   cd Haulmatic
   ```

2. **Install dependencies:**
   - Client-side:
     ```bash
     cd client
     npm install
     ```
   - Server-side:
     ```bash
     cd server
     npm install
     ```

### Running the Application

1. **Start the server:**
   ```bash
   cd server
   npm start
   ```

2. **Start the client:**
   ```bash
   cd client
   npm run dev
   ```

The client application will be available at `http://localhost:5173` and the server at `http://localhost:3500`.

## Features

- **User Authentication:** login, and manage user sessions.
- **Role-Based Access Control:** Different access levels for different user roles.
- **Data Management:** CRUD operations for managing user data.
- **Logging:** Request and error logging for better debugging and monitoring.

## Technologies Used

- **Frontend:**
  - React
  - Context API
  - Axios
- **Backend:**
  - Node.js
  - Express
  - MySql
  - JWT for authentication

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
