---
layout: post
title: "Priya's website, Launches Site"
date: 2019-01-31
---
Basic Git Commands

To start with the git, first, need to install the git bash.. https://git-scm.com/download/win
By clicking on above link one can install the git in their local machine(windows).
To verify whether git installed or not then Goto run→ type cmd → type  git --version.
The respective version of your git would display. Change to the respective folder where your repository resides in  local machine,right click on it select git bash.

Task
command
example
To tell the git who you are
git config --global user. name ""
------------------------------------
git config --global user.mail ""
git config --global user.name "kalpana123"
------------------------------------
Git config --global user.email
"kalpana@example.com"

To create a new local repository
git init
git init project-name
To create a working copy of the remote repository in our local machine.
git clone
git clone http://hithub.com/bob/example.git
To add files
git add 
git add sample.txt
To commit changes
git commit -m "commit message"
git commit -m "My first commit"
To check the status
git  status
git status
To change another directory in the same repository
cd to 
cd to .git
To list out the details of the files in a given repository
ls -la
ls -la(it displays read, write, execute permissions)
To remove a particular file from the repository
rm -rf 
rm -rf .git

To view help document
git  config --help  (or) git help config
git  config --help  (or) git help config
Push command is used to send changes to the master branch of your remote repository.
git push  
git push Testgit Testtask
To create a new branch and switch to it
git checkout -b 
git checkout -b task1
To switch from one branch to another
git checkout 
git branch task1
To list all the branches in your repo, and also tell you what branch you are currently in

git  branch

git branch
To delete the feature branch
git branch -d 
git branch -d task1
Discard commits in a private branch or throw away uncommitted changes

git reset
git reset
To merge one or more branches into your current branch and automatically creates a new commit if there are no conflicts
git merge 
git merge newbranch
Fetches the files from the remote repository and advances its branches
git pull origin
git pull origin
To show a listing of commits on a branch including the corresponding details
git log
git log
To compare the different versions of your file
git diff
git diff


