# Git Commands  

Git was developed by **Linus Torvalds** to manage the Linux project.  

---

## Configuration  
- `git config user.name "Name"` → Sets username for commits  
- `git config user.email "Email"` → Sets email for commits  
- `git config --list` → Shows current configuration  

---

## Start a Repo  
- `git init` → Initialize Git in current folder  
- `git clone "Link"` → Clone a repo from a remote source  

---

## Workflow  
- `git status` → Shows status of working directory  
- `git add "File Name"` → Stages a specific file for commit  
- `git add .` → Stages all files for commit  
- `git commit -m "Message"` → Commits staged files with a message  

---

## History  
- `git log` → Shows commit history  
- `git log --oneline` → One-line view of commit history  
- `git diff` → Shows changes not yet staged  
- `git diff --staged` → Shows changes that are staged  

---

## Branching and Merging  
- `git branch` → Shows all branches  
- `git branch "Branch Name"` → Creates a new branch  
- `git checkout "Branch Name"` → Switch to the branch  
- `git checkout -b "Branch Name"` → Creates and switches to a branch  
- `git merge "Branch Name"` → Merges branch into current branch  

---

## Remote Repositories  
- `git remote -v` → Show remote repositories  
- `git remote add origin "Link"` → Adds a remote repository  
- `git fetch` → Downloads updates from remote repo  
- `git pull` → Fetches and merges changes from remote  
- `git push` → Pushes local commits to remote  
- `git push -u origin "Branch"` → Pushes and sets default upstream branch  

---

## Undoing Changes  
- `git checkout -- "File"` → Discards changes in a file (unstaged)  
- `git reset "File"` → Unstages a staged file  
- `git reset --hard` → Resets working directory & staging area to last commit  
- `git revert "Commit Id"` → Creates a new commit that undoes a specific commit  

---

## Stashing  
- `git stash` → Temporarily saves changes without committing  
- `git stash list` → Shows stashed changes  
- `git stash apply` → Applies the latest stash  
- `git stash pop` → Applies and removes the latest stash  
