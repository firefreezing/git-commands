# Git common command

### Common terminologies

- fast-forward
- remote

git add .



### list all the branches (local & remote)

`git branch -a`

- list commit history

### checkout a new branch

`git checkout -b <new branch name>`

By default git checkout -b will base the new-branch off the current HEAD. 

### show local branch and remote branch tracking relations

`git branch -vv`: result shows the 


`git remote show origin`: lists which remote branch(es) the default `git push` and `git push` to push/pull code to/from

### push a local branch to remote, and set it as upstream

`git push --set-upstream origin <remote branch>`

- resolve conflict
- gitflow
- delete a remote branch
- pull request flow
- tagging
- revert a past commit