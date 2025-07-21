
# Git Basic Guide

This guide will help you get started with Git, including installing Git, cloning a repo, configuring your Git environment, and basic Git commands.

---

## 1. How to Install Git

Download and install Git from the official website:  
[https://git-scm.com/downloads](https://git-scm.com/downloads)

---

## 2. How to Clone a Repository

```bash
git clone https://github.com/username/repository.git
````

Replace the URL with your repository link.

---

## 3. Configure Your Git Repository

Set your username:

```powershell
git config --global user.name "hariram7405"
```

Set your email:

```powershell
git config --global user.email "hariram7405@gmail.com"
```

---

## 4. Basic Git Commands

* **git add** : Stage files for commit
  Example:

  ```bash
  git add filename.txt
  ```

* **git commit** : Commit staged changes
  Example:

  ```bash
  git commit -m "your commit message"
  ```

* **git status** : Check the status of your repo

* **git diff** : See changes not yet staged

* **git push** : Push changes to remote repository

* **git checkout** : Switch branches
  Example:

  ```bash
  git checkout main
  ```

* **git branch** : List branches

---

## 5. Handling Git Conflicts

If you face conflicts:

1. Edit conflicting files (e.g. `index.html`) to fix conflicts
2. Stage the fixed files:

   ```bash
   git add index.html
   ```
3. Commit your changes:

   ```bash
   git commit -m "Fix conflict in index.html"
   ```
4. Push your changes:

   ```bash
   git push
   ```

---

## 6. Using Git Stash

`git stash` temporarily saves your changes without committing:

```bash
git stash
git pull
git stash pop
```

This is useful to pull remote changes without committing your local unfinished work.

---

## 7. Viewing Git Log

To see the history of commits:

```bash
git log
```

---

Feel free to expand this guide as you learn more!

---

**Author :Hari Ram L**
```
