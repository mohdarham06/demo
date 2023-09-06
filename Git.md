

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
git clone <- some link ->
* git clone https://github.com/mohdarham06/demo.git



### Status Command
Display the status of code.
File status lifecycle--> untracked->unmodified->modified->staged
* git status



### add
Adds new changes in fles in four working directory to the Git staging area.
git add <- file name ->
for all files( 'use git add .' )
* git add index.html
* git add .



### commit
It is the record of changes.
git commit -m "some message"
* git commit -m "Some new files"



### Push
Upload local repo content to remote repo
* git push origin main



