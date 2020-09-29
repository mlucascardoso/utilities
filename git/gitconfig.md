# Git config (.gitconfig)

```bash
[user]
	email = your_mail@mail.com
	name = Your Name
[credential]
	helper = store
[core]
	editor = code --wait
[alias]
  s = !git status -s
  c = !git add --all && git commit -m
  l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
  cm = !git checkout master && git pull origin master
  pu = !git pull origin
  po = !git push origin
```
