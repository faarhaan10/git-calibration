# Here's some instructions

## to Delete the last commit:
- `git reset --hard HEAD~1`
----------------------------------------------------------------
### ⬆️⬆️ This will remove the last commit locally. To update the remote repository, force push the changes:
- `git push origin main --force`
----------------------------------------------------------------

## revert back to the first commit:
`git checkout HEAD^`
----------------------------------------------------------------

### ⬆️⬆️ This will move you back to the first commit. Now, if you want to make this change permanent on the remote repository, push the changes:
`git push origin main --force`
----------------------------------------------------------------

## If you want to create a new branch to retain commits you create, you may do so (now or later) by using -c with the switch command. Example:
`git switch -c <new-branch-name>`

## Or undo this operation with:
`git switch -` || `git switch - --detach`