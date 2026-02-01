# Python Distilled

A hands-on learning repository following along with **Python Distilled** by David Beazley. This project contains interactive Jupyter notebooks with code examples, explanations, and experiments as I work through the book.

---

## Motivation <- Written by my hand.

This project is intentionally done by hand. In a time where Large Language Models can generate code at the click of a button, the goal here is to slow down and actually learn. LLMs are a tool meant to help, not to replace the learning process. Relying too heavily on them leads to shallow understanding, review fatigue, and a bottleneck in real comprehension. True learning requires breaking things down to their smallest detail and understanding how they work, and that only happens when you write the code yourself.

---

## Table of Contents

| Chapter | Title | Description | Status |
|:-------:|-------|-------------|:------:|
| 1 | [Python Basics](chapter_1/chapter_1_python_basics.ipynb) | Basic types, operators, control flow, and strings | In Progress |

---

## Repository Structure

```
Python Distilled/
│
├── README.md
│
└── chapter_1/
    └── chapter_1_python_basics.ipynb    # Python Basics
```

---

## Quick Setup

1. Clone the repository
   ```bash
   git clone https://github.com/Kronixion/python-distilled.git
   cd python-distilled
   ```
2. Create a virtual environment and install Jupyter
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   pip install jupyter
   ```
3. Launch Jupyter and open any notebook
   ```bash
   jupyter notebook
   ```

**VS Code Alternative:** Open the project folder in VS Code with the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) installed. You can run `.ipynb` files directly in the editor without launching a separate Jupyter server.

---

## Reference

**Python Distilled** by David Beazley
A concise guide to the essential core of Python programming.
