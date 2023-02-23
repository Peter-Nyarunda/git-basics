# Git and GitHub Process Practise
---

# _A brief introduction to Git_
---
Real life projects often require multiple devs working in parallel. A version control system (Git) is useful in handling code updates, their history and changes. Git also enables branching and merging.

This repository aims at practicing and refreshing a couple of Git and GitHub practices.
It covers:
-   The Trunk workflow which is
  -   Initialize Git repository in local machine `git init`.
  -   Add files to be tracked by Git `git add 'my-file'`.
  -   Stage changes to be commited `git add 'my-file'`.
  -   Finding out information regarding what files are modified and those that are in the staging area using `git status`.
  -   Commit changes with appropriate commit message `git commit -m 'commit message'`.
  -   Printing out all the commits that are completed using `git log`.
  -   Pushing all code from local repository to the remote repository on GitHub using `git push -u origin master`
  -   Using `git pull origin master` to pull the latest changes from the remote repository to local
  -   Cloning existing repositories to your PC using `git clone [repository url]`.
  
# _Setting up local repos and working with remotes_
---
Follow the following simple steps to create your first local repository! (Please note that you should have a Git version compatible with your device installed prior to this).

-  In your computer, create a folder for your project. Let's name it myProject.
-  Go into myProject and add a local git repository using the following commands `cd myProject` then, `git init`
-  Create a new file in the folder and name it `demo.txt` and type in the following code in it `Hello Git`
-  In the command line, use `git add demo.txt` to stage the file 
-  Commit the file using `git commit -m "initial commit"` 

To create a remote repository, first create a github account, then follow these steps.
-  On the github homepage, click on start a project to create a new repository.
-  Name the repository `myProject` and click on create repository.
-  Open the new repository you just created and click on the code section to reveal the repository url.
-  Copy this URL and use `git remote add origin [repository url]` 
-  To push all the code from the local repository to the remote one, use `git push -u origin master`

There you go! 

# _Git branching_
---

What is a branch? _A branch is a pointer to the latest commit in the git repository_ . Multiple branches are required to support parallel project development. Create a new branch using the command `git branch myBranch`. This command creates a branch called myBranch. In order to switch from the main branch to myBranch, use `git checkout myBranch`. In order to list all the branches in local, the `git branch` command comes in handy. 





