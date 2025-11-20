# Github-Spark


## Setup
```bash
# Configure Git with your name and email
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```
## Basic Commands
```bash
# Initialize a new Git repository
git init

# Clone a repository
git clone https://github.com/username/repository.git

# Check status of changes
git status

# Add files to staging area
git add filename.txt

# Commit changes with a message
git commit -m "Commit message"

# View commit history
git log
```

## Branching

```bash
# List branches
git branch

# Create a new branch
git branch feature-branch

# Switch to a branch
git checkout feature-branch

# Create and switch to new branch
git checkout -b feature-branch
```

## Merging 

```bash 
# Merge a branch into current branch
git merge feature-branch

# Resolve conflicts if any
```

## Remote Repositories

```bash
# Add remote repository
git remote add origin https://github.com/username/repository.git

# Push changes to remote master branch
git push origin master

# Pull changes from remote repository
git pull origin master
```
