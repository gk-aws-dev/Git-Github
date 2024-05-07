## GIT RESET:

- reset is the command we use when we want to move the repository back to a previous commit, discarding any changes made after that commit. also useful for updating staging area and working directory accordingly.
(HEAD is the reference to the currently active branch or commit. HEAD~1 refers to the commit one step before the latest commit)

## Soft reset: move the HEAD to different commit, but keep changes staged.

- ```git reset --soft HEAD~1```: reset the HEAD to one commit before the current one while keeping the changes staged.

## Mixed reset: move to HEAD the commit just before the latest one and unstages the changes. Keep them in working directory.

```git reset HEAD~1```

## Hard reset: to discard changes and cannot be undo. 

```git reset HEAD~1 --hard```


## git revert: 
- reverting changes where commit history remain unchanged. It will help to revert the changes and when we are committing the same file again the previous commit history remain unchanged. Used for maintaining clean history and transparency.

```git revert <commit-id>```		
