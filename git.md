git #Git

##One Time Setup

 git config --global user.name "Tayler Stegman"
 git config --global user.email "Tae@myfreeapps.com"

# alias
<!-- .bash_profile create and code -->
alias gs="git status"
alias ga="git add"
alias gc="git commit -m"
alias go="git checkout"
alias gb="git branch"
alias gd="git diff"

alias ..="cd .."

alias glg="git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"


## Project Setup
git init
touch .gitignore 
Add *.class to the .gitignore
git add.
git commit-m "Initial Commit"


## 3 Step Repeating Commit Process
1. Make changes to code
2. Stage related changes
    * git add
3. Commit changes with a message
    * git commit -m"Message"
:)git 



## Commands

* ls -a                    --> shows hidden directories and files
* git status               --> shows what files have been staged or commitment
* add                      --> adds a file to the stage
* add .                    --> adds most recent file changed if more than one won't work
* rm --cached              --> removes a file from stage
* git commit -m"Present tense description of what changed" 
* git log                  --> enter to move down q to quit
* git checkout -- filename --> discard changes (go back in history)


## Problems
* commit without -m        --> Use Esc :wq to quit Vim
* wrong message            --> git commit --amend -m"New message"
* wrong commit             --> git checkout COMMIT_ID