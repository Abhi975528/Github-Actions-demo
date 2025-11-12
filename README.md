# GitHub Actions Demo 🚀

This repository is a demo project to learn and experiment with **GitHub Actions** using a simple Python example.

## 🧠 Purpose

The goal of this repository is to:
- Understand how **GitHub Actions workflows** are structured.
- Practice setting up CI/CD pipelines that automatically test code.
- Explore workflow triggers and job steps in action.


## ⚙️ Project Overview

- **addition.py** → A simple Python script that defines and tests an `add(a, b)` function.
- **.github/workflows/first-actions.yml** → The GitHub Actions workflow that runs automatically when code is pushed or a pull request is made.

## 🧩 How It Works

When you push code or open a pull request:
1. GitHub Actions triggers the workflow defined in `first-actions.yml`.
2. The workflow sets up a Python environment.
3. It runs `addition.py` to ensure the `add()` function works correctly through the test.

## ▶️ Running Locally

If you want to test it manually:

```bash
python addition.py
