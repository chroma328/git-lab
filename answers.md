1. git version 2.43.0
2. user.name=chroma328
user.email=ip740625@ohio.edu
3. When you type git --help, a list of common Git commands appears, sorted by what tasks they perform and listed with a short explanation of what they do. Text also appears giving other help commands and what they list. 
4. The command "git status" lists the files in which changes to them are being tracked, files whose changes are not being tracked, and files are ready to be committed to the repository, which will save the version of the file put into the staging area to the online repository.
5. When I added README.md to the staging area, the command "git status" updated to remove the file "README.md" from the list of untracked files and added it to the list of tracked files which will be committed. Whether a file is being tracked is indicated by its color, and README.md changed from red, indicating it is not being tracked, to green, indicating that it is now being tracked.
6. When I added answers.md to the staging area, the file "answers.md" also appeared in the list of files whose changes will be committed, with its text colored green. However, a new list of changes not set to be committed was created, and a modified version of answers.md appeared there. I believe that this is because I made changes to the document after adding it to the staging area and before using "git status," and between those times, "answers.md" autosaved.
7. On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")
8. commit 832eebcb6631433baad9f66c3e74f7009462eb1c (HEAD -> master)
Author: chroma328 <ip740625@ohio.edu>
Date:   Tue Sep 1 17:03:00 2026 -0400

    Initial commit
9. The status of my repository changed to state that "the branch is up to date with origin/main," with "main" being the one branch in the repository on Github. This changed because there is now a repository on Github for the files to be pushed to.
10. The changes I made to "README.md" online were not reflected in my local copy of the file. This did not occur because the local file on my personal computer itself is not connected to the Internet. The version of the file on Github had not been shared to the local repository, similar to how information on the local repository is not shared to the file on Github until the file is tracked and committed.
11. The "git push" command does not work because the version of "README.md" has been changed in the Github repository and not the local repository.
12. After using "git pull," the local "README.md" file did update with the changes made on Github.
13. The files in the "git-lab-2" directory are ".," "..," ".git," ".gitignore," and "README.md."