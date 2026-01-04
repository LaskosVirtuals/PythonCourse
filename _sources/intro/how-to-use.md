# How to Use This Course

## Interactive Code

Every code example in this course is **live**. You can run it, modify it, and experiment.

### Enabling Live Code

1. Look for the **rocket icon** (🚀) at the top right of any page with code
2. Click it and select **"Live Code"**
3. Wait a few seconds for Pyodide (Python in browser) to load
4. Now you can run and edit any code cell!

### Running Code

Once live code is enabled:
- Click the **"Run"** button in any code cell
- Or press **Shift + Enter** to run and move to the next cell
- Modify the code and run again to experiment

---

## Example: Try It Now

Here's your first interactive code cell. After enabling live code, try running it:

```python
# Your first interactive Python!
message = "Hello, AI Coder!"
print(message)

# Try changing the message and running again
```

```python
# Experiment: what happens if you run this?
numbers = [1, 2, 3, 4, 5]
doubled = [n * 2 for n in numbers]
print(f"Original: {numbers}")
print(f"Doubled: {doubled}")
```

---

## Learning Tips

### 1. Break Things on Purpose

The best way to understand code is to break it:
- Remove a line and see what error you get
- Change a value and see what happens
- Misspell something and read the error message

Error messages are your teacher.

### 2. Use Your AI Assistant

As you learn, keep using Claude or Copilot:
- Ask "what does this code do?"
- Ask "why did you write it this way?"
- Now you'll understand the answers better

### 3. Focus on Patterns

Don't memorize syntax. Recognize patterns:
- "Oh, this is the import pattern"
- "This is how classes are structured"
- "This is the error handling pattern"

---

## Troubleshooting

### Live code not loading?

- Check your internet connection
- Try refreshing the page
- Some browsers block WebAssembly - try Chrome or Firefox

### Code gives an error?

- Read the error message carefully
- The last line usually tells you what went wrong
- Check for typos in variable names

### Not sure what to try?

Each lesson includes:
- **Concept explanation** - what it means
- **Code examples** - how it looks
- **Experiments** - things to try
- **Quick checks** - test your understanding

---

## Ready?

Let's dive into the most important topic for AI coders: understanding Python's import system.

{doc}`../02-import-system/index`
