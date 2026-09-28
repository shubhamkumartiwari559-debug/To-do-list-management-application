# To Do List Management Application

## Project Overview

The **To Do List Management Application** is a Python-based task management program developed as a practical project for the Python Essentials course.

The application provides a command-line interface (CLI) as its **primary execution mode**, making it directly executable from a terminal without requiring a GUI environment.

An optional Tkinter GUI is also included in `gui.py`.

## Problem Statement

Users often need a simple way to record daily tasks, identify priorities, track completion, and retain their task list between sessions. Manual notes or unstructured text files make these activities harder to organize.

This project provides a structured Python solution that allows users to add, view, prioritize, complete, delete, filter, and persist tasks locally.

## Features

- Add tasks
- Set Low, Medium, or High priority
- Add and validate due dates
- View all tasks
- View active tasks
- View completed tasks
- Mark tasks complete / undo completion
- Delete tasks
- Display task statistics
- Clear completed tasks
- Save tasks automatically in `tasks.json`
- Load saved tasks when the program starts
- No third-party Python packages required

## Technologies

- Python 3
- JSON
- Python standard library
- Tkinter (optional GUI)

## Project Structure

```text
ToDoListManagementApplication/
├── main.py
├── gui.py
├── tasks.json
├── README.md
└── .gitignore
```

`main.py` is the primary submission and is designed to run directly from a terminal.

## Requirements

- Python 3.8 or later recommended
- No external packages are required

Check Python:

```bash
python --version
```

On some systems:

```bash
python3 --version
```

## How to Run

### Windows

Open a terminal in the project folder:

```bash
python main.py
```

If required:

```bash
py main.py
```

### Linux / macOS

```bash
python3 main.py
```

## Example

```text
======================================================================
                 TO DO LIST MANAGEMENT APPLICATION
======================================================================
1. Add Task
2. View All Tasks
3. View Active Tasks
4. View Completed Tasks
5. Complete / Undo Task
6. Delete Task
7. Statistics
8. Clear Completed Tasks
9. Exit
======================================================================
Enter your choice [1-9]:
```

## Data Storage

The program stores tasks in `tasks.json`.

Example:

```json
[
    {
        "title": "Complete Python assignment",
        "priority": "High",
        "due_date": "30-09-2026",
        "completed": false
    }
]
```

The JSON file is created automatically when the first task is saved.

## Optional GUI

The project also contains a basic Tkinter GUI in `gui.py`.

Run it with:

```bash
python gui.py
```

The GUI is optional. **The required project entry point is `main.py`, which runs from the command line.**

## Python Concepts Demonstrated

This project demonstrates core Python Essentials concepts:

- Variables
- Input/output
- Conditional statements
- Loops
- Functions
- Lists
- Dictionaries
- String handling
- Exception handling
- File handling
- JSON serialization/deserialization
- Modules
- `if __name__ == "__main__":`
- Basic date validation
- Event-driven GUI programming in the optional interface

## Testing Checklist

Before submission, test:

1. Start the program from a terminal.
2. Add a task.
3. Add a task with each priority.
4. Enter an invalid date and verify validation.
5. View all tasks.
6. View active tasks.
7. Complete a task.
8. View completed tasks.
9. Undo a completed task.
10. Delete a task.
11. Check statistics.
12. Clear completed tasks.
13. Close the program.
14. Run it again and verify that saved tasks are still present.

## Submission Checklist

Before submitting the repository:

- [ ] Repository visibility is **Public**
- [ ] Repository URL is the root URL, not a `/tree/main` or `/blob/...` URL
- [ ] `main.py` is present at repository root
- [ ] `README.md` is present at repository root
- [ ] Project runs using `python main.py`
- [ ] No missing dependencies
- [ ] `tasks.json` is either included as sample data or generated automatically
- [ ] Test the project on a clean terminal before submission
- [ ] Verify the submitted GitHub URL opens correctly

## Author

**SHUBHAM KUMAR TIWARI**

Registration Number: **26BSA10048**

## Academic Note

This project is intended as an academic Python project. The student should understand the code, test it personally, and make any changes required by their instructor before submission.
