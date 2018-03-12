# Branches in git
### Create a new branch
`git branch <branchName>`

### Checkout to a branch
`git checkout <branchName>`
</br></br>
Or, simply use: `git checkout -b <branchName>` to create a branch and checkout immediately.

### Delete a branch:	
  * If the branch is fully merged in its upstream branch, or in HEAD if no upstream was set, then : `git branch -d <branchname>` 
  * Shortcut for -delete --force : `git branch -D <branchname>` 
  * Delete a branch on your remote repository: `git push origin :<branchname>`

### Push a branch to your remote repository:	
`git push origin <branchname>`

### Push all branches to your remote repository:	
`git push --all origin`

### Rename your local branch.
* If you are on the branch you want to rename: `git branch -m new-name`
* If you are on a different branch: `git branch -m old-name new-name`
* Delete the old-name remote branch and push the new-name local branch: `git push origin :old-name new-name`
