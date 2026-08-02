# Git_Notes
  Welcome to my git Notes repository.
  Hear I am Learning Git from Biginner to Advance

  -----
  ## 📚 Table of Contents

1. What is Git?
2. Version Control System (VCS)
3. Git vs GitHub
4. Git workflow
5. Git Installation/ Configuration
6. Git Commands
7. Branching
8. Merging
9. Git Stash
10. GitHub


    
# What is a Git?
Git is a **Distributed Version Control System (DVCS)**
 - Track change in file
 - manage different version of a project
 - collaborate with other devlopers
 - Restored previous version if needed 
## Real -Life -Example 
 Imaging you are write a project report.
 Day 1 ---> version 1
 Day 2 --> Version 2
 Day 3 --> version 3
 if Version 3 contains a mistake .
 git allows you to return to version 2 easily.

## Key Feture 
- Track Change
- Version history
- Branching
- collaboration
- Backup
## Advantage
 - Free and open source
 - fast
 - Secure
 - cross plateform (Linux,Windows,macos)


# step 2: Version control System (VCS)
## what is Version a version control system (VCS)?
 A **Version Control System** is a Tool that track  change in file stores different Version and allows You to store previous Version Whenever needed
 ### Example 
  version 1 --> First Project 
  version 2 --> Added Login Page 
  version 3 --> Fixed Buges
  Version 4 --> Added Dashboard

---
# Types of Version Control System 
1. Local Version Control System(LVCS)
2. Centralized Version Control System
3. Distributed Version Control System

---
## What is Git?

Git is a Distributed Version Control System (DVCS).

It is used to:
- Track changes in files
- Manage project versions
- Work offline
- Restore previous versions
- Collaborate with developers

---

## What is GitHub?

GitHub is a Cloud-based platform that hosts Git repositories online.
It is used to:
- Store Git repositories online
- Share projects
- Collaborate with teams
- Manage open-source projects
- Create Pull Requests
--
## Git vs GitHub
| Git | GitHub |
|------|---------|
| Git is a Version Control System. | GitHub is a Cloud Platform. |
| Works on your local computer. | Stores repositories online. |
| Can work without the internet. | Internet is required for syncing. |
| Tracks file changes. | Hosts and shares Git repositories. |
| Developed by Linus Torvalds. | Owned by Microsoft. |
-----


## Git Workflow

Working Directory
        │
   git add
        │
        ▼
 Staging Area
        │
 git commit
        │
        ▼
 Local Repository
        │
  git push
        │
        ▼
 Remote Repository (GitHub)

---
### Git install and configuration
1. install a git from the official web site.
2. Run and Install .
3. Keep The default setting and click a Next.
4. Finish the installaction
## check a version 

 Open  a Terminal or Commend Prompt and Run :
 ```bash
 git --version
 ```
 Example Output :
 ```bash
 git Version 2.50.1
 ```
## configure Git 
After installing Git , configure your username and email.
### set Username
```bash
git config --global user.name"Abhishek Kushwaha"
```
### Set Email 
```bash
git config --global user.email"MY_email@gmail.com"
```
### check configuration
```bash
git config --list
```
## Git commend

### What is repository?
 A repository is a storage location where Git keep all the files folder and the complete history of your project.
 ## Types of repository
 ### 1. Local Repository
  - stored your computer created using git.
### 2. Remote Repository
  - stored on platform like Github.
 ## what is git init?
  the `git init` command created a new Git repository in your project folder.
  Commend:
  ```bash
   git init
  ```
output:
```text
Instalized empoty git repository
```
## What is git status?

The git status command shows the current state of your repository.

Command:
```
git status
 ```
# Git Commands Cheat Sheet

## Repository

git init → Create a new Git repository.

git clone <url> → Copy a remote repository to your local machine.

git status → Show the current status of the repository.

git add <file> → Add a specific file to the staging area.

git add . → Add all files to the staging area.

git restore --staged <file> → Remove a file from the staging area.

git commit -m "message" → Save staged changes with a commit message.

git log → Show commit history.

git diff → Show differences between file versions.

---

## Branch

git branch → List all local branches.

git branch <branch-name> → Create a new branch.

git switch <branch-name> → Switch to another branch.

git switch -c <branch-name> → Create and switch to a new branch.

git checkout <branch-name> → Switch to another branch (older command).

git checkout -b <branch-name> → Create and switch to a new branch.

git merge <branch-name> → Merge a branch into the current branch.

git branch -d <branch-name> → Delete a local branch.

git branch -D <branch-name> → Force delete a local branch.

git branch -a → Show all local and remote branches.

---

## Remote Repository

git remote add origin <url> → Connect a local repository to GitHub.

git remote -v → Show remote repository URLs.

git remote set-url origin <url> → Change the remote repository URL.

git push -u origin main → Push code and set upstream branch.

git push origin --delete <branch-name> → Delete a remote branch.

git pull → Download and merge latest changes.

git fetch → Download changes without merging.

---

## Stash

git stash → Save uncommitted changes temporarily.

git stash list → Show all saved stashes.

git stash show → Show stash details.

git stash apply → Apply a stash without deleting it.

git stash pop → Apply and remove the latest stash.

git stash clear → Delete all stashes.

git stash branch <branch-name> → Create a branch from a stash.

---

## Reset & Revert

git reset --hard → Reset project to a previous commit.

git revert <commit-id> → Undo a commit by creating a new commit.

---

## Cherry-pick

git cherry-pick <commit-hash> → Copy a specific commit to the current branch.

---

## Tags

git tag → List all tags.

git tag <tag-name> → Create a new tag.

git show <tag-name> → Show tag details.


 




 

  
  

