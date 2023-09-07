

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
git add <- file name ->
for all files (use 'git add .')
* git add index.html
* git add .



### commit
It is the record of changes.
git commit -m "some message"
* git commit -m "Some new files"



### push
Upload local repository content to remote repository
* git push origin main



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
* git push -u origin main         (setting 'origin main' to not repeat(optional))
* git checkout <-branch name->    (to navigate)
* git checkout -b <-new branch->  (to create new branch)
* git branch -d <-branch name->   (to delete branch)







