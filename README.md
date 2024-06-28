# Bookmarker Application

![bookmarker](https://github.com/LCC-CIT-Programming-CS233JS/03-bookmarker-template-travisburns/assets/41456635/88740eb9-c336-4641-889a-ae0a2eecb6e6)

## Project Overview
This application is a bookmark manager that allows users to save and organize their favorite websites. Users can add new bookmarks with URLs and descriptions, view their saved bookmarks, and delete bookmarks they no longer need. The application uses local storage to persist bookmarks between sessions.

## Features
- Add new bookmarks with URL and description
- View list of saved bookmarks
- Delete existing bookmarks
- Persistent storage using localStorage
- Responsive design with a visually appealing interface

## Technologies Used
- HTML5
- CSS3 (with Bootstrap 5.2.1)
- JavaScript (ES6+)
- Webpack for module bundling
- Babel for JavaScript transpiling

## Key Learning Points
1. ES6 Classes:
   - Encapsulation of app logic in a Bookmarker class

2. DOM Manipulation:
   - Dynamic rendering of bookmark list
   - Event handling for adding and deleting bookmarks

3. Local Storage:
   - Saving and loading bookmarks for data persistence

4. Modern JavaScript Development:
   - Use of Webpack for bundling
   - Babel for backwards compatibility

5. Error Handling:
   - Graceful handling of localStorage errors

6. Event Handling:
   - Managing form submission and click events

7. Template Literals:
   - Generating HTML strings for bookmarks

## Code Structure
- Constructor initializes bookmarks from localStorage or default list
- Methods for adding, deleting, and rendering bookmarks
- Helper method for generating HTML for each bookmark

## How to Use
1. Clone the repository
2. Run `npm install` to install dependencies
3. Run `npm run build` to build the project
4. Open `dist/index.html` in your web browser
5. Add new bookmarks using the form at the top
6. Click the trash icon to delete bookmarks

