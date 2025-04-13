# Simple DevOps Project

This is a demonstration of Git best practices in a DevOps project.

## Project Description
A simple Python web application built with Flask to demonstrate Git workflows.

## Features
- Basic web server
- Health check endpoint
- Simple homepage

## Installation
1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate venv: `source venv/bin/activate` (Linux/Mac) or `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Run the app: `python app.py`

## Branching Strategy
- `main`: Production-ready code
- `dev`: Development integration branch
- `feature/*`: Feature development branches

## Initializing a Git Repository
We started by installing Git and initializing it within a project. When you run the initialization command, Git creates a hidden .git folder that stores all version history data.
```bash
git init
```
## Setting Up a Remote Repository
Establishing a remote repository is crucial for backing up your local work and collaborating with team members. Connect your local repository to a remote server with the following command:
that stores all version history data.
```bash
git remote add origin https://.../[name].git
```

## Pushing Local Changes
With the remote repository in place, you can push your local changes to the remote server, ensuring your work is safely stored and shared:
```bash
git push origin master
```

## Using Rebasing
Rebasing is an alternative to merging that rewrites the commit history. Use the simple rebase command as shown:
```bash
git rebase feature
```