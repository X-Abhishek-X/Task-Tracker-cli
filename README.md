📝 Task Tracker CLIA robust command-line interface (CLI) tool to track and manage your daily tasks efficiently. Built with Python and zero external dependencies.This project is part of the roadmap.sh backend developer path.🚀 FeaturesFeatureDescriptionAdd TasksQuickly add new items to your todo list.Track StatusMark items as todo, in-progress, or done.Update & DeleteModify descriptions or remove tasks entirely.Filter ViewsList all tasks or filter by specific status.Persistent StorageAutomatically saves data to a local tasks.json file.🛠️ Installation & SetupYou don't need to install any heavy libraries. Just clone and run!Clone the repositorygit clone [https://github.com/X-Abhishek-X/Task-Tracker-cli.git](https://github.com/X-Abhishek-X/Task-Tracker-cli.git)
Navigate to the foldercd Task-Tracker-cli
Run the trackerpython task_cli.py list
💻 Usage GuideHere are the commands you can use to manage your tasks.1. Add a new taskpython task_cli.py add "Buy groceries"
# Output: Task added successfully (ID: 1)
2. List tasksYou can view all tasks or filter them by status.# List all tasks
python task_cli.py list

# List only 'done' tasks
python task_cli.py list done

# List 'in-progress' tasks
python task_cli.py list in-progress
3. Update a taskUpdates the description of an existing task. (Replace 1 with your Task ID).python task_cli.py update 1 "Buy groceries and cook dinner"
4. Mark statusChange the status of a task to keep track of progress.# Mark as in-progress
python task_cli.py mark-in-progress 1

# Mark as done
python task_cli.py mark-done 1
5. Delete a taskPermanently remove a task from your list.python task_cli.py delete 1
📂 Project StructureTask-Tracker-cli/
├── task_cli.py    # 🧠 Main application logic
├── tasks.json     # 💾 Data storage (Auto-generated)
├── .gitignore     # 🙈 Git ignore rules
└── README.md      # 📄 Documentation
Made with ❤️ by Abhishek Leji