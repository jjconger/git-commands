# Useful Git Commands #

## Cleaning Working Directory ##

Sometimes you want to remove the changes you made to your working directory. 

	git clean -df
	git checkout -- .

`git clean -df` removes all untracked files and `git checkout -- .` clears all unstaged changes


## Unstaging Changes ##

### Unstage New File ###

Unstage a file that was newly added to the index. This will return the file to untracked status.

	git rm --cached <file>

### Unstage Modified File ###

Unstages any modifications made to the file since the last commit, but keeps the modifications in working directory.

	git reset HEAD <file>




