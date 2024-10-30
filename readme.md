# TaskPad

TaskPad is a simple task management application built with Node.js and Express, designed to demonstrate basic CRUD operations. Users can create tasks, view a list of all tasks, and read task details.

## Features

- **Create Tasks**: Add new tasks with a title and description.
- **View Tasks**: List all created tasks on the homepage.
- **Read Task Details**: View the detailed content of each task in a separate view.

## Project Structure

- **Express.js** for handling routes and server setup.
- **EJS** templating for rendering views.
- **File System (fs)** module to manage tasks as text files.

## Getting Started

1. **Install Dependencies**:
   Ensure dependencies are installed by running:

   ```bash
   npm install
   ```

2. **Run the Application**:
   Start the application with:
   ```bash
   node index.js
   ```
3. **Access the Application**:
   Open your browser and navigate to `http://localhost:3000` to access TaskPad.

## Folder Structure

- `/files` - Stores each task as a separate `.txt` file.
- `/views` - Contains the EJS templates for the UI.

---

> **Note**: The node_modules folder is not provided. install express from npm.
