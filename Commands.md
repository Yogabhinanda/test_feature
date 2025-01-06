# Git Commands Guide

This document provides a comprehensive list of essential Git commands along with their descriptions. Use these commands to efficiently manage your Git repositories.

---

## Setting Up Git

### Set Global Username and Email (Locally)
Set your global username and email for Git configuration.
```bash
git config --global user.name "<your github username>"
git config --global user.email "<your email>"
```

---

## Repository Initialization and Cloning

### Initialize an Empty Git Repository
Start a new Git repository in your current directory.
```bash
git init
```

### Clone an Existing Git Repository
Clone a remote repository to your local machine.
```bash
git clone <repository URL>
```

---

## Adding and Committing Changes

### Add a Specific File to Git
Stage a specific file to include it in the next commit.
```bash
git add <filename>
```

### Add All Files to Git
Stage all files in the current directory.
```bash
git add .
```

### Commit All Staged Files
Record changes to the repository with a descriptive message.
```bash
git commit -m "<your commit message>"
```

### Restore a File from Being Modified to Tracked
Undo changes to a specific file and revert it to the tracked state.
```bash
git restore <filename>
git checkout <filename>
```

---

## Checking Repository Status

### Show Repository Status
Display the current state of the working directory and staging area.
```bash
git status
```

### Show Branches in the Repository
List all branches in the repository.
```bash
git branch
```

---

## Branch Management

### Create and Switch to a New Branch
Create a new branch and switch to it.
```bash
git checkout -b <branch name>
```

### Switch to an Existing Branch
Change to an existing branch.
```bash
git checkout <branch name>
```

### Remove a Branch from Git
Delete a branch locally.
```bash
git branch -d <branch name>
```

---

## Remote Repository Management

### Show Remote Origin URL
Display the remote URLs associated with the repository.
```bash
git remote -v
```

### Add Remote Origin URL
Link a remote repository to your local repository.
```bash
git remote add origin <your remote git URL>
```

### Remove Remote Origin URL
Remove the association with a remote repository.
```bash
git remote remove origin
```

### Fetch All Remote Branches
Retrieve updates from the remote repository without merging.
```bash
git fetch
```

---

## Pushing and Pulling Changes

### Push Local Changes to Remote Branch
Upload local commits to the specified branch on the remote repository.
```bash
git push origin <branch name>
```

### Pull Remote Changes to Local Branch
Download and integrate changes from the specified branch on the remote repository.
```bash
git pull origin <branch name>
```

---

## Checking Commit History

### View Git Commits and Logs
Display the commit history of the repository.
```bash
git log
