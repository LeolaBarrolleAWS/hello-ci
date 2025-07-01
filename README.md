# Python CI/CD Pipeline with GitHub Actions

This project demonstrates a basic CI/CD pipeline for a Python application using GitHub Actions.

## Features

- GitHub Actions workflow (`python-ci.yml`) triggered on code push
- Automated installation of dependencies via `requirements.txt`
- Runs tests and validates the application
- Designed for rapid feedback in development

## Workflow Overview

- **Trigger:** On push to `main`
- **Jobs:**
  - Set up Python 3.9
  - Install dependencies
  - Run unit tests
  - Output build status

## Folder
