```markdown
# Todo List Application

## Overview

This repository contains a simple Todo List application developed in Node.js. The application supports basic CRUD operations for tasks, with data storage in a JSON file.

## Project Structure

- **`index.js`**: Main entry point for the application.
- **`tasks.json`**: JSON file for storing tasks data.
- **`utils.js`**: Utility functions for reading and writing data to the JSON file.

## Getting Started

### Prerequisites

- Node.js installed on your machine v18.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.dev/rahuldahal/node-mentorship
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-app-vanilla-node
   ```

3. Initialize with NPM:

   ```bash
   npm init -y
   ```

### Usage

- Run the application:

  ```bash
  node index.js
  ```

- Use tools like Postman, curl, or Thunder Client to interact with the following routes:

  - `GET /tasks`: Retrieve all tasks.
  - `POST /tasks`: Add a new task.
  - `PUT /tasks/:id`: Update a task.
  - `DELETE /tasks/:id`: Delete a task.

### Project Details

- The application stores tasks data in `tasks.json`.
- Task structure includes fields such as ID, description, and status.
- Ensure proper error handling for edge cases.

## Optional Enhancements

- Add date/time stamps to tasks.
- Implement basic validation for task inputs.
- Consider middleware for logging or error handling.

## Contributors

- [Your Name]
- [Contact Information]

Feel free to reach out for questions or contributions!
``