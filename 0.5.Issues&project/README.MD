# Introduction to Git and GitHub

A beginner-friendly guide to help you use GitHub effectively in your learning journey — no prior programming experience required.

---

## What is Git?

**Git** is a version control system — it tracks every change you make to your files so you can go back to any previous version. Think of it as an "undo history" for your entire project.

Created by Linus Torvalds in 2005, Git lets you:

- Save snapshots of your work at any point (called **commits**).
- Experiment on separate **branches** without breaking your main project.
- Collaborate with others by **merging** everyone's changes together.

## What is GitHub?

**GitHub** is a website that hosts your Git projects online. It adds collaboration tools on top of Git — you can share code, review each other's work, track tasks, and more.

**Why it matters for your learning:**
- Your projects are backed up and accessible from anywhere.
- You build a public portfolio that shows your work.
- You learn the same workflow used by professional developers and AI teams worldwide.

---

## Getting Set Up

### 1. Create a GitHub account

Go to [github.com](https://github.com/) and sign up for a free account.

> If you are a student, apply for the [GitHub Student Developer Pack](https://github.com/education/students) — it gives you free access to premium tools including GitHub Copilot.

### 2. Install Git on your computer

- **Windows:** Download from [git-scm.com/downloads](https://git-scm.com/downloads) and run the installer.
- **Mac:** Open Terminal and run `git --version`. If Git is not installed, you will be prompted to install it.
- **Linux:** Run `sudo apt install git` (Ubuntu/Debian) or `sudo dnf install git` (Fedora).

### 3. Configure Git with your identity

Open your terminal (Command Prompt, PowerShell, or Terminal) and run:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Use the same email you used for your GitHub account.

---

## Key Concepts

| Term | What it means |
|------|---------------|
| **Repository (Repo)** | A folder tracked by Git. Contains your project files and their full history. |
| **Commit** | A saved snapshot of your changes. Each commit has a message describing what changed. |

