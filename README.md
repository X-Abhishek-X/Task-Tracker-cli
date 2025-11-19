# 📝 Task Tracker CLI

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

A robust command-line interface (CLI) tool to track and manage your daily tasks efficiently. Built with **Python** and zero external dependencies.

> This project is part of the [roadmap.sh backend developer path](https://roadmap.sh/projects/task-tracker).

---

## 🚀 Features

| Feature | Description |
| :--- | :--- |
| **Add Tasks** | Quickly add new items to your todo list. |
| **Track Status** | Mark items as `todo`, `in-progress`, or `done`. |
| **Update & Delete** | Modify descriptions or remove tasks entirely. |
| **Filter Views** | List all tasks or filter by specific status. |
| **Persistent Storage** | Automatically saves data to a local `tasks.json` file. |

---

## 🛠️ Installation & Setup

You don't need to install any heavy libraries. Just clone and run!

1. **Clone the repository**
   ```bash
   git clone [https://github.com/X-Abhishek-X/Task-Tracker-cli.git](https://github.com/X-Abhishek-X/Task-Tracker-cli.git)
Navigate to the folder

cd Task-Tracker-cli
Run the tracker

Bash

python task_cli.py list
💻 Usage Guide
Here are the commands you can use to manage your tasks.

1. Add a new task
Bash

python task_cli.py add "Buy groceries"
# Output: Task added successfully (ID: 1)
2. List tasks
You can view all tasks or filter them by status.

Bash

# List all tasks
python task_cli.py list

# List only 'done' tasks
python task_cli.py list done

# List 'in-progress' tasks
python task_cli.py list in-progress
3. Update a task
Updates the description of an existing task. (Replace 1 with your Task ID).

Bash

python task_cli.py update 1 "Buy groceries and cook dinner"
4. Mark status
Change the status of a task to keep track of progress.

Bash

# Mark as in-progress
python task_cli.py mark-in-progress 1

# Mark as done
python task_cli.py mark-done 1
5. Delete a task
Permanently remove a task from your list.

Bash

python task_cli.py delete 1
📂 Project Structure

Task-Tracker-cli/
├── task_cli.py    # 🧠 Main application logic
├── tasks.json     # 💾 Data storage (Auto-generated)
├── .gitignore     # 🙈 Git ignore rules
└── README.md      # 📄 Documentation
Made with ❤️ by Abhishek Leji