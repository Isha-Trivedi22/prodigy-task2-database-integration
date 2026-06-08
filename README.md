# Task 1 - Basic REST API with CRUD Operations

This project is a simple REST API built using Node.js and Express.js.

## Features

- Create a user
- Get all users
- Get user by ID
- Update user
- Delete user
- Basic input validation
- Proper error handling

## Tech Stack

- Node.js
- Express.js
- Thunder Client for API testing

## User Fields

Each user has:

- id
- name
- email
- age

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | / | Check server status |
| POST | /users | Create a new user |
| GET | /users | Get all users |
| GET | /users/:id | Get user by ID |
| PUT | /users/:id | Update user |
| DELETE | /users/:id | Delete user |

## How to Run

```bash
npm install
node server.js

Server will run on:

http://localhost:3000

Validation

If required fields are missing:

{
  "message": "All fields are required"
}

If email format is invalid:

{
  "message": "Invalid email format"
}
Author

Isha Trivedi