# Programming Fundamentals — Module 1 Lab: Lab Setup

Set up a standard Python development environment on your own Windows laptop and
run everything from the command line.

**Handout:** [Module 1 Lab - Student Guide - Lab Setup.pdf](Module%201%20Lab%20-%20Student%20Guide%20-%20Lab%20Setup.pdf)
(editable source: the `.docx` next to it)

## What you will set up

| Tool | Version |
|------|---------|
| Python | 3.13.15 (64-bit Windows installer from python.org — not 3.14) |
| Visual Studio Code | User Installer, with the Microsoft Python extension |
| Git for Windows | current (2.55.0 at the time of writing) |
| GitHub | your account |
| Virtual environment | `python -m venv .venv` inside your `PythonCourse` folder |

No Anaconda, no Colab, and no packages to install for this lab.

## Files

| File | Purpose |
|------|---------|
| `Module 1 Lab - Student Guide - Lab Setup.pdf` | The handout — follow it part by part |
| `Module 1 Lab - Instructor Guide - Lab Setup.pdf` | For instructors: preparation, timing, common issues and fixes |
| `hello.py` | The first program from Part 12 |
| `.gitignore` | Keeps `.venv/` and `__pycache__/` out of Git (Part 17) |

## Quick check at the end of the lab

In the VS Code terminal (Command Prompt, not PowerShell), from your `PythonCourse` folder:

```bat
.venv\Scripts\activate
python --version
python hello.py
```

Expected:

```text
Python 3.13.15
Hello, Python!
My Python environment is working.
```

## Guide version

v1.1 — every step tested on Windows 10 with Python 3.13.15 on 26 Sep 2026; links
and current versions checked the same day. Main change from v1.0: the VS Code
terminal is switched to Command Prompt before activating `.venv`, because
PowerShell's default policy blocks the activation script.
