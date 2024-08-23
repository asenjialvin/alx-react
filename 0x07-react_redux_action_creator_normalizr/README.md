# React Redux Action Creator + Normalizr Project

## Overview

This project is part of the **React Front-End Specialization** and focuses on integrating Redux with action creators and Normalizr. The objective is to enhance your understanding of key Redux concepts, normalize nested JSON data, handle asynchronous actions, and write tests for various Redux components.

## Learning Objectives

By the end of this project, you should be able to explain:
- The purpose and use of **Normalizr** for normalizing nested JSON data.
- Schemas and normalization of nested JSON structures.
- Core concepts of **Redux**, including state management and the reducer pattern.
- **Redux actions** and how to create them.
- How to create **async actions** in Redux using middleware like `redux-thunk`.
- How to write and execute **tests** for Redux actions and reducers.

## Project Tasks

### Task 0: Read Data from JSON
- **Goal**: Reuse the dashboard project and implement a function, `getAllNotificationsByUser`, to retrieve notifications based on the user ID.
- **Testing**: Use Jest's `arrayContaining` method to validate returned data.

### Task 1: Normalize a Nested JSON
- **Goal**: Normalize JSON data using **Normalizr**, and create schema entities for `user`, `message`, and `notification`.
- **Testing**: Verify the correct structure of normalized data using Jest.

### Task 2: Filter a Normalized Schema
- **Goal**: Refactor `getAllNotificationsByUser` to use the normalized dataset and reduce complexity.
- **Testing**: Ensure tests pass with the refactored function.

### Task 3: Create Actions for the Course List
- **Goal**: Create `SELECT_COURSE` and `UNSELECT_COURSE` action types and creators to handle course selection.
- **Testing**: Write tests to verify the behavior of the action creators.

### Task 4: Create Actions for the UI
- **Goal**: Implement UI actions for login, logout, and notification drawer display.
- **Testing**: Write tests for the UI action creators.

### Task 5: Create Actions for the Notification List
- **Goal**: Define action types and creators to handle marking notifications as read and filtering by type.
- **Testing**: Validate the correctness of the notification actions using Jest.

### Task 6: Bound the Actions
- **Goal**: Use `bindActionCreators` to bind action creators in your components for `Courses`, `Notifications`, and `UI`.

### Task 7: Async Action Creators
- **Goal**: Implement `redux-thunk` to handle async actions and simulate an API request for login functionality.
- **Testing**: Write tests for the async actions, including success and failure scenarios.

## Requirements

- All files should end with a new line.
- Use **Ubuntu 18.04 LTS** with **Node.js 12.x.x** and **npm 6.x.x** for development.
- Ensure all tests pass for each task.
- Submit a `README.md` file at the root of the project.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/alx-react.git
    cd 0x07-react_redux_action_creator_normalizr
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

4. Run tests:
    ```bash
    npm test
    ```

## Project Structure

```
0x07-react_redux_action_creator_normalizr/
│
├── task_0/
│   ├── dashboard/
│   ├── src/schema/notifications.js
│   ├── src/schema/notifications.test.js
│   └── notifications.json
│
├── task_1/
│   ├── dashboard/
│   ├── src/schema/notifications.js
│   ├── src/schema/notifications.test.js
│
...
└── task_7/
    └── dashboard/
```

## Technologies

- **JavaScript** (ES6+)
- **React**
- **Redux** for state management
- **Normalizr** for data normalization
- **Redux Thunk** for handling async actions
- **Jest** for testing

## Resources

- [Normalizr Documentation](https://github.com/paularmstrong/normalizr)
- [Redux Documentation](https://redux.js.org)
- [Async Actions in Redux](https://redux.js.org/tutorials/essentials/part-5-async-logic)

## Author

Project developed as part of the **ALX Front-end Specialization**.
