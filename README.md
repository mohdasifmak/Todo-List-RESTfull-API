# To-Do List Backend (MongoDB)

## Description
This project is a REST API for managing a to-do list, built using Node.js, Express, and MongoDB. It supports CRUD operations for tasks.

## Features
- Create a new task.
- Fetch all tasks or a specific task by ID.
- Update the status of a task.
- Delete a task.

## Setup Instructions
1. Clone the repository:
   git clone <repository-url>
Navigate to the project directory:
cd project-folder

Install dependencies:
npm install
Start MongoDB on your local machine.
Start the server:
npm start
The server will run at http://localhost:3000.

API Endpoints

POST /tasks: Create a new task (Request Body: { title, description }).

GET /tasks: Fetch all tasks.

GET /tasks/:id: Fetch a specific task by ID.

PUT /tasks/:id: Update a task's status (Request Body: { status }).

DELETE /tasks/:id: Delete a task by ID.

Dependencies

Express

Mongoose

Body-Parser

Notes
Ensure MongoDB is running on your system before starting the application.
