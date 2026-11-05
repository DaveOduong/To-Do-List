# TO-DO LIST

## 1. Project Description
To-Do List is a simple web application developed using HTML and JavaScript. It allows users to add, display, and delete tasks. The application uses browser Local Storage to save tasks so that they remain available even after refreshing or reopening the webpage.

## 2. Features
- Add new tasks to the list.
- Display all saved tasks.
- Delete individual tasks.
- Prevent empty tasks from being added.
- Automatically save tasks using Local Storage.
- Restore previously saved tasks when the webpage is reopened.

## 3. Technologies Used
- **HTML:** Creates the webpage structure, input field, and buttons.
- **JavaScript:** Handles task management, DOM manipulation, and Local Storage.

## 4. Project Files
- `index.html` – Contains the webpage structure and user input elements.
- `script.js` – Contains the functions responsible for adding, displaying, deleting, and saving tasks.

## 5. How to Run
1. Save the HTML code as `index.html`.
2. Save the JavaScript code as `script.js`.
3. Place both files in the same folder.
4. Open `index.html` in a web browser.
5. Enter a task and click **Add Items**.
6. Use the Delete button to remove unwanted tasks.

## 6. JavaScript Functions

**renderItems()**

Displays all tasks on the webpage and creates a Delete button for each task.

**savedItems()**

Converts the items array into a JSON string using `JSON.stringify()` and saves it in Local Storage.

**loadItems()**

Retrieves previously saved tasks from Local Storage using `getItem()` and displays them.

**addItems()**

Retrieves user input, checks for empty values, adds new tasks to the array, updates the display, and saves the changes.

**removeItems(idx)**

Uses `splice()` to remove a selected task from the array, refreshes the display, and saves the updated list.

## 7. JavaScript Concepts Demonstrated
- Arrays and array manipulation (`push()` and `splice()`).
- Functions and parameters.
- DOM manipulation.
- Event handling.
- Loops (`for...of`).
- Conditional statements (`if`).
- Local Storage (`setItem()` and `getItem()`).
- JSON conversion (`JSON.stringify()` and `JSON.parse()`).
- Dynamic HTML element creation.
- Arrow functions.

## 8. Conclusion
This project demonstrates how JavaScript can be used to build a basic task management application. It introduces DOM manipulation, arrays, event handling, and browser Local Storage for persistent data storage.
