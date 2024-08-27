# Flask To-Do List Application

This is a simple To-Do List web application built using Flask, SQLAlchemy, and SQLite. The app allows users to create, update, and delete tasks.

## Features

- **Add Tasks**: Users can add new tasks to their to-do list.
- **View Tasks**: All tasks are displayed in the order they were created.
- **Update Tasks**: Users can update the content of existing tasks.
- **Delete Tasks**: Users can delete tasks from the list.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework in Python.
- **SQLAlchemy**: A SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **SQLite**: A lightweight, disk-based database.
- **Jinja2**: A templating engine for Python, used in rendering HTML templates.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/qedir314/Flask-Introduction.git
   cd Flask-Introduction
2. **Create a virtual environment:**
    ```bash
    python3 -m venv venv
    venv\Scripts\activate
3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
4. **Create the SQLite database:**

    Uncomment the following lines in 'app.py':
    ```bash
    with app.app_context():
        db.create_all()
    ```
    Then, run the following command to create the database:
    ```bash
    python app.py
The application will start running on localhost:5000/


## Usage

- **Home Page**: Displays a list of all tasks with options to update or delete each task.
- **Add Task**: Use the input field and button on the home page to add new tasks.
- **Update Task**: Click the "Update" button next to a task to modify it.
- **Delete Task**: Click the "Delete" button next to a task to remove it from the list.

## Deployment

The application is deployed on Heroku. You can access it using the following link:

[Heroku App Link](https://flask-crud-introduction-30c853812c42.herokuapp.com/)

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
