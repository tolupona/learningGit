# learning git
## what is git
git is a version control system
## importance
enable snapshots on code/ projects
Collaborative developement
backup codes
have several versions of a project, i.e. version 1, version 2, e.t.c.
Sync projects on different machines

## git providers
they are all built on git and use the same commands
github, bitbucket, gitlab, ...
we shall use github

## basic git terms
### repository (repo)
is basically a parent folder in git
contains related files and folders of a certain project
e.g. learning git is a repo, pythonLesson1 is a repo too
- should contain the .git folder
- .git folder is created by an initialize command
command: [ git init . ]
#### two type: 
local - repo on your pc
remote - the one on github
### branch
is a version of the project
### commit
### stage
### head

## states
#### working state
 -  this are the changes you have currently made on a project, they appear in red on running [ git status ]
#### staged state
 - hightlighting / selecting the changes you have made so that you can stage them appear as green in on running [ git status ]
run  [ git add * ] to add all changes on stage
#### committed state
 - once you have finalize on the changes, and now you want to make them final / snapshot them, put them in committed state [ git commit - m "some comments" ]
#### stashed state
 - if you have made changes in as staged state, but you dont want to commit them, and need to work on something else

## basic git commands / actions

### git init
initiaze a repo

### git branch
view all branches

### git branch new-branch-name 
creates a branch

### git checkout branch-name
chagne from working branch to another

### git checkout -b branch-name
is a combination of git branch and  git checkout

### git add
shift changes from working state to staged state

### git status
view states

### git stash
works on staged state only
recycle-bin's codes
### git stash pop
restore codes from git stash

### git commit -m ""
shift changes from staged state to commited state
takes in some comments
### git push origin branch-name
add the changes on local repo to remote repo
### git pull origin branch-name
get the changes made on remote repo
### git merge branch-name
sync changes made in one branch to another
### rebase

### git branch -D branch-name (deletes a branch)

### revert (undoes a commit)
