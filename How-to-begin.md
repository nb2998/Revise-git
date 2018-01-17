### Initalising an empty git repository 
`git init`

### Checking status of git repository
`git status`

### Adding files
To add all untracked files: `git add .`<br>
To add a specific file: `git add fileName.txt`

### Commit files
* Giving a commit message: `git commit -m "Meaningful commit message"`<br> 
* Adding more files to the last commit (no change in commit message): <br> 
`git add file.txt`<br>
`git commit --amend --no-edit`<br> 
* In case commit message has to be changed too, `git commit --amend` suffices the purpose. 
