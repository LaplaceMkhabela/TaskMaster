**To-Do List Application**.

---

# **Project Name: TaskMaster**

## Project Description
TaskMaster is a simple To-Do List Application built to help users organize their tasks effectively. Users can create, update, view, and delete tasks based on their priorities. This app is perfect for those who want to stay organized, track their to-do items, and boost their productivity.

## Features
- **Add New Tasks**: Quickly add tasks with details like title, description, due date, and priority level.
- **Mark Tasks as Complete/Incomplete**: Keep track of completed tasks and what’s still pending.
- **Edit Task Details**: Update task information at any time.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Filter and Sort**: View tasks by completion status or due date.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask (Python)
- **Database**: SQLite (or any preferred database)

## Installation Instructions
To get a local copy of TaskMaster up and running, follow these steps:

### Prerequisites
- Python (3.x)
- Flask
- SQLite

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/TaskMaster.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd TaskMaster
   ```
3. **Set up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
5. **Run the Application**:
   ```bash
   flask run
   ```
6. **Access the App**:
   - Open your web browser and go to [http://localhost:5000](http://localhost:5000)

## Usage
1. **Home Page**: The home page displays all tasks. You can filter tasks by status or due date.
2. **Add Task**: Click the “Add Task” button, fill in task details, and submit.
3. **Edit Task**: Click on any task to edit its details.
4. **Mark as Complete/Incomplete**: Use the checkbox to mark tasks as done or pending.
5. **Delete Task**: Remove tasks you no longer need with the “Delete” button.

## Project Structure
```
TaskMaster/
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── models.py
│   ├── templates/
│   └── static/
├── venv/
├── requirements.txt
└── README.md
```

## Future Improvements
- **User Authentication**: Allow users to register and log in to save their tasks securely.
- **Reminder Notifications**: Send notifications or reminders for upcoming tasks.
- **Priority Sorting**: Add custom sorting options by priority or other fields.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request.

## License
This project is licensed under the MIT License.
