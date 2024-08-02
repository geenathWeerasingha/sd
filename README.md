
# Haulmatic Application

## Overview

Haulmatic is a full-stack web application designed to manage and streamline transportation logistics. It consists of a client-side built with React and a server-side built with Node.js and Express.

## Directory Structure

- **client/**: Contains the frontend code.
  - **public/**: Static files for the frontend.
  - **src/**: Source code for the React application.
    - **components/**: React components.
    - **context/**: Context API for state management.
    - **hooks/**: Custom React hooks.
    - **pages/**: Different pages of the application.
    - **styles/**: CSS styles.
    - **App.jsx**: Main App component.
    - **index.jsx**: Entry point for the React application.
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
- MongoDB (for the database)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
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

3. **Set up environment variables:**
   Create a `.env` file in the `server` directory and add the necessary environment variables. For example:
   ```env
   PORT=5000
   MONGO_URI=<your_mongodb_connection_string>
   JWT_SECRET=<your_jwt_secret>
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
   npm start
   ```

The client application will be available at `http://localhost:3000` and the server at `http://localhost:5000`.

## Features

- **User Authentication:** Register, login, and manage user sessions.
- **Role-Based Access Control:** Different access levels for different user roles.
- **Data Management:** CRUD operations for managing transportation data.
- **Logging:** Request and error logging for better debugging and monitoring.

## Technologies Used

- **Frontend:**
  - React
  - Context API
  - Axios
- **Backend:**
  - Node.js
  - Express
  - MongoDB
  - JWT for authentication

## Contributing

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
