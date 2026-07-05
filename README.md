<div align="center">

# Task Manager

A full-featured task management web application built with Python, Flask, and SQLite.

[![Python](https://img.shields.io/badge/Python-3.6%2B-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.x-black.svg)](https://flask.palletsprojects.com/)
[![SQLite](https://img.shields.io/badge/Database-SQLite-07405e.svg)](https://www.sqlite.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Issues](https://img.shields.io/github/issues/adhvaith267/flask-crud-website)](https://github.com/adhvaith267/flask-crud-website/issues)
[![Stars](https://img.shields.io/github/stars/adhvaith267/flask-crud-website)](https://github.com/adhvaith267/flask-crud-website/stargazers)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

Task Manager is a lightweight, self-hosted web application for organizing and tracking daily tasks. It provides complete CRUD functionality, status-based filtering, due date tracking, and a real-time statistics dashboard, all wrapped in a clean, responsive interface.

## Features

- **Full CRUD Operations** — Create, read, update, and delete tasks seamlessly
- **Status Filtering** — Filter tasks by All, Pending, In Progress, or Completed
- **Due Date Management** — Assign and track deadlines for each task
- **Statistics Dashboard** — Real-time overview of task counts and progress
- **Modern UI** — Clean design with smooth hover animations
- **Responsive Design** — Fully optimized for desktop, tablet, and mobile devices

## Tech Stack

| Layer      | Technology               |
|------------|---------------------------|
| Backend    | Python, Flask             |
| Database   | SQLite                    |
| Frontend   | HTML5, CSS3, JavaScript   |

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.6 or higher
- pip (Python package manager)
- A modern web browser

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/adhvaith267/flask-crud-website.git
cd flask-crud-website
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install flask
```

### 4. Run the application

```bash
python app.py
```

The application will be available at `http://localhost:5000`.

## Usage

1. Navigate to `http://localhost:5000` in your browser.
2. Add a new task using the input form.
3. Set a status and due date for each task.
4. Use the filter tabs to view tasks by status.
5. Track overall progress via the statistics dashboard.

## Project Structure

```
task/
├── static/
│   ├── custom.css       # Application styles
│   └── custom.js        # Client-side scripts
├── templates/
│   ├── base.html        # Base layout template
│   ├── index.html       # Main task list view
│   └── task_form.html   # Add/edit task form
├── app.py               # Application entry point
├── database.db          # SQLite database
└── README.md            # Project documentation
```

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

<div align="center">
Made with Flask and Python
</div>
