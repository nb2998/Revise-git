# Undoing Wrong Commits

### Remember to Use Git Log Before Pushing
`git log`

### You Can Fix a Commit Message With
`git commit --amend -m "New Commit Message"`
</br></br>
You can also add some files before, in case you forgot: `git add <MissingFile>`.

### Undoing a Commit
`git reset --soft HEAD^`
</br></br>
This command will return a commit in your repository, but modified files will still be in your directory.

You can use `git reset --hard HEAD^` if you want to **Throw Away** both the commit and files/modifications.
