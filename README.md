# TaskFlow - Vanilla JS Kanban Board

![Status](https://img.shields.io/badge/Status-Planning-yellow)
![Tech](https://img.shields.io/badge/Tech-Vanilla%20JS-green)

## 🚀 Project Overview

TaskFlow is a drag-and-drop Kanban-style task management application built entirely with Vanilla JavaScript. The goal of this project is not just to build a functioning app, but to simulate a professional production environment without the abstraction of frameworks.

This project serves as a capstone to demonstrate proficiency in modern JavaScript concepts including ES6 modules, asynchronous programming, event delegation, and state management.

## 🎯 Learning Objectives

The primary purpose of this project is to bridge the gap between tutorial-based learning and real-world software engineering. Specific technical goals include:

- Architecture: Implementing a modular file structure to separate concerns (API logic, State, UI Rendering).
- State Management: managing a complex "Single Source of Truth" object that drives the UI, rather than querying the DOM for data.
- Asynchronous JS: Handling Promises, async/await, and API requests using fetch and json-server.
- CRUD Operations: Implementing full Create, Read, Update, and Delete functionality.
- Modern Syntax: Utilizing destructuring, spread operators, arrow functions, and ES6 modules.

## 💡 Planned Features

- Dynamic Board Rendering: Boards and columns generated dynamically from a JSON data source.
- Drag & Drop: Native HTML5 Drag and Drop API to move tasks between columns.
- Task Management: Create new tasks, edit descriptions, assign priority levels, and delete tasks.
- Persistence: All changes persist via a RESTful API (simulated with json-server).
- Responsive Design: Mobile-first layout using CSS Grid and Flexbox.

## 🏗️ Technical Architecture

To avoid "spaghetti code," this application will follow a loose MVC-like pattern:

- model.js: Handles the data state and business logic.
- api.js: Abstracts the network requests away from the rest of the app.
- view.js: Handles DOM manipulation and rendering.
- main.js: The controller that initializes the app and connects events to logic.

## 🛠️ Tech Stack

- Language: HTML5, CSS3, JavaScript (ES6+)
- (Mock): json-server (npm)
- Styling: Vanilla CSS (BEM naming convention)

## 🗓️ Development Roadmap

- Setup project scaffolding and file structure.
- Initialize json-server and test API endpoints.
- Build static HTML/CSS layout for the board.
- Implement data fetching and initial render logic.
- Implement Create/Read/Update/Delete functionality.
- Implement Drag and Drop logic.
- Refactor for clean code and error handling.
