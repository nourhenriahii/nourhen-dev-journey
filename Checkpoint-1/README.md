# Checkpoint: Git & GitHub Project

## 1. Create a folder called learn_git
```bash
mkdir learn_git
```

## 2. Cd into the learn_git folder
```bash
cd learn_git
```
![mkdir and cd](screenshots/1-mkdir-cd.png)

---

## 3. Create a file called third.txt
```bash
touch third.txt
```
![touch third.txt](screenshots/2-touch-third.png)

---

## 4. Initialize an empty git repository
```bash
git init
```
![git init](screenshots/3-git-init.png)

---

## 5. Add third.txt to the staging area
```bash
git add third.txt
```
![git add third.txt](screenshots/4-git-add-third.png)

---

## 6. Commit with the message "adding third.txt"
```bash
git commit -m "adding third.txt"
```
![commit third.txt](screenshots/5-git-commit-third.png)

---

## 7. Check out your commit with git log
```bash
git log
```
![git log](screenshots/6-git-log-first.png)

---

## 8. Create another file called fourth.txt
```bash
touch fourth.txt
```
![touch fourth.txt](screenshots/7-touch-fourth.png)

---

## 9. Add fourth.txt to the staging area
```bash
git add fourth.txt
```
![git add fourth.txt](screenshots/8-git-add-fourth.png)

---

## 10. Commit with the message "adding fourth.txt"
```bash
git commit -m "adding fourth.txt"
```
![commit fourth.txt](screenshots/9-git-commit-fourth.png)

---

## 11. Remove the third.txt file
```bash
rm third.txt
```
![rm third.txt](screenshots/10-rm-third.png)

---

## 12. Add this change to the staging area
```bash
git add .
```
![git add all](screenshots/11-git-add-all.png)

---

## 13. Commit with the message "removing third.txt"
```bash
git commit -m "removing third.txt"
```
![commit remove third.txt](screenshots/12-git-commit-remove.png)

---

## 14. Check out your commits using git log
```bash
git log
```
![full git log](screenshots/13-git-log-full.png)

---

## 15. Change global settings to core.pager=cat
```bash
git config --global core.pager "cat"
```
![git config pager](screenshots/14-git-config-pager.png)

---

## 16. List all global configurations for git
```bash
git config --global --list
```
![git config list](screenshots/15-git-config-list.png)

---

## 17. Create a repository on GitHub
![github repo](screenshots/16-github-repo.png)

---

## 18. Connect local repository to GitHub
```bash
git remote add origin git@github.com:nourhenriahii/gomycode-test-.git
```
![git remote add](screenshots/17-git-remote-add.png)

---

## 19. Push code to GitHub
```bash
git push -u origin main
```
![git push](screenshots/18-git-push.png)

---

## 20. Final result on GitHub
![github final](screenshots/19-github-final.png)