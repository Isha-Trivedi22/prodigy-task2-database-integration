# Task 2 - Database Integration

## Description
This project demonstrates database integration using Node.js, Express.js, and MongoDB Atlas.

## Features
- Connect Node.js application to MongoDB Atlas
- Create new users
- Retrieve all users
- Delete users
- Store data permanently in MongoDB

## Technologies Used
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Dotenv

## Installation

1. Clone the repository
2. Install dependencies

npm install

3. Create a .env file

MONGO_URI=your_mongodb_connection_string

4. Run the server

node server.js

## API Endpoints

### GET /users
Fetch all users

### POST /users
Add a new user

Example:
{
  "name": "Isha",
  "email": "isha@gmail.com",
  "age": 20
}

### DELETE /users/:id
Delete a user by ID

## Output

Data is stored and retrieved from MongoDB Atlas successfully.

## Author

Isha Trivedi