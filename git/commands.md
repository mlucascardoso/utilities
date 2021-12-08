# Commands

## Delete local branches except <branch_name>
```bash
git branch --merged <branch_name> | grep -v '^[ *]*<branch_name>$' | xargs git branch -d
```

## Prune origin branches
```bash
# method 1
git remote prune origin

# method 2
git fetch origin --prune

# method 3
git branch -r -d origin/devel
```

