# Banking Application using MERN stack with JWT Token Authorization

This is a full-stack banking application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack, enhanced with JWT (JSON Web Token) authorization for secure user access. This application allows users to manage their bank accounts, make transactions, view transaction history, and more.



## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [Authentication](#authentication)
  - [API Endpoints](#api-endpoints)
- [Deployment](#deployment)    

## Features

- User registration and authentication with JWT tokens.
- Create and manage bank accounts with different types (savings, checking, etc.).
- Perform transactions (deposits, withdrawals, transfers) between accounts.
- View transaction history and account balances.
- Admin panel for managing users, accounts, and transactions.
- Responsive design for a seamless user experience on various devices.

## Prerequisites

Before you start, ensure you have the following prerequisites installed:

- **Node.js and npm**: You need Node.js and npm (Node Package Manager) to run the application.

- **MongoDB**: MongoDB should be installed and running as the database for this application. Update the database connection URL in the `.env` file.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/kavineshduraisamy/Banking-Application-with-MERN.git
   ```

2. Navigate to the project directory:

   ```bash
   cd BankApp
   ```

3. Install the backend dependencies:

   ```bash
   cd backend
   npm install
   ```

4. Install the frontend dependencies:

   ```bash
   cd ../frontend
   npm install
   ```

## Usage

### Authentication

1. Create a `.env` file in the `backend` directory with the following content:

   ```
   MONGODB_URI=your-mongodb-connection-url
   JWT_SECRET=your-secret-key
   ```

   Replace `your-mongodb-connection-url` with your MongoDB connection string and `your-secret-key` with a secret key for JWT token generation.

2. In the `backend` directory, start the server:

   ```bash
   npm start
   ```

3. In the `frontend` directory, start the React application:

   ```bash
   npm start
   ```

4. Access the application in your web browser at [http://localhost:3000](http://localhost:3000).

### API Endpoints

- **Create**: POST `/api/users/create`
- **Login**: POST `/api/users/login`
- **Profile**: POST `/api/profile`
- **Deposit**: POST `/api/transactions/deposit`
- **Withdraw**: POST `/api/transactions/withdraw`
- **Transfer**: POST `/api/transactions/transfer`

You can find more details about these endpoints and their usage in the backend code.

## Deployment
The application is deployed and accessible at (https://banking-application-mern-kavinesh.netlify.app/)


