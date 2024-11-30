# Task-management-app
# Task Management App

A task management web application built using **Express.js**, **Node.js**, and **EJS**. The app allows users to create tasks, save them as text files, and edit the names of existing tasks.

## Features

- **Create Tasks**: Allows users to enter a task title and details, which are saved as `.txt` files locally.
- **Edit Task**: Users can rename existing task files to manage them better.
- **Read Tasks**: Users can view the content of the task files directly in the app.

## Technologies Used

- **Node.js**
- **Express.js**: Web framework for building web applications.
- **EJS**: Templating engine to render HTML pages dynamically.
- **File System (fs module)**: Used to handle file operations (create, read, rename).

## Setup and Installation

Follow these steps to run the application locally:

### Prerequisites

- Install **Node.js** (if you don't have it already):  
  [Node.js Downloads](https://nodejs.org/)

### Clone the Repository

```bash
git clone https://github.com/mudit203/task-management-app.git
cd task-management-app


Install Dependencies
Run the following command to install the required dependencies:

bash

npm install


Start the Application
To start the application locally, run the following command:

bash
Copy code
npm start



Routes
GET /: Displays the main page where tasks are listed.
POST /create: Allows users to create new tasks (saved as .txt files).
POST /edit: Allows users to rename task files.
GET /file/:filename: Displays the content of a specific task file.
GET /edit/:filename: Displays the form to edit a task's file name.
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Express.js: A minimal and flexible Node.js web application framework.
EJS: A simple templating engine for embedding JavaScript in HTML.
Node.js fs module: Used for file handling operations like reading and writing files.

