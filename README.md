Git: it is a version control system (VCS) that allows you to track changes,history, and version of dependencies (1.0.2) .
Github: it is cloud-based platform that host git repositories and provide collaboration features like pull, push request and issue tracking.

Git Commands:

1.	Git Configration
  •	Git config –global user.name "YourName"
  •	Git config --global user.email "you@example.com"
  •	git init : Initialize a new Git repository in the current folder.
  •	git clone <url> : Copy an existing repository from GitHub/GitLab/etc.
  •	git status : Show changes (staged, unstaged, untracked files).
3.	Staging & Committing
  •	git add <file> : Add specific file to staging area.
  •	git add : Add all changes in current directory.
  •	git commit -m "message" :Save staged changes with a message.
  •	git commit -am "message" : Add + commit modified (tracked) files in one step.
4.	Branching
  •	git branch : List all branches.
  •	git branch <name> : Create a new branch.
  •	git checkout <name> : Switch to a branch.
  •	git checkout -b <name> : Create + switch to a new branch.
  •	git merge <branch> : Merge another branch into current one.
  •	git branch -d <name> : Delete a branch.
5.	Remote Repositories
  •	git remote -v: Show remote repositories.
  •	git remote add origin <url>: Link local repo to remote (usually GitHub).
  •	git push origin <branch>: Upload branch changes to remote.
  •	git pull origin <branch>: Download and merge changes from remote.
  •	git fetch : Download changes (without merging).
6.	Undo & Reset
  •	git log : Show commit history.
  •	git diff : Show changes not staged.
  •	git diff --staged : Show staged changes.
  •	git reset <file> : Unstage a file.
  •	git reset --hard <commit> : Reset everything to a specific commit.
  •	git revert <SHA>: revert back
  •	git checkout -- <file> : Discard local changes in a file.
7.	Useful Shortcuts
  •	git stash : Save uncommitted changes temporarily.
  •	git stash pop : Re-apply stashed changes.
  •	git tag <tagname> : Mark a commit (e.g., v1.0 release).
  •	git rebase <branch> : Re-apply commits on top of another branch.
