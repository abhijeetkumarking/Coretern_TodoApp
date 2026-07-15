# React To-Do List App

A simple and responsive To-Do List application built with React. The app allows users to create, manage, and track their daily tasks through a clean and easy-to-use interface.

Tasks and their completion states are stored in the browser using `localStorage`, allowing the task list to persist even after refreshing or reopening the application.

## Features

* Add new tasks using the **Add** button or by pressing **Enter**
* Delete tasks from the list
* Mark tasks as completed using checkboxes
* Completed tasks are displayed with strikethrough styling
* Tasks and completion states persist using `localStorage`
* Prevents empty or whitespace-only tasks from being added
* Uses unique IDs for reliable task management
* Responsive and clean user interface

## Technologies Used

* **React** – Used to build the user interface and manage application state
* **JavaScript** – Handles application logic and user interactions
* **CSS Modules** – Provides scoped component styling
* **Vite** – Development and build tool
* **UUID** – Generates unique IDs for individual tasks
* **localStorage** – Stores task data in the browser

## Project Structure

```text
Coretern_TodoApp/
├── public/
│   ├── todo.png
│   └── vite.svg
│
├── src/
│   ├── assets/
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── Style.module.css
│
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── README.md
└── vite.config.js
```

## Installation and Setup

To run this project locally, follow the steps below.

### 1. Clone the repository

```bash
git clone https://github.com/abhijeetkumarking/Coretern_TodoApp.git
```

### 2. Navigate to the project directory

```bash
cd Coretern_TodoApp
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Open the local development URL displayed in the terminal to view the application.

## How It Works

The application uses React state to manage the list of tasks. Users can add new tasks, mark existing tasks as completed, or remove tasks from the list.

Whenever the task list or completion state changes, the updated data is saved to `localStorage`. This allows the application to restore the user's tasks when the page is refreshed or reopened.

Each task is assigned a unique ID using the `uuid` package, making it easier to update or delete individual tasks reliably.

## Learning Outcomes

While developing this project, I gained practical experience with:

* React components and application structure
* Managing state in React
* Handling user events
* Working with forms and input validation
* Using `localStorage` for browser-based data persistence
* Rendering dynamic lists in React
* Managing unique IDs for application data
* Styling React applications using CSS Modules
* Setting up and running a React project with Vite

## Project Purpose

This project was developed as part of the **CoreTern Summer Internship Program 2026** to demonstrate the practical use of React and JavaScript in building an interactive web application.

## Author

**Abhijeet Kumar**

CoreTern Summer Internship Program 2026
