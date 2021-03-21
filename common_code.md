# Git common command

### Common terminologies

- fast-forward
- remote
- HEAD: a branch ref pointer



## Useful scenarios

### list all the branches (local & remote)

`git branch -a`

### list commit history

`git log --graph --oneline --decorate`

### checkout a new branch

`git checkout -b <new branch name>`

By default git checkout -b will base the new-branch off the current HEAD. 

### show local branch and remote branch tracking relations

`git branch -vv`: result shows the local & remote tracking relations

`git remote show origin`: lists which remote branch(es) the default `git push` and `git push` to push/pull code to/from

### push a local branch to remote, and set it as upstream

`git push --set-upstream origin local-branch-name:remote-branch-name`

-   if not include `--set-upstream`, then no auto-tracking relation
-   if `local-branch-name:remote-branch-name` becomes `branch-name`, then local branch and remote branch share the same name

### Merge a branch

`git merge branch-name-to-merge-from`

### Delete a remote branch

- delete a local branch: `git branch -d local-branch-name`, if force delete, then use `-D`

- delete a remote branch: `git push origin -d remote-branch-name`


To dos:

- resolve conflict
- gitflow
- pull request flow
- tagging
- revert a past commit
- compare two branches
- copy items from one branch to another