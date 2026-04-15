* git init #initialize a new git repository

@set configuration like username and email
* git config --global user.name "your_name"
* git config --global user.email "'your_email"

@basic workflow 
 1] #create a file >>  touch index.html  >>  untraked state
 2] #add file to staging area >> git add index.html  >> staged state
 3] #save staged state with a massege(commit) >>  git commit -m "added homepage"
 
 4]%upload local change to remote repository >>  git push origin main
 5]%fetch and merge change from remote repo >> git pull origin main

@view changes 
* git status

@display commit history(use frequntly to track changes)
* git log

@2)Adding more commands
* git log --oneline  #display git log (comit history) in oneline

* git branch 
* git branch feature-login    #list or create branches

@ 3)adding  more commands 
*  git diff  #to see exact changes (like git status)

*  * @first time local se remote tak chije bhejne ke liye (git push origin main )karte he uske liye kuch steps he
*  1)first check your origin (git remote -v)
*  2)then add new origin ,copy http/ssh from git repository jaha push karni he ( git add origin <git_ka _http/ssh copy from git and paste here>
*  agar https se karoge to token (github) se leke https me add kar dena ,nhi kiya to username aur password mangega,paSSWORD LI JAGAH BHI  token dal sakte ho
*  



