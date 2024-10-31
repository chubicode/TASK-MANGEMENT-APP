# TASK MANAGEMENT APP WITH REDUX
![todo-app-react-redux](/src/assets/github-cover.png)

To view app go to link : https://taskmanagerappflexisaf.netlify.app


## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Task Management Context API](#task-management-context-api)
- [Redux Integration](#redux-integration)
- [Contributing](#contributing)
- [License](#license)

## Overview
The Task Management Application is a user-friendly web application that allows users to efficiently manage their tasks. It provides an intuitive interface to add, edit, and delete tasks, helping users keep track of their daily activities. This application leverages Redux for state management and a Context API for task management, ensuring a smooth user experience.

## Features
- **Add Tasks:** Quickly add new tasks with titles and descriptions.
- **Edit Tasks:** Modify existing tasks to update their details.
- **Delete Tasks:** Remove tasks that are no longer needed.
- **Task Status:** Mark tasks as completed or pending.
- **Filter Tasks:** Easily filter tasks based on their status (all, completed, or pending).
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies Used
- **Frontend:** React
- **State Management:** Redux, Context API
- **Styling:** CSS
- **Build Tool:** Webpack
- **Version Control:** Git

## Getting Started

### Prerequisites
To run this application, you need to have the following installed:
- Node.js (version 14 or later)
- npm (Node Package Manager)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/task-management-app.git
2.  Navigate to the project directory:

``bash
cd task-management-app
npm install
npm start


### Usage
Once the application is running, you can:

- Add a New Task:
**Enter a task title and description in the input fields.
**Click the "Add Task" button to create a new task.
-Edit a Task:
**Click on a task to view its details.
**Modify the title or description as needed.
**Click the "Save" button to apply changes.
-Delete a Task:
**Click the "Delete" button next to a task to remove it.
-Filter Tasks:
**Use the filter buttons to view all tasks, only completed tasks, or only pending tasks.

### Task Management Context API
The Task Management Context API provides a way to share task-related data across different components without prop drilling. This context allows components to access and manipulate task data (such as adding, editing, and deleting tasks) easily.

### Key Functions:
TaskProvider: Wraps the main application to provide task data and functions to its children.
useTask Hook: A custom hook that enables components to consume task data and functions from the context.
This approach simplifies state management and reduces the need for passing props through multiple layers of components.

### Redux Integration
Redux is used to manage the application's global state effectively. It helps in maintaining a single source of truth for task-related data and actions, making it easier to debug and maintain the application.

### Key Components:
Store: The central hub for the application's state.
Reducers: Functions that specify how the application's state changes in response to actions.
Actions: Plain objects that describe the type of change to be made in the state.
Example Redux Workflow:
Dispatch an Action: When a user adds or edits a task, an action is dispatched.
Reducer Processes Action: The corresponding reducer processes the action and updates the state.
Component Rerenders: Components subscribed to the Redux store re-render with the updated state.

### Contributors
Contributions are welcome! 


### License
This project is licensed under the MIT License - see the LICENSE file for details.


