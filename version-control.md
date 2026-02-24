## Version Control with Git

This document outlines the essential Git commands used for tracking changes and collaborating on engineering projects.

# Initialization and Configuration

git init: Initializes a new Git repository in the current directory.

git config --global user.name "Sean Alvarado": Sets the username for commits.

git config --global user.email "your-email@example.com": Sets the email for commits.

# Basic Workflow

git status: Displays the state of the working directory and the staging area.

git add <file>: Adds a specific file to the staging area.

git add .: Stages all changes in the current directory.

git commit -m "Commit message": Saves the staged snapshot to the project history.

# Remote Repositories

git remote add origin <url>: Links the local repository to a remote server (like GitHub).

git push -u origin main: Uploads local content to the remote repository.

git pull origin main: Fetches and merges changes from the remote server to the local machine.