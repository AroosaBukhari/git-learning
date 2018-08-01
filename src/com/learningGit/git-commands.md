# Git commands

*TODO change to markdown*

git init   (initialize a new repository
git add <filename>  (adds file to staging area
git commit -m “message”  (commit staged files with a message
git status  (to find state of project files
git log (shows the commit history
git log -p (changes in each commit
git diff  (compares the contents of your files against the contents of the staging area
git diff --staged  (compare your staged changes against the previous commit
git rm <filename>  (deletes the file
git mv <oldFileName> <newFileName>  (renames or moves file from oldName to newName
git reset HEAD <fileName>  (to unstage
git revert <commitNo> (revert a particular commit
git revert HEAD (revert the most recent commit
git checkout -- <filename>  (to discard changes in the file in working directory
git remote (get a list of remote repos
git clone <RemoteRepo> <localRepoName> (Clone from remote repo to local dir
git pull (pull changes from remote repo
git remote add <you want to name remote repo> <path of remote repo> (to add local repo as remote repo
git pull <remoteRepo> master (pull chnges from remote branch to master branch