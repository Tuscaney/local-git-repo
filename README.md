# Local Git Repository Assignment

This project demonstrates working with Git and GitHub, including repository initialization, committing changes, using branches, and understanding merge vs. rebase.

---

## Part 1: Initialize Git Repository

**Command:**
```bash
git init

![Git Init](hhttps://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-init.png)

## Part 2: Adding File and Committing Changes

**Commands:** 

touch index.html
git add index.html
git commit -m "Add index.html"

![Git Index](https://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-index.png)
![Git Commit](https://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-commit.png)


## Part 3: Connecting to GitHub and Pushing Chnges

**Commands:**

git remote add origin https://github.com/Tuscaney/local-git-repo.git
git push -u origin main

![Git Connect](https://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-connect.png)
![Git Push](hhttps://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-push.png)


## Part 4: Created New Branch

**Commands:**

git branch dev
git checkout dev
# or
# git switch -c dev

![Git Branch](https://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-branch-dev.png)
![Git Changes](hhttps://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-changes.png)

## Part 5: Merge and Rebase

**Commands:**

git checkout main
git merge dev
git checkout dev
git rebase main

![Git Update](https://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-update.png)
![Git Switch](https://raw.githubusercontent.com/Tuscaney/local-git-repo/main/Screenshots/git-switch.png)


## Notes
- All screenshots are stored in the Screenshots/ folder.
