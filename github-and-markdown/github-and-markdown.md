# Markdown

## Headers

```
#       H1
##      H2
###     H3
####    H4
#####   H5
######  H6
```

# Git & GitHub

## How to roll back changes

git branch -d branch_name                    : deletes the local branch_name
git push origin --delete remote_branch_name  : deletes the remote_branch_name
git reset --hard commit_hash                 : deletes all recent commits untill the specified (not including) commit_hash
git push --force                             : forcibly pushes all local changes to the remote repository. 