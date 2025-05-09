To-Do List Web Application

![Screenshot 2025-05-09 182737](https://github.com/user-attachments/assets/b1f34995-8bb6-49d3-a8ab-12bb48f70562)
![Screenshot 2025-05-09 182905](https://github.com/user-attachments/assets/adefa092-66ac-4604-af68-8e4d0b57cdfe)

# Description

This is a simple, interactive to-do list web application that allows you to manage your tasks effectively. You can add new tasks, mark them as complete, and delete them.  It provides a user-friendly interface to keep track of your daily activities or project tasks.

# Features

* Add Task: Enter a task in the input field and click the "Add" button to add it to the list.
* Delete Task: Click the "X" button next to a task to remove it from the list.
* Dynamic List: The list of tasks is dynamically updated as you add or delete items.
* Simple Interface: A clean and intuitive user interface.

# Technologies Used

* HTML:  Provides the structure of the web application.
* CSS:  Styles the web application to make it visually appealing.
* JavaScript:  Implements the interactive functionality of the to-do list.

# How to Use

1.  Open the web application: Open the `To-Do List.html` file in your web browser.
2.  Add a task: Type your task in the input field labeled "Enter a new task".
3.  Submit the task: Click the "Add" button.  The task will be added to the list.
4.  Delete a task: Click the "X" button next to the task you want to remove.

# Code Explanation

# HTML (`To-Do List.html`)
* The `<body>` contains:
    * A heading (`<h1>`) for the title of the to-do list.
    * An input field (`<input>`) for entering new tasks.
    * A button (`<button>`) to add tasks.
    * An unordered list (`<ul>`) where tasks are displayed.
* The `<script>` tag contains the JavaScript logic for the to-do list.
* The `<style>` tag contains the CSS for the styling of the page.

# CSS (`<style>`)

* The CSS styles the page, including the font, colors, layout, and appearance of the input field, button, and list items.
* The list items have a hover effect and a delete button with a red "X" that appears on the right side of the list item.

# JavaScript (`<script>`)

* `addTask()`:
    * Gets the value from the input field.
    * Validates that the input is not empty.
    * Creates a new list item (`<li>`).
    * Adds the task text and a delete button ("X") to the list item.
    * Appends the new list item to the `taskList` (`<ul>`).
    * Clears the input field.
* `deleteTask(element)`:
    * Takes the clicked element (the "X" button) as an argument.
    * Removes the parent element of the button, which is the `<li>` element.

Author: Vivek Jayadev
