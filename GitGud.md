# Git Gud: A Quick Guide

Git is awesome when you "git gud" at it! This mini guide helps you level up your Git skills. 🚀

## 1. Learn Git Basics

### Essential Commands:
- **Clone a repository:**
  ```bash
  git clone <repo-url>
  ```
- **Commit your changes:**
  ```bash
  git add .
  git commit -m "your commit message"
  ```
- **Push your work:**
  ```bash
  git push origin <branch-name>
  ```

---

## 2. Branch Like a Pro
- Create a new branch for any new feature:
  ```bash
  git checkout -b feature/my-new-feature
  ```
- Switch between branches:
  ```bash
  git checkout main
  ```

---

## 3. Embrace Mistakes
- Undo your last commit:
  ```bash
  git reset HEAD~1
  ```
- Save "work in progress" without committing:
  ```bash
  git stash
  ```
- Reapply stashed changes:
  ```bash
  git stash apply
  ```

---

## 4. Collaborate Like a Wizard
- Fetch and merge the latest changes:
  ```bash
  git pull origin main
  ```
- Resolve merge conflicts like a hero:
  Use an editor to handle conflicts manually, then stage and re-commit.

---

## 5. Level-Up Git Tricks
- **Check who changed what (a.k.a detective mode):**
  ```bash
  git blame <file>
  ```
- **Inspect your commit history and flashy storytelling:**
  ```bash
  git log --oneline --graph --decorate
  ```
- **Unleash the power of aliases:**
  Add shortcuts to your `.gitconfig`:
  ```bash
  git config --global alias.hist "log --oneline --graph --decorate"
  ```

---

## 6. Fun Git "IRL" Commands:
- `git blame`: When you accidently break production...
- `git add`: Like tidying your desk after a long week.
- `git checkout`: When you sign up for your dream vacation.
- `git push`: Sharing your great ideas with the world!

---

**Now go forth and `git gud`, my friend!** 🎉