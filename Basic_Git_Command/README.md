# Instruction to control git!!

## Step to push repo from local to remote

```git
git add FileName # add file to commit
git reset FileName # unadd file
git commit -m "Commit Name" 
git commit --amend # if you have 3 files and just add 1 file and want to add another 2 files but don't want to change the commit name, use this
git push # push the repo from local to remote
git push -f # force to push repo if you use the git commit--amend
git status # check files have been add or not
git log --oneline #check commit version of Local and Remote

--------------------------

git fetch # check the change of the repo on remote
git log --oneline origin/main # update the repo on remote
git pull # get the repo from remote to local

```

Just use to pull
