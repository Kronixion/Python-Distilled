# Python Distilled

A hands-on learning repository following along with **Python Distilled** by David Beazley. This project contains interactive Jupyter notebooks with code examples, explanations, and experiments as I work through the book.

---

## About This Project

This repository serves as my personal study companion while reading Python Distilled. Each chapter is organized into its own folder containing Jupyter notebooks with:

- Code examples from the book
- Personal annotations and comments
- Executable demonstrations of Python concepts

---

## Progress

### Chapter 1: Primitives, Variables and Expressions

| Section | Topic | Status |
|---------|-------|--------|
| 1.3 | Primitives (`int`, `float`, `str`, `bool`) | Complete |
| 1.4.1 | Arithmetic Operators | Complete |
| 1.4.2 | Numerical Operations | Complete |
| 1.4.3 | Bitwise Operators | Complete |
| 1.4.4 | Comparison Operators | Complete |
| 1.4.5 | Logical Operators | Complete |
| 1.5 | Conditionals and Control Flow | Complete |
| 1.6 | Text Strings | In Progress |

---

## Repository Structure

```
Python Distilled/
│
├── README.md
│
└── chapter_1/
    └── chapter_1.ipynb    # Primitives, Variables and Expressions
```

---

## Topics Covered So Far

### Primitives and Variables
- Basic data types: integers, floats, strings, and booleans
- Type annotations
- Variable assignment

### Operators
- **Arithmetic**: `+`, `-`, `*`, `/`, `//`, `**`, `%`
- **Bitwise**: `<<`, `>>`, `&`, `|`, `^`, `~`
- **Comparison**: `==`, `!=`, `<`, `>`, `<=`, `>=`
- **Logical**: `and`, `or`, `not`

### Control Flow
- `if`, `elif`, `else` statements
- Ternary operator
- `while` loops
- Walrus operator (`:=`)
- `break` and `continue` statements

### Text Strings
- String literals (single, double, triple quotes)
- f-strings and formatting
- String slicing and indexing
- Common string methods

---

## Quick Reference

A handy lookup table for Python syntax and concepts learned throughout the book.

### Operators

| Operator | Name | Example | Result |
|----------|------|---------|--------|
| `+` | Addition | `7 + 4` | `11` |
| `-` | Subtraction | `7 - 4` | `3` |
| `*` | Multiplication | `7 * 4` | `28` |
| `/` | Division | `7 / 4` | `1.75` |
| `//` | Floor Division | `7 // 4` | `1` |
| `**` | Power | `7 ** 4` | `2401` |
| `%` | Modulo | `7 % 4` | `3` |
| `<<` | Left Shift | `0b11 << 2` | `0b1100` |
| `>>` | Right Shift | `0b1100 >> 2` | `0b11` |
| `&` | Bitwise AND | `0b1100 & 0b1010` | `0b1000` |
| `\|` | Bitwise OR | `0b1100 \| 0b1010` | `0b1110` |
| `^` | Bitwise XOR | `0b1100 ^ 0b1010` | `0b0110` |
| `~` | Bitwise NOT | `~0b1100` | `-0b1101` |
| `:=` | Walrus | `(x := 5)` | Assigns and returns `5` |

### Built-in Functions

| Function | Description | Example |
|----------|-------------|---------|
| `abs(x)` | Absolute value | `abs(-7)` → `7` |
| `divmod(x, y)` | Quotient and remainder | `divmod(7, 4)` → `(1, 3)` |
| `pow(x, y)` | Power (x^y) | `pow(2, 3)` → `8` |
| `round(x, n)` | Round to n decimals | `round(1.75, 1)` → `1.8` |
| `len(s)` | Length of sequence | `len("hello")` → `5` |

### String Operations

| Operation | Description | Example |
|-----------|-------------|---------|
| `s[i]` | Character at index | `"hello"[1]` → `"e"` |
| `s[i:j]` | Slice from i to j | `"hello"[1:4]` → `"ell"` |
| `s[:j]` | Slice from start | `"hello"[:3]` → `"hel"` |
| `s[i:]` | Slice to end | `"hello"[2:]` → `"llo"` |
| `s[-i:]` | Last i characters | `"hello"[-2:]` → `"lo"` |
| `s.replace(a, b)` | Replace substring | `"hello".replace("l", "x")` → `"hexxo"` |
| `f"{expr}"` | f-string formatting | `f"{2+2}"` → `"4"` |
| `f"{x:>10d}"` | Right-align, width 10 | `f"{42:>10d}"` → `"        42"` |

---

## How to Use

1. Clone the repository
2. Open the Jupyter notebooks in your preferred environment
3. Run the cells to see Python concepts in action

---

## Reference

**Python Distilled** by David Beazley
A concise guide to the essential core of Python programming.
