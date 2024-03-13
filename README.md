# Vue Todo App

This is a simple todo list application built using Vue.js, allowing users to add, remove, and mark tasks as completed.

## Features

- **Add Todo**: Users can add new tasks by typing in the input field and pressing the "Add" button.
- **Remove Todo**: Users can delete individual todos by clicking the delete icon next to each task.
- **Toggle Todo Completion**: Clicking on a todo item toggles its completion status.
- **Remove All**: Users can remove all todos with a single click using the "Remove all" button.
- **Remove Completed**: Users can remove all completed todos using the "Remove completed" button.
- **Drag and Drop**: Todos can be reordered via drag and drop functionality.

## Project Structure

- **HTML**: The structure of the todo list is defined in `index.html`.
- **CSS**: Styling for the todo app is written in `styles.css`.
- **JavaScript**: The main functionality and Vue.js components are implemented in `app.js`.
- **Dependencies**: External libraries like Vue.js, UUID, SortableJS, and Intro.js are included via CDN links.

## Setup

1. Clone the repository to your local machine.
2. Open `index.html` in a web browser.

## Usage

- **Adding a Todo**: Type your task in the input field and press the "Add" button.
- **Removing a Todo**: Click the delete icon next to the task you want to remove.
- **Marking a Todo as Completed**: Click on a todo item to toggle its completion status.
- **Reordering Todos**: Drag and drop todos to reorder them.
- **Removing All Todos**: Click the "Remove all" button to delete all todos.
- **Removing Completed Todos**: Click the "Remove completed" button to delete all completed todos.

## Notes

- Todos are stored locally using localStorage, so they persist even after refreshing the page.
- The application includes introductory tooltips for first-time users, powered by Intro.js.

## Dependencies

- Vue.js: A progressive JavaScript framework for building user interfaces.
- UUID: Library for generating unique IDs.
- SortableJS: Library for creating sortable lists.
- Intro.js: Library for creating step-by-step introductions and tooltips.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
