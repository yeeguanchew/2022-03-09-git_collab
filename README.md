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


Changes to b1 commit 1
Changes to b1 commit 2
Changes to b2 commit 1
Changes to b2 commit 2

## conflicts

git checkout -b conflict_branch_1 echo "Changes to b1 commit 1" >> README.md git status git add README.md git commit -m "b1 c1" echo "Changes to b1 commit 2" >> README.md git add README.md git commit -m "b1 c2" git checkout main git checkout -b conflict_

--add something

- Branch protection rules force you to practice collaboration on your own
- git reset --hard<HASH> : force move current branch to <HASH> location
- git log --oneline --graph --all
