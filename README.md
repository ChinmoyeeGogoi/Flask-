# Task Master - Flask To-Do Application

A simple Task Management web application built using Flask and SQLite. Users can add, view, update, and delete tasks through a clean web interface.

## Features

* Add new tasks
* View all tasks
* Store tasks in a SQLite database
* Track task creation date and time
* Update existing tasks
* Delete tasks
* Responsive and clean user interface

## Tech Stack

* Python
* Flask
* Flask-SQLAlchemy
* SQLite
* HTML
* CSS
* Jinja2 Templates

## Project Structure

```text
Task-Master/
│
├── app.py
├── test.db
├── templates/
│   ├── base.html
│   ├── index.html
│   └── update.html
│
├── static/
│   └── css/
│       └── main.css
│
├── .gitignore
└── README.md
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/task-master.git
cd task-master
```

### Create a Virtual Environment

```bash
python -m venv env
```

### Activate the Virtual Environment

#### Windows (PowerShell)

```powershell
.\env\Scripts\Activate
```

#### Linux / macOS

```bash
source env/bin/activate
```

### Install Dependencies

```bash
pip install flask flask-sqlalchemy
```

## Run the Application

```bash
python app.py
```

The application will be available at:

```text
http://127.0.0.1:5000
```

## Database

The application uses SQLite and automatically stores task information in:

```text
test.db
```

Task fields:

* id
* content
* completed
* date_created

## Future Enhancements

* User authentication
* Task categories
* Due dates and reminders
* Task status tracking
* Search and filtering
* Bootstrap-based responsive UI

## Learning Outcomes

This project demonstrates:

* Flask routing
* CRUD operations
* SQLAlchemy ORM
* Template rendering with Jinja2
* Form handling using POST requests
* Database integration with SQLite

## Author

Chinmoyee Gogoi

Built as a Flask learning project to understand web development fundamentals and database-driven applications.
