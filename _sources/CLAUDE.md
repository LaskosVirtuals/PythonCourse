# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **Jupyter Book** project - an interactive Python educational course called "Python for AI Coders." The course teaches Python from a "top-down" perspective specifically designed for people who code with AI assistants (Claude, Copilot, ChatGPT).

The pedagogical approach is unique: it teaches architecture and imports before basic syntax, helping AI users understand real code they encounter rather than learning Python from scratch.

## Build Commands

```bash
# Install dependencies
pip install -r requirements.txt

# Build the Jupyter Book (outputs to _build/html/)
jupyter-book build .
```

## Architecture

**Content Organization:**
- `index.md` - Course homepage
- `intro/` - Getting started content (welcome, how-to-use)
- `02-import-system/` - Module 2 content (pattern: `NN-module-name/`)
- Each module has an `index.md` overview and numbered `.ipynb` lesson files

**Configuration:**
- `_config.yml` - Jupyter Book settings (title, theme, Thebe interactive execution)
- `_toc.yml` - Table of contents defining course structure

**Build Output:**
- `_build/html/` - Generated static site with interactive code cells

**Interactive Features:**
- Uses Thebe + Pyodide for browser-based Python execution (no server required)
- Notebooks execute on build and are also runnable live in the browser

## Content Guidelines

Lessons follow a consistent format:
1. Concept explanation in markdown
2. Code examples in executable cells
3. "Try It Yourself" experiments

When adding new modules, follow the naming pattern `NN-module-name/` and update `_toc.yml` to include the new content.
