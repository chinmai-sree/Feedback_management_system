# Feedback Management System

A simple web app for collecting and managing customer feedback. Users can submit their name, email, category, rating, and comments. The dashboard shows the total number of submissions, average rating, and positive feedback count.

## Features

- Submit feedback with a category and 1–5 rating
- View submitted feedback
- See dashboard statistics
- Delete feedback entries
- Save feedback in the browser using local storage

## Built With

- HTML
- CSS
- JavaScript

## Run the Project

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Submit feedback using the form.

No build tools or additional dependencies are required.

## Project Files

```text
├── index.html   # Page structure
├── style.css    # Styling and layout
└── script.js    # Feedback form and dashboard logic

Data Storage:
Feedback is saved in the browser’s localStorage. It stays available in the same browser until its local storage is cleared. It is not sent to a server or shared between devices.
Future Improvements:
- Add search and category filters
- Add feedback export
- Connect to a database for shared, persistent storage
License:
This project is available for learning and personal use
