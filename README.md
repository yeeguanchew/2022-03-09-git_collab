# 2022-03-09-git_collab

- 'git clone':

## Branches

- 'git branch <NAME>': creates <NAME> where HEAD is
	-'git branch -a': list all your branches
- 'git switch <NAME>' : switch to branch <NAME>
	- 'git checkout <NAME>' : same as git switch
	- shortcut: git switch -c <NAME>: create and move in 1 step
	
- The PR (pull request) will update if you push new changes

- Cleaning up after PR merge:
	- 'git fetch --prune' : cleaning up anything locally that is no longer in remote
	- 'git branch -d <NAME>' : delete a branch <NAME>
		- Note: lower-case d (use -D for force delete)

