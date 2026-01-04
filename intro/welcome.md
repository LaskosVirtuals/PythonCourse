# Welcome: A New Way to Learn Python

## The AI Coder's Dilemma

You're not a traditional beginner. You've already built things with AI:
- Websites and apps
- Automation scripts
- Data processing tools

You know how to *describe* what you want. But when you look at the code AI generates, much of it is a mystery:

```python
from typing import Optional
from dataclasses import dataclass
import asyncio

@dataclass
class Config:
    timeout: int = 30
    retries: Optional[int] = None

async def fetch_data(config: Config) -> dict:
    ...
```

**What does all of this mean?**

---

## Why Traditional Learning Doesn't Fit

Most Python courses assume you know nothing. They start with:

> "A variable is like a box that holds a value..."

Then spend weeks on basics before you see anything resembling real code.

But you've already *seen* real code. You've worked with it. You just don't fully understand it yet.

---

## Top-Down Learning

This course inverts the traditional approach:

**Traditional (Bottom-Up):**
1. What is a variable?
2. What are data types?
3. How do loops work?
4. What is a function?
5. What is a class?
6. How do you organize a project?

**Our Approach (Top-Down):**
1. How are Python projects organized?
2. What do all these imports mean?
3. How do classes and objects work together?
4. What makes functions tick?
5. How does control flow work?
6. What are the basic data types? *(You'll pick this up naturally along the way)*

---

## The "AI Coder Perspective"

Every topic in this course is framed from your perspective:

> "When you see `@dataclass` in AI-generated code, here's what it's doing..."

> "When the AI writes `from X import Y`, here's why..."

> "When you get `ModuleNotFoundError`, here's how to fix it..."

---

## What You Need

- **A web browser** - all code runs directly in the browser via Pyodide
- **Curiosity** - you'll learn by experimenting with code
- **Your AI assistant** - keep using Claude/Copilot as you learn; now you'll understand what they're doing

---

## Let's Start

The most common confusion for AI coders is **imports**. When code fails, it's often because something wasn't imported correctly, or a package isn't installed.

We start there: {doc}`../02-import-system/index`

But first, learn {doc}`how-to-use` the interactive features of this course.
