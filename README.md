# GIT-HOL-Assignment

This is Git Lesson assignment for DevKTOps DevOps Class.

**This is some bold text**

# Git Commands Cheat Sheet

## Configuration

### Configure user information for all local repositories

```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```


### Configure user information for the current repository
```
git config user.name "Your Name"
git config user.email "your.email@example.com"
```


## Repository Creation and Cloning

### Create a new repository locally
```
git init
```


### Clone an existing repository from a URL
```
git clone <repository_url>
```


## Branching and Merging

### Create a new branch
```
git checkout -b <branch_name>
```

### Switch to an existing branch
```
git checkout <branch_name>
```

### Merge changes from one branch into the current branch
```
git merge <source_branch>
```

## Staging and Committing

### Add changes to the staging area
```
git add <file_name>
```

### Commit changes in the staging area
```
git commit -m "Descriptive commit message"
```

### Push commits to a remote repository
```
git push <remote_name> <branch_name>
```

## Remote Repositories

### Add a remote repository
```
git remote add <remote_name> <repository_url>
```

### Fetch changes from a remote repository
```
git fetch <remote_name>
```

### Pull changes from a remote repository into the current branch
```
git pull <remote_name> <branch_name>
```

## Viewing Information

### View the status of changes
```
git status
```

### View the commit history
```
git log
git log --oneline
```


### View the differences between the working directory, staging area, and latest commit
```
git diff
```

## Miscellaneous

### Discard changes in the working directory
```
git checkout -- <file_name>
```

### Undo the last commit, keeping changes in the working directory
```
git reset HEAD~1
```

### Undo the last commit and discard changes
```
git reset --hard HEAD~1
```

### Remove untracked files from the working directory
```
git clean -f
```


### Remove untracked files and directories from the working directory
```
git clean -fd
```

**Feel free to customize this cheat sheet by adding or modifying commands as needed!**