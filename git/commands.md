# Commands

## Add modified or new files to staged area
```bash
git add <file_name>

Example:
git add inicio.js

You can also use the shortcut '.' to add all files:
git add .
```

## Commit staged area files
```bash
git commit -m "<your_message_here>"

Example:
git commit -m "feat: add inicio.js logic"
```

## Push modified files to origin
```bash
git push origin <branch_name>

Example:
git push origin master

You can also use the `-u` flag once to tell git to sync the branch automatically for the future push:
git push -u origin master

And after that just:
git push
```

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

