# Git commands

***

+  `git init`   *initializes a new repository*

+  `git add <filename>`  *adds file to staging area*

+  `git commit -m “message”`  *commits staged files with a message*

+  `git status`  *finds state of project files*

+  `git log` *shows the commit history*

+  `git log -p` *shows changes in each commit*

+  `git diff`  *compares the contents of your files against the contents of the staging area*

+  `git diff --staged`  *compares your staged changes against the previous commit*

***

+  `git rm <filename>`  *deletes the file*

+  `git mv <oldFileName> <newFileName>`  *renames or moves file from oldName to newName*

+  `git reset HEAD <fileName>`  *unstages a file*

+  `git revert <commitNo>` *reverts a particular commit*

+  `git revert HEAD` *reverts the most recent commit*

+  `git checkout --<filename>`  *discards changes in the file in working directory*

***

+  `git remote` *gets a list of remote repos*

+  `git clone <RemoteRepo> <localRepoName>` *Clones from remote repo to local dir*

+  `git pull` *pulls changes from remote repo*

+  `git remote add <you want to name remote repo> <path of remote repo>` *adds local repo as remote repo*

+  `git pull <remoteRepo> master` *pulls changes from remote branch to master branch*


source : [https://teamtreehouse.com/library/introduction-to-git]