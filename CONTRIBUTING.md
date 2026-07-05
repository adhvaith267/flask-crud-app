# Contributing to Task Manager

Thank you for considering contributing to Task Manager! Contributions of all kinds are welcome — bug fixes, new features, documentation improvements, and suggestions.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)
- [Style Guidelines](#style-guidelines)

## Code of Conduct

Be respectful and constructive. This project welcomes contributors of all experience levels, and we want it to remain a friendly, harassment-free space for everyone.

## Getting Started

1. Fork the repository on GitHub.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/flask-crud-website.git
   cd flask-crud-website
   ```
3. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate
   pip install flask
   ```
4. Run the app locally to confirm everything works:
   ```bash
   python app.py
   ```

## How to Contribute

1. Create a new branch for your change:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Make your changes, following the [Style Guidelines](#style-guidelines) below.
3. Test your changes locally to make sure nothing is broken.
4. Commit your changes with a clear message:
   ```bash
   git commit -m "Add: short description of your change"
   ```
5. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a Pull Request against the `main` branch of the original repository.

## Pull Request Guidelines

- Keep pull requests focused on a single feature or fix.
- Write a clear title and description of what your PR does and why.
- Reference any related issues (e.g. `Fixes #12`).
- Ensure the app runs without errors before submitting.
- Be responsive to review feedback.

## Reporting Bugs

If you find a bug, please open an issue and include:

- A clear, descriptive title
- Steps to reproduce the issue
- Expected vs. actual behavior
- Screenshots, if applicable
- Your environment (OS, Python version, browser)

## Suggesting Features

Feature suggestions are welcome. Please open an issue describing:

- The problem your feature would solve
- How you imagine it working
- Any alternatives you've considered

## Style Guidelines

- Follow [PEP 8](https://peps.python.org/pep-0008/) conventions for Python code.
- Keep functions small and focused.
- Use descriptive variable and function names.
- Comment non-obvious logic.
- Keep HTML/CSS/JS consistent with the existing style in `templates/` and `static/`.

---

Thank you for helping improve Task Manager!
