used to manage large projects spanning many files.

[Useful video tutorial](https://www.youtube.com/watch?v=USjZcfj8yxE)
[Video notes for above video in blog form](https://videotutorials.notion.site/Introduction-to-Git-ac396a0697704709a12b6a0e545db049)

## Basics: 
Initial config: 
	set username ->  git config --global user.name "Your Name"
	and email -> git config --global user.email "your@email.com"
	git init -> initialize the current folder as a git repository

## Using Git: 
git status -> check the status of the current repository in relation to the current branch

git add name_of_file -> add this file to the staging area 
git add . -> add all files in the directory to the staging area

git commit -m "Commit message" -> commits the changes that are currently in the staging area to the current branch

## Branches
git log -> list all branches of the project
	The logs will show details for each commit, like the author name, the generated hash for the commit, date and time of the commit, and the commit message that we provided.

git checkout "commit-hash" -> go to a different branch

## Changing Branches
git checkout "branch-name" -> change to an existing branch

git checkout -b "new-branch-name" -> create a new branch of the project
	usually it's a good idea to create a new branch for development, experimental features, and release/release candidates.

## Merging branches
git merge "branch name" -> merges the branch "branch name" INTO the branch we are working in.

## Deleting a branch
git branch -d "branch-name" -> deletes the branch "branch-name"