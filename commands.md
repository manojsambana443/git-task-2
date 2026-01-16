# Git & GitHub – Commands Log

This file contains all the Git commands I practiced while completing Task 2. These commands helped me understand version control, branching, merging, and rollback.

---

## 1. Git Installation & Configuration

```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
git config --list
```

---

## 2. Initializing a Local Repository

```bash
mkdir git-task-2
cd git-task-2
git init
ls -a
```

---

## 3. Creating Files & First Commit

```bash
touch file1.txt
nano file1.txt
git status
git add file1.txt
git commit -m "Initial commit with file1"
```

---

## 4. Connecting Local Repo to GitHub

```bash
git remote add origin <your-repo-url>
git branch -M main
git push -u origin main
```

---

## 5. Creating a New Branch

```bash
git checkout -b feature-branch
nano file1.txt
git status
git add file1.txt
git commit -m "Updated file1 in feature branch"
```

---

## 6. Merging Branch to Main

```bash
git checkout main
git merge feature-branch
git push
```

---

## 7. Rollback Practice

```bash
git log
git reset --hard <commit-id>
git checkout <commit-id>
```

---

## Notes

All the above commands were executed on a Linux terminal. Screenshots of commit history and outputs are stored in the screenshots folder.
