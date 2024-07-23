# React Todo App

A simple and efficient Todo application built with React, designed to manage tasks with API integration.

## Overview

React Todo App is a task management tool that helps you keep track of your daily tasks. This application demonstrates the fundamental concepts of React, including components, state management, and hooks, with API integration for persistent data storage.

## Demo

You can view a live demo of the application [DEMO](https://bodyarespect.github.io/react_todo-application/).

## Key Features

- **Smooth Tile Movement**: Implements fluid animations for tile movements and merges.
- **Responsive Design**: Ensures the game is playable on various devices, including desktops, tablets, and mobiles.
- **Score Tracking**: Keeps track of the player's score and updates it in real-time.
- **Win and Lose Conditions**: Alerts the player when they win or lose the game with appropriate messages.
- **Restart Functionality**: Allows players to restart the game at any time.
- **Task Management**: Add, edit, delete, and mark tasks as complete or incomplete with ease.
- **API Integration**: All changes are saved to a backend API for persistent data storage.
- **Error Handling**: Displays appropriate error messages for any API or input errors.
- **Filtering by Status**: Filter tasks by their status (All, Active, Completed) to easily manage tasks.
- **Real-time Updates**: Ensure that all changes are reflected in real-time, providing a seamless user experience.

## Challenges

Developing the React Todo App posed several challenges, particularly around implementing the core functionalities and ensuring a smooth user experience.

### Key Challenges

- **Tile Movement and Merging**: Implementing the logic for moving and merging tiles required careful handling to ensure accuracy and performance.
- **Responsive Design**: Making the game playable and visually appealing on different screen sizes involved extensive testing and adjustments.
- **Animation Performance**: Ensuring smooth animations for tile movements and merges was crucial for a good user experience.
- **Game State Management**: Keeping track of the game state, including the board configuration, score, and win/lose conditions, needed efficient and bug-free handling.
- **API Integration**: Interacting with the API to load, add, delete, and update todos required handling asynchronous operations and errors efficiently.
- **User Experience Enhancements**: Ensuring that input fields are focused when needed, preventing duplicate actions, and displaying spinners during API operations were key for a smooth user experience.
- **Error Handling**: Implementing robust error handling to show appropriate notifications and maintaining input states correctly after errors.
- **State Management**: Managing the application state, including todos, temporary states, and UI states, in a scalable and maintainable manner.
- **Testing and Debugging**: Ensuring that all functionalities work correctly across different browsers and devices required thorough testing and debugging.

These challenges were addressed with careful planning, rigorous testing, and iterative development to ensure a high-quality, user-friendly application.

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js (version 14.x or later)
- npm (version 6.x or later) or yarn

## Installation & Setup

To install the project and run it locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/username/react_todo-application.git
    ```

2. Navigate to the project directory:
    ```bash
    cd react_todo-application
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Start the local development server:
    ```bash
    npm start
    ```

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A strongly typed programming language that builds on JavaScript.
- **CSS Modules**: For scoped and maintainable CSS.
- **Webpack**: Module bundler.
- **Babel**: JavaScript compiler.
- **ESLint**: For code quality and linting.
- **Prettier**: For code formatting.
