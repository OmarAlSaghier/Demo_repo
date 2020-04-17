# Demo_repo
This is a Demo repository

Git Commands:

initialize a local git repo
> git init

connect to remotr reop
> git remote add origin "link"

pull files from remote repo
> git pull origin master

	if error: fatal: HTTP request failed
	git remote set-url origin "link"

list of files (untracked and modified)
> git status

add a file to index
> git add "file_name"

commit files
> git commit -m "commiting message"

add all new/ modified files to index
> git add -A

commit all new/ modified files
> git commit -a -m "message"

log data
> git log

create a new branch
> git branch branch_name

switch to branch
> git checkout branch_name

merging branch to master branch
> git merge branch_name

rebasing a brach
> git rebase master OR branch_name

Pushing files: first need to made an SSH key
-generate SSH key
> ssh-keygen

see the SSH key
> cat "SSH key path" (near to "saved in")

authenticating SSH with GitHub
> ssh -T git@github.com

push to specific branch
> git push origin master/ branch_name





