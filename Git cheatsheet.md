# Git

## cheat sheet

### Commit commands

`git add -p`: choose what changes you want to add to the commit  
`git commit -m "commit description"`  
`git pull`  
`git push`

### Create branch commands

`git checkout -b "branchName"`  
one or more git commits  
`git push -u origin branchName`

### Get a remote branch

`git branch -a` (see all remote branches)  
`git checkout remoteBranchName`  
Several commands and their meaning

### Check the branch status

`git status`

### See the uncommitted code differences

`git diff`

### See only the files uncommitted

`git diff --name-only`

### Add new files and updates to the commit

`git add -A`

### Add updates to the commit

`git add -u`

### Commit changes with a message describing the commit

`git commit -m "message"`

### Pull all the commits from the remote branch

`git pull`

### Push the local commits to the remote

`git push`

### List local branches

`git branch`

### Delete a local branch

`git branch -d branchName`

### Create a new local branch

`git checkout -b "nameOfTheBranch"`

### Create and push the new branch to remote

`git push -u origin nameOfTheBranch`

### Revert one file

`git checkout path/to/file.js`

### Merge a branch to the one your in

`git merge nameOfTheBranch`

### Undo/rollback last commit

`git reset --soft HEAD~`

## 2FA

2FA (Two-factor authentication) is mandatory for all users

If you are having issues connecting to git, please see [link](https://help.github.com/articles/authorizing-a-personal-access-token-for-use-with-a-saml-single-sign-on-organization/)
