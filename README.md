# Quick setup -- if you've done this kind of thing before

## Create a new repository on the command line

```bash
echo "# Mockup" >> README.md
git init
git add README.md
git commit -m "First commit message" -m "First commit description"
git branch -M master
git remote add origin https://github.com/yrifl/mockup.git
git push -u origin master
```

## Push an existing repository from the command line

```bash
git remote add origin https://github.com/yrifl/mockup.git
git branch -M master
git push -u origin master
```

## Create a new branch

```bash
git checkout -b feature-branch-descriptive

```

## The Github command line

### The use of gh repo

Archiving a repository:

```bash
gh repo archive user/repo
```

Cloning a repository:

```bash
gh repo clone user/repo
```

Delete a repository:

```bash
gh repo delete user/repo
```

Open current repository in browser:

```
gh browse
#=> Open the home page of the current repository

gh browse src/
#=> Open the source directory of the current repository

gh browse --settings
#=> Open repository settings
```




