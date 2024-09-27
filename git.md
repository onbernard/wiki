# Staging
```shell
# Add all changes (new, modified, deleted) in the current directory
git add .
# Add all changes (new, modified, deleted) in the entire repository
git add -A
# Add all tracked files
git add -u
# Add changes interactively
git add -i
# Add portions of a file
git add -p <file>
# Add only new files
git add --all
```
# Unstaging
```shell
# Unstage a file
git reset HEAD <file>
# Unstage everithing
git reset HEAD
# Untrack a file that was added to .gitignore
git rm --cached <file>
# Untrack recursively all files and directories
git rm -r --cached .
```
# Commit
```shell
# Amend last commit
git commit --amend
```
# Push
```shell
# Push and set upstream
git push -u <remote> <branch>
# Force push (overwrite remote history)
git push -f <remote> <branch>
```
# Undo changes
```shell
git checkout HEAD -- <file>
```
# Log
```shell
# Show the last n commits
git log -n 5
```
# Branches
```shell
# Show all branches, including remote
git branch -av
```
# Remote
```shell
# Show all remotes
git remote -v
# Add a remote
git remote add <name> <url>
# Change a remote's url
git remote set-url <name> <new_url>
# Remove remote
git remote remove <name>
```
