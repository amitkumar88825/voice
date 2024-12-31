# Voice Application

This is a Voice Application built using the MERN stack (MongoDB, Express.js, React, and Node.js). The application allows users to interact with the system using voice commands.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- Voice recognition and processing
- Real-time interaction with the backend
- User authentication and authorization
- Responsive user interface built with React
- RESTful API with Express.js and Node.js
- Database management with MongoDB

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following software installed on your machine:

- Node.js (v14.0.0 or higher)
- MongoDB (v4.0.0 or higher)
- npm (v6.0.0 or higher) or yarn (v1.22.0 or higher)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/voice-application.git
    cd voice-application
    ```

2. Install server dependencies:

    ```sh
    cd server
    npm install
    ```

3. Install client dependencies:

    ```sh
    cd ../client
    npm install
    ```

4. Create a `.env` file in the `server` directory and add the following environment variables:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

### Usage

1. Start the MongoDB server:

    ```sh
    mongod
    ```

2. Start the server:

    ```sh
    cd server
    npm start
    ```

3. Start the client:

    ```sh
    cd client
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000`.

## API Endpoints

### Authentication

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Log in a user

### Voice Commands

- `POST /api/voice/command` - Process a voice command

### User

- `GET /api/user/profile` - Get user profile information

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.