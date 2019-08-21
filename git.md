git #Git

##One Time Setup

 git config --global user.name "Tayler Stegman"
 git config --global user.email "Tae@myfreeapps.com"


## Project Setup

git init


## 3 Step Repeating Commit Process
1. Make changes to code
2. Stage related changes
    * git add
3. Commit changes with a message
    * git commit-m "Message"




## Commands

* ls -a                    --> shows hidden directories and files
* git status               --> shows what files have been staged or commitment
* add                      --> adds a file to the stage
* add .                    --> adds most recent file changed if more than one won't work
* rm --cached              --> removes a file from stage
* git commit -m"Present tense description of what changed" 
* git log                  --> enter to move down q to quit
* git checkout -- filename --> discard changes 


## Problems
* commit without -m        --> Use Esc :wq to quit Vim
* wrong message            --> git commit --amend -m"New message"

