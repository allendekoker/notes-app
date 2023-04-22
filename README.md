# Notes App

A simple web application built with React for creating, saving, and accessing notes. The application also includes a search bar for finding specific notes.

## Features

- Create and save notes
- Access and delete notes
- Search for specific notes
- Utilizes local storage to persist notes

## Prerequisites

- Node.js installed on your system

## Installation

1. Clone this repository or download it as a ZIP file and extract it.

2. Open a terminal/command prompt, navigate to the project folder, and run the following command to install the required dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000` to access the Notes App.

## Usage

1. To create a note, type your note in the textarea and press `Enter`. Your note will be added to the list.

2. To delete a note, click the `Delete` button next to the note you wish to remove.

3. To search for a specific note, type the search term in the search bar. The list will be filtered to display only the notes containing the search term.

## Built With

- [React](https://reactjs.org/) - The web framework used
- [UUID](https://www.npmjs.com/package/uuid) - For generating unique IDs for notes