# git-tutorial

*Study on Basic Terminologies used in git and certain Git Commands

*Study on Push, pull,branching and merging in Git


# GIT

Free and open source 'control system'


# GIT COMMANDS

**Clone**-bring the repo that is hosted on github into a folder on your local machine 

**add**-Track your files and changes in git 

**commit**-save your files in Git 

**push**-upload git commits to a remote repo 

**pull**-download changes from remote repo to your local machine


# PUSH_COMMANDS

## Steps to push the changes into repository from local machine

### Cloning the Repository
```
git clone link
```

### Get Status
```git status```

###Tracking the Changes
**git add fileneame**

###Track all changes
**git add .**

###Committing the Changes
**git commit -m("filename") -m("description")**

###pushing the changes from local machine to the repository
**git push -u origin main**


##Steps to push a new folder created in local machine to remote

###Intialize empty git repository
**git init**

###To connect the new repo to the Github
**git remote add origin/link**

###Push it into the Repo
**git push -u origin main**


##Pull Request
**git pull**

#GIT_BRANCHING
*Master branch-default branch
*Feature branch-additional branch
*Hotfix branch-bug fixing branch

##Steps For Creating a branch

###Identify the current branches
**git branch**

###Create new branch
**git checkout -b feature-dd**

###switch between branches
**git checkout main**

###Adding the branch to repository
**git add .**
**git commit -m"" -m""**
**git push origin main**

###Combing the step of adding and committing
**git commit -am""**

Note:Changes in the master branch it doesnot affect the feature branch similarly for master branch.BRANCHING

#GIT_MERGING

##Steps to merge the branches

###Find the difference between the branches
**git diff**

###Merge the master branch with the feature branch
**git merge master**

###Merge the feature branch with the master branch
**git merge feature-dd**

###Push the changes into the repo
**git push -u origin branchname**


##Steps to delete the feature branch once merged
**git branch -d branchname**


##Steps to undo in Git

###Before commit
**git reset**

###For 1 commit further
**git reset HEAD~1**
Note:Head is a pointer to the last commit

###To find all the commits in back chronological order
**git log**

Note:
**Forking**-complete copy of the repository
