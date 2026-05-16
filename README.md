# Assignment on Module 2 (Git & GitHub)

This repository has been created to demonstrate Git and GitHub concepts. It serves as a space for learning, testing, and exploring both command-line operations and GitHub's graphical interface.

## Git Commands I've Learned

### Setup
```
git config --global user.name "Name"
git config --global user.email "email@mail.com"
git init
git branch -m master main  //If repo started locally and has master branch instead of main
git clone <repoURL>
```

### Staging & Committing
```
git status
git add <FileName>
git commit -m "Commit Message"
git commit --amend -m "Commit Message"
```

### Branching
```
git branch
git branch -D <BranchName>
git checkout -b <NewBranchName>
git checkout <ExistingBranchName>
git push origin --delete <BranchName>
```

### Inspection & History
```
git log
git show HEAD
git diff
git checkout <CommitHash>
git reset <FileName>
```

### Remote & Push
```
git remote add origin <repoURL>
git remote -v
git push origin main
```
