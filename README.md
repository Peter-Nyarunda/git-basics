# Git and GitHub Process Practise
---

This repository aims at practicing and refreshing a couple of Git and GitHub practices.
It covers:
-   The Trunk workflow which is
  -   Initialize Git repository in local machine `git init`.
  -   Add files to be tracked by Git `git add 'my-file'`.
  -   Stage changes to be commited `git add 'my-file'`.
  -   Commit changes with appropriate commit message `git commit -m 'commit message'`.
  - Finding out information regarding what files are modified and those that are in the staging area using `git status`.
  - Printing out all the commits that are completed using `git log`.
  - Pushing all code from local repository to the remote repository on GitHub using `git push -u origin master`
  -  Using `git pull origin master` to pull the latest changes from the remote repository to local
  - Cloning existing repositories to your PC using `git clone [repository url]`.
  


# _A brief introduction to Git_
---
Real life projects often require multiple devs working in parallel. A version control system (Git) is useful in handling code updates, their history and changes. Git also enables branching and merging.

What is a branch? _A branch is a pointer to the latest commit in the git repository_ . Multiple branches are required to support parallel project development. Create a new branch using the command `git branch myBranch`. This command creates a branch called myBranch. In order to switch from the main branch to myBranch, use `git checkout myBranch`. In order to list all the branches in local, the `git branch` command comes in handy. 

