

# Git

Git is a free and open source Version control system.
version control system - ttol that helps to track changes in code.

Helps to work together in building projects, 
helps to colaborate in organised way by tracking history.




## Configuring Git

* git config --global user.name "Mohd Arham"
* git config --global user.email "mohdarham0634@gmail.com"
* git config --list



## Basic Git Commands

### Clone Command
Cloning a repo in your local machine.
git clone <- link ->
* git clone https://github.com/mohdarham06/demo.git



### Status Command
Display the status of code.
File status lifecycle--> untracked->unmodified->modified->staged
* git status



### add
Adds new changes in fles in four working directory to the Git staging area.
* git add <- file name ->
* use 'git add .' (for all files)
* git add index.html
* git add .



### commit
It is the record of changes.
* git commit -m <-"some message"->
* git commit -m "learned about branches"



### push
Upload local repository content to remote repository
* git push origin main
* git push -u origin main         (to simply use 'git push' in future)



### init
It is used to create new repository
* git init
* git remote add origin <- link ->
* git remote add origin https://github.com/mohdarham06/project2.git
* git remote -v      (To verify remote)



### Git Branches Commands
* git branch                      (To check remote branches)
* git branch -M main <-new name-> (To rename branch)
* git push origin main
* git push -u origin main         (to simply use 'git push' in future)
* git checkout <-branch name->    (to navigate)
* git checkout -b <-new branch->  (to create new branch)
* git branch -d <-branch name->   (to delete branch)



### Merging Code
* git diff <-branch name> (to compare commits, branches, files & more)
* git merge <-branch name> (to merge 2 branches)
OR
Create a Pull Request (to merge branches)

Git Ull is used to fetch and download content from a remote repository and immediately update the loack repo to match that content.
* git pull origin main
* git pull -u origin main (to simply use 'git pull' in future)



### Fixing Mistakes
Case 1: staged changes
* git reset <-file name->
* git reset (for all files)

Case 2: commited changes (for one commit)
* git reset HEAD~1 "some message"

Case 3: commited changes (for many commits)
* git log (to check commit history and commit hash)
* git reset <- commit hash ->
* git reset --hard <- commit hash -> (it remove changes after that commit)










