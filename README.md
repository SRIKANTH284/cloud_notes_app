

# Cloud Notes App

A lightweight and simple note-taking web application where users can create, edit, and delete notes, all saved locally in the browser's `localStorage`. This app does not require any backend and works completely offline.

## Features

- **Add New Notes**: Create new notes by clicking the `Add` button.
- **Edit Notes**: Toggle between edit mode and preview mode using the `Edit` button.
- **Delete Notes**: Remove notes using the `Delete` button.
- **LocalStorage**: All notes are saved locally in the browser, ensuring persistence between sessions.
- **Responsive Design**: The app adjusts to different screen sizes, ensuring accessibility on mobile and desktop.

## Technologies Used

- **HTML**: The structure of the application.
- **CSS**: Styling using the Poppins font and a simple layout (as defined in `style.css`).
- **JavaScript**: Main functionality for adding, editing, deleting notes, and saving them in localStorage.

## Setup Instructions

To run the project locally:

1. **Download or Clone the Repository**
   ```bash
   git clone https://github.com/username/cloud-notes-app.git
   ```
   
2. **Open the Project Folder**
   Navigate to the folder containing the project files.

3. **Open the `index.html` in a Browser**
   Simply double-click the `index.html` file or use a local development server to run the project in your browser.

## File Structure

```bash
cloud-notes-app/
│
├── index.html    # The main HTML file
├── script.js     # JavaScript for note-taking functionality
├── style.css     # CSS for styling the app
└── README.md     # This readme file
```

### `index.html`
This is the main HTML file where the structure of the application is defined.

### `script.js`
Handles the core logic for adding, editing, and deleting notes, and updates the localStorage accordingly.

### `style.css`
Contains all the styles applied to the app for proper presentation.

## Usage

1. **Adding a Note**: Click the green `Add` button at the top right to create a new note.
2. **Editing a Note**: Use the `Edit` button to switch between the preview and edit modes.
3. **Deleting a Note**: Click the trash icon to delete a note.
4. **Automatic Saving**: Any changes made to notes are automatically saved in the browser’s localStorage.

## License

