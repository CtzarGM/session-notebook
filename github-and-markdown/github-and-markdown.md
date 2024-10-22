# Markdown
---
### Markdown Cheatsheet

[Markdown CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


# Git & GitHub
---
### Git Cheatsheet
[Git CheatSheet](https://training.github.com/downloads/github-git-cheat-sheet/)

### How to roll back changes
 command | effect 
 --- | ---
 git branch -d branch_name | deletes the local branch_name
 git push origin --delete remote_branch_name | deletes the remote_branch_name
 git reset --hard commit_hash | deletes all recent commits untill the specified (not including) commit_hash
 git push --force | forcibly pushes all local changes to the remote repository

### Git branch commands

| command                      | effect                               |
| ---------------------------- | ------------------------------------ |
| `git switch -c <branchname>` | create a new branch and switch to it |
| `git switch <branchname>`    | switch branches                      |
| `git branch`                 | list your branches                   |
| `git branch -a`              | list all branches (local and remote) |
| `git branch -d <branchname>` | delete a branch                      |
