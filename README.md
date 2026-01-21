# Sticky Notes Application

This project contains a Django-based sticky notes application with full CRUD functionality.

## Folder Structure

- `code/`: Contains the Django project and application code
  - `manage.py`: Django management script
  - `sticky_notes/`: Django project settings
  - `notes/`: Django app for notes functionality
  - `staticfiles/`: Collected static files
  - `db.sqlite3`: SQLite database file

- `diagrams/`: Design diagrams
  - `use_case_diagram.md`: Use case diagram
  - `sequence_diagram.md`: Sequence diagram
  - `class_diagram.md`: Class diagram

- `research/`: Research answers
  - `research_answers.md`: Answers to research questions

## Setup Instructions

1. Navigate to the `code/` folder
2. Run `python manage.py runserver` to start the development server
3. Access the application at `http://127.0.0.1:8000/`

## Features

- Create, read, update, and delete sticky notes
- Responsive web interface with CSS styling
- Proper Django MVT architecture