# command-line-todo-app
Here's a simple README file you can use for your GitHub repository based on the information about your command-line to-do app:

---

# Command Line Todo App

A simple command-line to-do list application built with Node.js. This app allows users to manage their tasks by adding, deleting, and clearing tasks. All tasks are stored in a `todo.json` file, providing persistence between app runs.

## Features
- **Add tasks**: Add new tasks to your to-do list.
- **Delete tasks**: Remove specific tasks from the list.
- **Clear all tasks**: Delete all tasks in the list.
- **Persistent storage**: Tasks are saved and loaded from a `todo.json` file.

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yashwankhade5/todo-cli-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todo-cli-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

## Usage

You can use the following commands to manage your tasks:

- **Add a task**:
  ```bash
  node app.js add "<task>"
  ```
  Example:
  ```bash
  node app.js add "Buy groceries"
  ```

- **Delete a task**:
  ```bash
  node app.js delete "<task>"
  ```
  Example:
  ```bash
  node app.js delete "Buy groceries"
  ```

- **Clear all tasks**:
  ```bash
  node app.js clear
  ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


