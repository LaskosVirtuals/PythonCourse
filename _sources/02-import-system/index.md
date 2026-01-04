# Module 2: The Import System

## Why Start Here?

When AI-generated code fails, the error often looks like this:

```
ModuleNotFoundError: No module named 'requests'
```

Or:

```
ImportError: cannot import name 'Foo' from 'bar'
```

Understanding Python's import system is **the most valuable skill** for debugging AI code. This module teaches you:

1. What all the different `import` statements mean
2. Which modules are built-in vs. need installation
3. How packages and modules are organized
4. How to fix common import errors

---

## What Is an Import?

When you write Python code, you don't start from zero. Python comes with a huge library of pre-written code, and there are millions of additional packages available.

An `import` statement brings that code into your program:

```python
# Now you can use everything in the 'os' module
import os

# Get the current working directory
current_dir = os.getcwd()
```

Without the import, Python wouldn't know what `os` is.

---

## The Four Types of Imports You'll See

### 1. Standard Library (Built-in)
```python
import os
import json
import datetime
```
These come with Python. No installation needed.

### 2. Third-Party Packages
```python
import requests
import pandas as pd
import numpy as np
```
These need to be installed with `pip install package_name`.

### 3. Local/Project Modules
```python
from myproject import utils
from .helpers import process_data
```
These are files in your own project.

### 4. Relative Imports
```python
from . import sibling_module
from ..parent import something
```
These reference modules relative to the current file.

---

## This Module's Lessons

```{tableofcontents}
```

---

## Quick Reference

| Import Style | Meaning |
|-------------|---------|
| `import X` | Import module X, access via `X.thing` |
| `from X import Y` | Import Y from X, use directly as `Y` |
| `from X import Y as Z` | Import Y, rename to Z |
| `import X as Y` | Import X, rename to Y |
| `from X import *` | Import everything (not recommended) |
| `from . import X` | Relative import from same package |
| `from .. import X` | Relative import from parent package |
