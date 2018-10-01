### Initalising an empty git repository 
`git init`

### Checking status of git repository
`git status`

### Adding files
To add all untracked files: `git add .`<br>
To add a specific file: `git add fileName.txt`

### Removing files
 `git rm file.txt`
 <br/> To remove directories, `git rm -r dirName`
 <br/><br/><i> To record all removals, additions, and modifications in the working tree use: `git add -A`</i>
 
### Commit files
* Giving a commit message: `git commit -m "Meaningful commit message"`<br> 
* Adding more files to the last commit (no change in commit message): <br> 
`git add file.txt`<br>
`git commit --amend --no-edit`<br> 

  In case commit message has to be changed too, `git commit --amend` suffices the purpose.<br>
 
  Note : To push it now, you need to use the force command (Careful!)<br>
  `git push origin master --force`<br>

### Configure the author name and email address to be used with your commits
`git config --global user.name "xyz"` <br>
`git config --global user.email xyz@example.com`

### View all the file diff
`git diff` 

### Checking the commits history
`git log` <br>
- Summary parameter will show information such as creations, renames and mode changes: `git log --summary`
