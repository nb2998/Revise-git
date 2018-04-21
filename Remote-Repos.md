# All about remote repositories
### Create a clone
`git clone <url>`

### Setting a remote
`git remote add origin <url>`</br>

### Keeping forked repo in sync
#### 1. Setting upstream 	
`git remote add upstream <url of forked repo>`

#### 2. Fetching latest changes from upstream	
`git fetch upstream`

#### 3. Rebasing 
With the rebase command, you can take all the changes that were committed on one branch and replay them on another one<br/>
* `git checkout b` <br/>
* `git rebase upstream/master` -Applies changes of master branch of remote upstream on the branch b.

#### 4. Push to cloned repo
`git push origin master`

#### 5. Reset to upstream (CAUTION!)
You might want to keep a copy of local work first: <br/><br/>
`git commit -a -m "Saving my work, just in case"`<br/>
`git branch my-saved-work`</br><br/>
And then:
`git reset --hard upstream/master`

### Reviewing pull requests
`git fetch upstream pull/PR_Number/head:branchName` </br>
`git checkout branchName`
