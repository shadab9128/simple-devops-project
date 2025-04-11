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