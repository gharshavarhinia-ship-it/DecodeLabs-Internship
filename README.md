## Project Overview

This repository contains the implementation of **DecodeLabs Industrial Training - DevOps Project 2 and Project 3**.

The objective of these projects is to understand the fundamentals of **Git Version Control** and **Continuous Integration/Continuous Deployment (CI/CD)** using **GitHub Actions**.

Project 2 focuses on managing source code using Git and GitHub, while Project 3 demonstrates how to automate software workflows whenever code is pushed to a GitHub repository.

---

# Project Objectives

## Project 2 – Version Control with Git

- Initialize a Git repository
- Track file changes
- Stage project files
- Create commits
- Connect a local repository to GitHub
- Push changes to a remote repository
- Understand the Git workflow

## Project 3 – CI/CD Pipeline Basics

- Understand CI/CD concepts
- Create a GitHub Actions workflow
- Automate project execution on every push
- Learn pipeline stages
- Understand workflow automation

---

# Tools Used

- Git
- GitHub
- GitHub Actions
- Visual Studio Code
- Python 3.13
- Windows Command Prompt

---

# Repository Structure

```
DevOps-Projects/
│
├── README.md
├── .gitignore
├── app.py
├── requirements.txt
├── git_commands.txt
├── workflow.md
├── git_cheatsheet.md
├── ci_cd_concepts.md
├── pipeline_workflow.md
└── .github/
    └── workflows/
        └── python-ci.yml
```

---

# Project 2 - Git Workflow

Git helps developers keep track of every change made to a project.

Workflow:

```
Working Directory
        │
        ▼
git add
        │
        ▼
Staging Area
        │
        ▼
git commit
        │
        ▼
Local Repository
        │
        ▼
git push
        │
        ▼
GitHub Repository
```

---

# Project 3 - CI/CD Workflow

GitHub Actions automatically executes a workflow whenever code is pushed to GitHub.

Workflow:

```
Developer
     │
     ▼
git push
     │
     ▼
GitHub Repository
     │
     ▼
GitHub Actions Triggered
     │
     ▼
Checkout Repository
     │
     ▼
Setup Python
     │
     ▼
Install Dependencies
     │
     ▼
Run Python Program
     │
     ▼
Workflow Completed Successfully
```

---

# GitHub Actions Pipeline

The workflow is stored inside:

```
.github/workflows/python-ci.yml
```

Whenever code is pushed to the **main** branch, GitHub automatically:

1. Checks out the repository
2. Creates an Ubuntu runner
3. Installs Python
4. Installs project dependencies
5. Executes the Python application
6. Reports Success or Failure

---

# Git Commands Used

| Command | Description |
|----------|-------------|
| git init | Initialize Git repository |
| git status | Check repository status |
| git add . | Stage all files |
| git commit -m "message" | Save project snapshot |
| git log | View commit history |
| git remote add origin URL | Connect GitHub repository |
| git branch -M main | Rename default branch |
| git push -u origin main | Upload repository |
| git pull | Download latest changes |
| git diff | Compare file changes |

---

# CI/CD Concepts Learned

- DevOps
- Version Control
- Continuous Integration (CI)
- Continuous Delivery (CD)
- Continuous Deployment
- GitHub Actions
- Workflow
- Jobs
- Steps
- Runners
- Pipeline Automation

---

# Learning Outcomes

After completing these projects, I learned:

### Git

- Repository creation
- Tracking file changes
- Staging files
- Creating commits
- Managing GitHub repositories
- Version control workflow

### CI/CD

- Creating GitHub Actions workflows
- Understanding YAML configuration
- Running automated workflows
- Pipeline stages
- Automation using GitHub Actions
- Continuous Integration concepts

---

# Project Outcome

Successfully implemented:

- Git Version Control
- GitHub Repository Management
- GitHub Actions Workflow
- Automated Python Execution
- Continuous Integration Pipeline

The workflow executes automatically whenever code is pushed to the repository.

---

# Future Improvements

- Add automated testing using PyTest
- Integrate code quality checks (Linting)
- Deploy application automatically
- Add Docker support
- Integrate cloud deployment

---

# Author

**Name:** Harshavarhini G

**Training Program:** DecodeLabs Industrial Training

**Projects:**
- Project 2 – Version Control with Git
- Project 3 – CI/CD Pipeline Basics
