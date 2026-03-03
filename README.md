# Git Practice Repository
This repository contains all the Git Commands I have practiced
---

## 🔹 Basic Commands

- `git init` → Initialize a new repository
- `git status` → Check current repo status
- `git add <file>` → Stage specific file
- `git add .` → Stage all changes
- `git commit -m "message"` → Create a commit
- `git log` → View commit history
- `git log --oneline` → Compact history view

---

## 🔹 Branching

- `git branch` → List branches
- `git branch <branch-name>` → Create branch
- `git checkout <branch-name>` → Switch branch
- `git checkout -b <branch-name>` → Create + switch
- `git branch -d <branch-name>` → Delete branch

---

## 🔹 Merging

- `git merge <branch-name>` → Merge branch into current branch
- Fast-forward merge
- Manual merge conflict resolution

---

## 🔹 Remote Repository

- `git remote -v` → View remote repo
- `git remote add origin <repo-link>` → Connect local to GitHub
- `git push -u origin main` → Push to GitHub
- `git pull origin main` → Pull from GitHub
---

## 🔹 Reset

- `git reset --soft HEAD~1`
- `git reset HEAD~1`
- `git reset --hard HEAD~1`

Learned difference between soft, mixed, and hard reset.

---

## 🔹 Revert

- `git revert HEAD`
- `git revert <commit-id>`

Understood safe undo using revert.

---
## 🔹 Git commit --Amend
- `git commit --amend`

---

## 🔹 Git cherry pick
- `git cherry-pick <commit-hash>`
