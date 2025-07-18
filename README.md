# ICC1_todoapp

## Purpose

This repository is meant to be used as a basis for the ICC1 module at Ada.
This is the first task for the part of learning for the capstone project.
Learners will deploy this in a virtual machine on a Cloud Provider such as AWS, Azure, or GCP. 

A simple Flask-based To-Do application that lets you manage tasks with priorities.

## Features

- Add, view, and delete tasks
- Tasks have priorities (lower number = higher priority)
- Data stored in a local SQLite database

## Getting Started

- Azure: See the Tango Guide **[here](https://app.tango.us/app/workflow/Create-and-Configure-Azure-VM-for-Todo-App-58d526e854564c769259ad3d02b8c872)**
- AWS: - AWS: **[here](https://app.tango.us/app/workflow/Launch-and-Configure-an-EC2-Monolithic-ToDo-App-on-AWS--IaaS--6818e7d54be2406cb9e9bc695784c313)**

### Prerequisites

- Python 3.x
- Flask

### Installation

1. Clone this repository:
    ```sh
    git clone <repo-url>
    cd ICC1_todoapp
    ```
2. Install dependencies:
    ```sh
    pip install flask
    ```

### Running the App

**Note:** Running on port 80 may require root privileges.

```sh
sudo python3 app.py
```

## Project Structure

- `app.py` — Main Flask application
- `todo.db` — SQLite database (created automatically)
- `templates/` — HTML templates

## License

MIT License
