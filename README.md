# 📝 Task Tracker CLI

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white) ![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge) ![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

A simple, dependency-free command-line interface (CLI) to track and manage daily tasks.

This project is part of the [roadmap.sh backend developer path](https://roadmap.sh/projects/task-tracker).

---

## 🚀 Features

- **Add Tasks:** Quickly add new items to your todo list.
- **Track Status:** Mark items as `todo`, `in-progress`, or `done`.
- **Update & Delete:** Modify descriptions or remove tasks entirely.
- **Filter Views:** List all tasks or filter by specific status.
- **Persistent Storage:** Saves data to a local `tasks.json` file.

---

## 🛠️ Installation & Setup

No external dependencies required — just Python 3.x.

1. Clone the repository:

```powershell
git clone https://github.com/X-Abhishek-X/Task-Tracker-cli.git
cd Task-Tracker-cli
```

2. Run the CLI (examples below assume `python` points to Python 3):

```powershell
# Show help / usage
python task-cli.py --help

# List all tasks
python task-cli.py list
```

---

## 💻 Usage Guide

Examples of common commands (replace IDs as needed):

```powershell
# Add a new task
python task-cli.py add "Buy groceries"

# List all tasks
python task-cli.py list

# List tasks by status (todo | in-progress | done)
python task-cli.py list done

# Update a task description (task ID 1)
python task-cli.py update 1 "Buy groceries and cook dinner"

# Mark a task in-progress
python task-cli.py mark-in-progress 1

# Mark a task done
python task-cli.py mark-done 1

# Delete a task
python task-cli.py delete 1
```

---

## 📂 Project Structure

```
Task-Tracker-cli/
├── task-cli.py    # Main application logic
├── tasks.json     # Data storage (auto-generated)
├── .gitignore
└── README.md
```

Made with ❤️ by Abhishek Leji