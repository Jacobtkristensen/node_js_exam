# Node.js Fullstack Exam

## Overview
This project is a fullstack application built with a Svelte frontend and a Node.js backend. 

## Frontend
- **Framework**: Svelte

## Backend
- **Runtime**: Node.js

### Functionality and Dependencies

#### Core Functionality
- **bcrypt**: Used for hashing user passwords.
- **crypto**: Used to generate session secret.
- **dotenv**: Used for environmental variables.
- **express**: Web framework for Node.js, used to build web applications and APIs.
- **express-rate-limit**: Middleware to limit repeated requests to server endpoints. 
- **express-session**: Middleware for managing user sessions.
- **mongodb**: simple MongoDB setup.
- **resend**: used for email verification and password resets.
- **socket.io**: used to toggle dark/light mode for all connected users
- **validator**:  used for Validating and sanitizing strings.

## Getting Started
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Set up environment variables:
    - Create a `.env` file in the root directory and add necessary environment variables.
4. Set up the database:
    ```bash
    npm run database-create
    ```
5. Start the development server:
    ```bash
    npm run dev
    ```

