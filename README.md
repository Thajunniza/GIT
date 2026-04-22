# 📘 Useful Git Commands

A handy reference for commonly used Git commands, from basic setup to advanced workflows.

---

## 🚀 Getting Started

```bash
git init
git clone <repository-url>
```

---

## ⚙️ Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list
```

---

## 📂 Repository Basics

```bash
git status
git add <file>
git add .
git rm <file>
```

---

## ✅ Committing

```bash
git commit -m "Commit message"
git commit -am "Commit message"
git commit --amend --no-edit
```

---

## 🌿 Branching

```bash
git branch
git branch <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
git branch -d <branch-name>
```

---

## 🔁 Merging & Rebasing

```bash
git merge <branch-name>
git rebase <branch-name>
git rebase --abort
```

---

## 🗃 Stashing

```bash
git stash
git stash list
git stash apply
git stash drop
```

---

## 🌍 Remote Repositories

```bash
git remote -v
git remote add origin <repo-url>
git push origin <branch>
git pull origin <branch>
```

---

## ⏪ Undo & Fix Mistakes

```bash
git checkout -- <file>
git reset HEAD <file>
git reset --soft HEAD~1
git reset --hard HEAD~1
```

---

## 🔍 Logs & Inspection

```bash
git log
git log --oneline --graph --all
git show <commit-hash>
git diff
```

---

## 🏷 Tags & Releases

```bash
git tag
git tag v1.0.0
git push origin --tags
```

---

## ⚡ Useful Shortcuts

```bash
git fetch
git clean -fd
git blame <file>
git cherry-pick <commit-hash>
```

---

✅ Happy version controlling!
