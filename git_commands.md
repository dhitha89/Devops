# Git Commands

## Start a new project
git init


## Stage files
git add file.txt


## Unstage files
git rm --cached file.txt
or
git restore --staged file.txt


## Remove all files from staging (before initial commit)
git rm --cached -r .


## Commit your changes
git commit -m "new file added"


## See commit history
git log


## Set email for this project only
git config user.email


## Set email for all projects
git config --global user.email
Note: Local config overrides global


## Create a new branch and switch to it
git checkout -b newbranch


## Switch to an existing branch
git checkout newbranch
