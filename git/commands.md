# Commands

## Prune local branches except master
```bash
git branch --merged master | grep -v '^[ *]*master$' | xargs git branch -d
```
