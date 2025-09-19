## basic git commands
## 1. git init - To initialize a repository or to start tracting all files in a folder
## 2. git status - Gives you the status of your repository

## 3. git add - will tell git what files to track e.g git add index.html
## 4. git rm - this will remove a file from being tracked and also delete the file
## 5. gt rn -cached [file_name] - this remove a file from being tracked the file would still be on the system

## 6. git commit -m 'first commit' - this create a commit i.e a snapshot of a particular version of your code

<!-- once you have stage your files, you can commit them into git. imagine a commit command as a snapshot at a certain point and time where you can return back to access your repository at the stage. you assign a commit massage to every commit, which you can pass with the -m prefix.-->

A - Added/Tracked: A file which has been previously staged or committed.
U - Untracked: A file which has not be stage or committed
M  - [Modified]
Ignored - A file which git has been explicitly told to ignore


<!-- Confied git --->
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL"