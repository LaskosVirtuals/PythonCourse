# Python for AI Coders

A top-down Python course designed for AI coders who use tools like Claude, Copilot, or ChatGPT.

## Live Course

The course is available at: **https://laskosvirtuals.github.io/PythonCourse/**

## About

This course teaches Python differently - from architecture to syntax, not the other way around. It's designed for developers who already build software with AI assistants but want to understand the "why" behind the code.

## Building Locally

### Prerequisites

- Python 3.9+
- pip

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/LaskosVirtuals/PythonCourse.git
   cd PythonCourse
   ```

2. Create and activate a virtual environment (recommended):
   ```bash
   python -m venv venv

   # Windows
   venv\Scripts\activate

   # macOS/Linux
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Build the Book

```bash
jupyter-book build .
```

The built HTML will be in `_build/html/`. Open `_build/html/index.html` in your browser to view locally.

### Clean Build

To rebuild from scratch:
```bash
jupyter-book clean .
jupyter-book build .
```

## Deploying to GitHub Pages

The course can be deployed to GitHub Pages using `ghp-import`:

```bash
pip install ghp-import
ghp-import -n -p -f _build/html
```

This pushes the `_build/html` folder to the `gh-pages` branch.

## Project Structure

```
PythonCourse/
├── _config.yml          # Jupyter Book configuration
├── _toc.yml             # Table of contents
├── index.md             # Home page
├── requirements.txt     # Python dependencies
├── intro/               # Getting Started section
│   ├── welcome.md
│   └── how-to-use.md
├── 02-import-system/    # Module 2: Import System
│   ├── index.md
│   └── *.ipynb          # Interactive notebooks
└── _build/              # Generated output (git-ignored)
```

## Features

- **Interactive Code**: All code examples run in the browser via Thebe/Pyodide
- **Jupyter Notebooks**: Lessons use `.ipynb` files for hands-on learning
- **GitHub Integration**: Edit on GitHub, open issues, launch in Binder

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Build and test locally
5. Submit a pull request

## License

Copyright 2025 AI Coder Community
