\# Task Tracker CLI



A simple command-line interface (CLI) to track and manage your tasks. This project is part of the \[roadmap.sh backend developer path](https://roadmap.sh/projects/task-tracker).



\## Features



\- Add, update, and delete tasks

\- Mark tasks as in-progress or done

\- List all tasks or filter by status (todo, done, in-progress)

\- Data is stored in a local JSON file



\## Requirements



\- Python 3 installed



\## Usage



Run the script using Python from your terminal:



```bash

\# Add a new task

python task\_cli.py add "Buy groceries"



\# List all tasks

python task\_cli.py list



\# List tasks by status

python task\_cli.py list done



\# Update a task (replace 1 with your task ID)

python task\_cli.py update 1 "Buy groceries and cook dinner"



\# Mark a task as in progress or done

python task\_cli.py mark-in-progress 1

python task\_cli.py mark-done 1



\# Delete a task

python task\_cli.py delete 1

