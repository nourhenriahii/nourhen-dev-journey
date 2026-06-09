# 🧠 Learn Git — Checkpoint Project

> A hands-on Git & GitHub workflow practice project by **Nourhen Riahi**

---

## 📖 What is Git?

Git is a **version control system** that tracks changes in your files over time. It lets you save snapshots of your project (called *commits*), go back to previous versions, and collaborate with others without losing work.

## 🐙 What is GitHub?

GitHub is a **cloud platform** that hosts Git repositories online. It allows you to back up your code, share it with others, and collaborate on projects from anywhere.

---

## 📋 Project Overview

This repository documents a complete Git workflow exercise — from creating a local folder to pushing commits to GitHub. Each step is captured with a real terminal screenshot.

---

## ✅ Steps Completed

### 1. Create & Navigate to the Project Folder
```bash
mkdir learn_git
cd learn_git
```
![mkdir and cd](screenshots/1-mkdir-cd.png)

---

### 2. Create a File
```bash
touch third.txt
ls
```
![touch third.txt](screenshots/2-touch-third.png)

---

### 3. Initialize Git Repository
```bash
git init
```
![git init](screenshots/3-git-init.png)

---

### 4. Stage the File
```bash
git add third.txt
```
![git add third.txt](screenshots/4-git-add-third.png)

---

### 5. First Commit
```bash
git commit -m "adding third.txt"
```
![first commit](screenshots/5-git-commit-third.png)

---

### 6. View Commit History
```bash
git log
```
![git log](screenshots/6-git-log-first.png)

---

### 7. Create a Second File
```bash
touch fourth.txt
ls
```
![touch fourth.txt](screenshots/7-touch-fourth.png)

---

### 8. Stage the Second File
```bash
git add fourth.txt
```
![git add fourth.txt](screenshots/8-git-add-fourth.png)

---

### 9. Second Commit
```bash
git commit -m "adding fourth.txt"
```
![second commit](screenshots/9-git-commit-fourth.png)

---

### 10. Remove `third.txt`
```bash
rm third.txt
ls
```
![rm third.txt](screenshots/10-rm-third.png)

---

### 11. Stage the Deletion
```bash
git add .
```
> `git add .` stages **all changes** at once — including deletions, new files, and modifications.

![git add all](screenshots/11-git-add-all.png)

---

### 12. Third Commit
```bash
git commit -m "removing third.txt"
```
![commit remove](screenshots/12-git-commit-remove.png)

---

### 13. View Full Commit History
```bash
git log
```
![full git log](screenshots/13-git-log-full.png)

All 3 commits are visible in order:
- `adding third.txt`
- `adding fourth.txt`
- `removing third.txt`

---

### 14. Configure Git Pager
```bash
git config --global core.pager "cat"
```
> This makes `git log` print directly in the terminal instead of opening an interactive pager (like `less`).

![git config pager](screenshots/14-git-config-pager.png)

---

### 15. List Global Git Configurations
```bash
git config --global --list
```
![git config list](screenshots/15-git-config-list.png)

Output:
```
user.name=nourhenriahii
user.email=nourhenriahi11@gmail.com
core.pager=cat
```

---

### 16. Create GitHub Repository
Created a new public repository called `gomycode-test-` on GitHub.

![github repo](screenshots/16-github-repo.png)

---

### 17. Connect Local Repo to GitHub
```bash
git remote add origin git@github.com:nourhenriahii/gomycode-test-.git
```
![git remote add](screenshots/17-git-remote-add.png)

---

### 18. Push to GitHub
```bash
git push -u origin main
```
![git push](screenshots/18-git-push.png)

---

### 19. Final Result on GitHub
The repository is now live on GitHub with all commits.

![github final](screenshots/19-github-final.png)

---

## 💡 Key Differences Learned

| Command | What it does |
|---|---|
| `git add <file>` | Stages one specific file |
| `git add .` | Stages **all** changes in the folder |

---

## 🛠️ Commands Summary

| Command | Description |
|---|---|
| `git init` | Initialize a new local repository |
| `git add <file>` | Stage a specific file |
| `git add .` | Stage all changes |
| `git commit -m "..."` | Commit staged changes |
| `git log` | View commit history |
| `git config --global ...` | Set global Git configuration |
| `git remote add origin` | Link to a remote GitHub repo |
| `git push -u origin main` | Push local commits to GitHub |

---

## 📁 Repository Structure

```
learn_git/
├── fourth.txt
├── README.md
└── screenshots/
    ├── 1-mkdir-cd.png
    ├── 2-touch-third.png
    ├── 3-git-init.png
    ├── 4-git-add-third.png
    ├── 5-git-commit-third.png
    ├── 6-git-log-first.png
    ├── 7-touch-fourth.png
    ├── 8-git-add-fourth.png
    ├── 9-git-commit-fourth.png
    ├── 10-rm-third.png
    ├── 11-git-add-all.png
    ├── 12-git-commit-remove.png
    ├── 13-git-log-full.png
    ├── 14-git-config-pager.png
    ├── 15-git-config-list.png
    ├── 16-github-repo.png
    ├── 17-git-remote-add.png
    ├── 18-git-push.png
    └── 19-github-final.png
```

---

## 👤 Author

**Nourhen Riahi**  
  

---

*Checkpoint project — Git & GitHub Module* 🎓
