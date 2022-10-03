# Demo
## Git Commands:

Initialize a local git repo:
> git init

Connect to remote reop:
> git remote add origin "ssh link"/"link" (most preferably using ssh)

Pull files from remote repo:
> git pull origin master

	if error: fatal: HTTP request failed
	git remote set-url origin "link"

List of files (untracked and modified):
> git status

Add a file to index:
> git add "file_name"

Commit files:
> git commit -m "commiting message"

Add all new/ modified files to index:
> git add -A

Commit all new/ modified files:
> git commit -a -m "message"

Log data:
> git log

Create a new branch:
> git branch branch_name

Switch to branch:
> git checkout branch_name

Merging branch to master branch:
> git merge branch_name

Rebasing a brach:
> git rebase master OR branch_name

Pushing files: first need to made an SSH key:
-generate SSH key
> ssh-keygen

See the SSH key:
> cat "SSH key path" (near to "saved in")

Authenticating SSH with GitHub:
> ssh -T git@github.com

Push to specific branch:
> git push origin master/ branch_name





