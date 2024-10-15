# Task Management API

### Frontend deployment
https://chipper-kringle-9180cb.netlify.app/

### Backend Deploayment
https://task-management-2-0.onrender.com/

This is a Task Management API built with Node.js and Express. It provides functionality for users to create, update, delete, and retrieve tasks. Admin users can also retrieve all tasks in the system.

## Table of Contents

[Installation](#installation)

- [Usage](#usage)
- [API Endpoints](#api-endpoints)

  - [Create Task](#create-task)
  - [Get Tasks for User](#get-tasks-for-user)
  - [Get Single Task](#get-single-task)
  - [Delete Task](#delete-task)
  - [Update Task](#update-task)
  - [Get All Tasks for Admin](#get-all-tasks-for-admin)

## Install dependencies:

npm install
## Start the server:
npm start

## API Endpoints

Create Task
POST /api/task

Get Tasks for User
GET /api/task

Get Single Task
GET /api/task/:id

Delete Task
DELETE /api/task/:id

Update Task
PATCH /api/task/:id

Get All Tasks for Admin
GET /api/task/all/tasks

## Dependencies

This project uses the following dependencies:

- **bcrypt**:

  - Version: `^5.1.1`
  - Description: A library to hash passwords, providing a secure way to store user credentials.

- **cors**:

  - Version: `^2.8.5`
  - Description: Middleware to enable Cross-Origin Resource Sharing, allowing your API to accept requests from different origins.

- **dotenv**:

  - Version: `^16.4.5`
  - Description: A zero-dependency module that loads environment variables from a `.env` file into `process.env`, helping manage configuration settings.

- **express**:

  - Version: `^4.21.1`
  - Description: A web application framework for Node.js, designed for building APIs and web applications with a minimal footprint.

- **jsonwebtoken**:

  - Version: `^9.0.2`
  - Description: A library to sign and verify JSON Web Tokens (JWT), commonly used for authentication and authorization.

- **mongodb**:

  - Version: `^6.9.0`
  - Description: The official MongoDB driver for Node.js, providing functionality to interact with MongoDB databases.

- **mongoose**:

  - Version: `^8.7.1`
  - Description: An ODM (Object Data Modeling) library for MongoDB and Node.js, making it easier to work with MongoDB data in an object-oriented way.

- **socket.io**:
  - Version: `^4.8.0`
  - Description: A library for real-time web applications, enabling bi-directional communication between clients and servers.
