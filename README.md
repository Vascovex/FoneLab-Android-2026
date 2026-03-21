# Welcome to GitHub Desktop!

# 📝 Task Manager (Python CLI App)

A simple command-line Task Manager built with Python. It allows you to add, view, complete, and delete tasks, with data saved locally using JSON.

---

## 🚀 Features

* Add new tasks
* View all tasks with status
* Mark tasks as completed
* Delete tasks
* Persistent storage using a JSON file
* Simple and user-friendly CLI interface

---

## 📁 Project Structure

```
.
├── tasks.json       # Stores all tasks (auto-created)
├── main.py          # Main application file
```

---

## ⚙️ Requirements

* Python 3.x

No external libraries are required (uses built-in modules like `json`, `os`, and `datetime`).

---

## ▶️ How to Run

1. Clone or download this project
2. Open terminal in the project folder
3. Run:

```bash
python main.py
```

---

## 🧠 How It Works

* Tasks are stored as objects with:

  * Title
  * Completion status
  * Creation timestamp
* All tasks are saved in a `tasks.json` file
* The app loads tasks on startup and saves after every change

---

## 📋 Menu Options

```
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
```

---

## 💾 Data Storage

* Tasks are saved automatically in `tasks.json`
* If the file doesn’t exist, it will be created automatically

---

## ⚠️ Notes

* Task numbers start from 1 in the UI
* Invalid inputs are handled with error messages
* Make sure not to manually corrupt the `tasks.json` file

---

## 🔧 Possible Improvements

* Add task editing
* Add due dates and priorities
* Search/filter tasks
* GUI version using Tkinter or web app
* Sync with cloud storage

---

## 📄 License

This project is open-source and free to use.

---

## 🙌 Author

Created as a beginner-friendly Python project to practice file handling and object-oriented programming.

