# To Do List
 This project is a simple to-do list application built using HTML, CSS, and JavaScript. It allows users to add tasks, remove tasks, and mark tasks as complete. Tasks are stored in the browser's localStorage, ensuring they persist even after the page is reloaded.

Features
Add Tasks: Users can add new tasks to the to-do list using an input field.
Remove Tasks: Each task has a "Remove" button to delete the task from the list.
Mark Tasks as Complete: A checkbox allows users to mark tasks as complete, which visually crosses out the task.
Persistent Storage: Tasks are saved in localStorage, so they are retained across page reloads.

Demo

Getting Started
Follow the instructions below to set up and run this project on your local machine.

Prerequisites
All you need to run this project is a web browser (e.g., Chrome, Firefox).

Installation
Clone the repository:


git clone https://github.com/yourusername/simple-todo-list.git


Navigate to the project directory:

cd simple-todo-list

Open the index.html file in your browser:

You can either double-click on the index.html file or right-click and select "Open with" and choose your browser.


File Structure

simple-todo-list/
│
├── index.html         # Main HTML file
├── styles.css         # CSS file for styling
└── script.js          # JavaScript file for functionality


Technologies Used
HTML: For the structure of the application.
CSS: For styling and layout.
JavaScript: For handling interactions, DOM manipulation, and storing tasks in localStorage.


Code Explanation

HTML:
The HTML file provides the structure of the application, which includes:

An input field for task input.
A button to add the task.
A task list to display the added tasks.

CSS:
The CSS file styles the application with a simple, clean interface. It includes:

Flexbox for layout management.
Hover effects for buttons.
Styles for completed tasks (strikethrough and green background).

JavaScript:
The JavaScript file handles the core functionality:

Adding new tasks to the list and saving them in localStorage.
Marking tasks as complete/incomplete.
Removing tasks from the list and updating localStorage.
Loading tasks from localStorage when the page is loaded.

How It Works
Adding a Task:
Users can enter a task in the input field and click the "Add" button (or press "Enter"). This adds the task to the task list and stores it in localStorage. The user will also see a success alert.

Marking Tasks as Complete:
Each task has a checkbox. When the checkbox is checked, the task gets a line-through effect, indicating completion. The task's completed status is also updated in localStorage.

Removing a Task:
Each task has a "Remove" button. Clicking it removes the task from both the task list and localStorage.

Persistent Storage:
Tasks are saved in localStorage, ensuring they persist even if the user refreshes the page or closes the browser.

LocalStorage
Tasks are stored in localStorage as an array of objects. Each object has:

text: The task description.
completed: A boolean indicating whether the task is complete.
Example localStorage Data:
[
    {
        "text": "Buy groceries",
        "completed": false
    },
    {
        "text": "Do laundry",
        "completed": true
    }
]
Contributing
If you'd like to contribute to this project:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature-name).
Make your changes.
Commit the changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/your-feature-name).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
