# Quick setup, if you've done this kind of thing before

SSH: git@github.com:user/repo.git
HTTPS: https://github.com/user/repo.git

## Create a new repository on the command line

```bash
echo "# Mockup" >> README.md
git init
git add README.md
git commit -m "First commit message" -m "First commit description"
git branch -M master
git remote add origin https://github.com/user/repo.git
git push -u origin master
```

## Push an existing repository from the command line

```bash
git remote add origin https://github.com/user/repo.git
git branch -M master
git push -u origin master
```
