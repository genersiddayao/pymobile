# PyMobile IDE

**A free Python 3 editor and runner for your phone.** No install, no fee, no sign-up.

### ▶ Website: **https://genersiddayao.github.io/pymobile/**
### ▶ Go straight to the app: **https://genersiddayao.github.io/pymobile/app/**

Built for students and faculty of Cagayan State University, and free for anyone learning Python.

---

## Why this exists

Many students learn programming without owning a laptop, and popular mobile Python apps put useful features behind a paid upgrade. PyMobile IDE is a free alternative: open a link on any phone, write Python, tap **Run**.

## Features

- Runs real Python 3 code right in the browser, on the phone itself
- `input()` support: type answers straight into the output panel
- Clear error messages that highlight the bad line, with a **Go to line** button
- **Stop** button for runaway loops
- `turtle` graphics drawn in the output panel
- Syntax highlighting, line numbers, auto-indent and bracket matching
- Symbol key bar for phones (Tab, `:`, `()`, `[]`, quotes, `#`, Undo/Redo)
- Multiple files, saved automatically on your device
- Open `.py` files from your phone, or copy your code to submit or back up
- 7 built-in examples: grade calculator, guessing game, OOP, recursion, turtle and more
- Light and dark mode

## Quick start

1. Open **https://genersiddayao.github.io/pymobile/** on your phone and tap **Launch the app**.
2. Type your code, or open the menu (☰) and pick an example.
3. Tap the green **Run** button. On a laptop, press **Ctrl + Enter**.

```python
name = input("What's your name? ")
print(f"Hello, {name}! Welcome to Python.")
```

Tip: use your browser's **Add to Home screen** option so it opens like an app.

## What's supported

| Works | Not available |
| --- | --- |
| Core Python 3: variables, strings, f-strings, lists, dicts, sets, loops, functions, classes, exceptions | numpy, pandas, matplotlib and other pip packages |
| `input()` and `print()` | Reading/writing files with `open()` |
| `math`, `random`, `time`, `datetime`, `string`, `re` | Internet access from scripts |
| `collections`, `itertools`, `copy`, `bisect`, `textwrap` | `json`, `functools`, `heapq`, `decimal`, `fractions`, `statistics` |
| `turtle` graphics | Tkinter, Kivy and other GUI toolkits |

For numpy or pandas, use Google Colab or a computer with Python installed.

## Good to know

- The page needs internet the first time it loads. After that, your scripts run on the phone itself.
- Your files are saved in your browser on that device. Clearing browser data or switching phones means losing them, so use **Copy code** to back up important work.
- **Seeing a page that only says "pymobile"?** Your browser has an old saved copy. Open the link in a private/incognito tab or refresh.

## How it's built

Static files hosted on GitHub Pages: `index.html` is the landing page and `app/index.html` is the app.

- [Skulpt](https://skulpt.org/) runs Python in the browser
- [CodeMirror 5](https://codemirror.net/5/) powers the code editor
- No server, no database, no tracking

## About

Developed by **Generino P. Siddayao** (Sir Gener), faculty member of the College of Information and Computing Sciences, Cagayan State University – Carig Campus, Tuguegarao City, Philippines.

Found a bug or have a feature idea? Open an [issue](https://github.com/genersiddayao/pymobile/issues), or tell your instructor.
