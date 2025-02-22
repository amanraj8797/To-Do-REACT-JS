# Todo App

## Overview
This is a simple **React-based Todo List App** that allows users to add, toggle, and delete tasks. The app persists the todo list in `localStorage`, ensuring tasks remain available even after a page refresh.

## Features
- **Add Tasks**: Users can add tasks to their todo list.
- **Toggle Task Status**: Clicking on a task toggles its completion state (done/not done).
- **Delete Tasks**: Users can remove tasks from the list.
- **Local Storage Support**: The app saves tasks in `localStorage`, so they persist across sessions.

## Folder Structure
```
TodoApp/
│── src/
│   ├── components/
│   │   ├── Todo.jsx
│   │   ├── TodoItems.jsx
│   ├── assets/
│   │   ├── tick.png
│   │   ├── not_tick.png
│   │   ├── cross.png
│   ├── css/
│   │   ├── Todo.css
│   │   ├── TodoItems.css
│── public/
│── package.json
│── README.md
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/todo-app.git
   cd todo-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## Components
### 1. `Todo.jsx`
This is the main component where users can add tasks. It uses `useState`, `useRef`, and `useEffect` hooks for state management and local storage.

#### Key Functionalities:
- Handles adding tasks to the list.
- Retrieves existing tasks from `localStorage` on component mount.
- Updates `localStorage` whenever the task list changes.

### 2. `TodoItems.jsx`
This component represents individual todo items.

#### Key Functionalities:
- Toggles the completion status of a task.
- Deletes tasks when clicked on the delete icon.
- Updates `localStorage` accordingly.

## Usage
1. Type a task in the input field and click **Add**.
2. Click on a task to mark it as completed.
3. Click the **X** button to remove a task.

## Technologies Used
- **React**: Frontend library.
- **JavaScript (ES6+)**: Core scripting language.
- **CSS**: Styling.
- **LocalStorage**: Persistent storage for tasks.

## License
This project is open-source under the **MIT License**.

---
Made with ❤️ by Aman Raj

## Credit
GreatStack
[YouTube Video](https://www.youtube.com/watch?v=gbAdFfSdtQ4&t=3212s)
