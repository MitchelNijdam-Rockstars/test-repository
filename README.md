# Git examples and tests project

This is a repository to test stuff with branches, mergin, rebasing and other awesome git stuff. Below I will list all useful commands or instructions for reference.

## Branches

Create new branch:

    > git checkout -b [new_branchname]

Create new branch from another branch:

    > git checkout -b [new_branchname] [current_branchname]

Change working branch:

    > git checkout [new_branchname]

Push the branch to GitHub:

    > git push origin [new_branchname]

Delete a local branch:

    > git branch -d [branchname]

Delete a remote branch (on GitHub):

	> git push origin :[branchname]
	
Reset branch to remote (use carefully):

	> git fetch origin
	> git reset --hard origin/[branchname]
