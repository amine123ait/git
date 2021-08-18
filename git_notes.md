# Learn Git 

## intro :
	+ Git command line tool ; keep track of changes to code ; sync code between ppl ; test changes in "branches" without losing the original ; revert back to the previous version of ur code 
## Cmd : 

**git clone** : "git clone url" < download code from the repo

**git add** : "git add file" < keep track of the changes of the file ;add file to the repo ;add a file in order to return back to;save the stat of the curent asset (code); take a snapshot 

**git commit**: "git commit -m msg" < save the repo and make a note about the new changes ; add notes ; keep track of the changes by including a msg ; save a new snapshot 

**git status** "git status" < status 

**git push** "git push " < push the code to github repo

**git config --global user.name** "git config --global user.name YOUR_NAME" < your name will be displayed in commits 

**git config --global user.email** "git config --global user.email YOUR@GMAIL.COM" < your email will be displayed in commits changes 

**git log** "git log" < commit log 

**git checkout** " change branches ;git checkout commit_hash" < come back to a certent change in commits 

**git branch** "git branch / git branch NAME_OF_THE_BRANCH" < its a good idea to create a dev branch where u can improve your code and adding new stuff and features , Then testing and check if there is not bugs ; after u can merge them to the master branch and push it the the main repo 

**git merge** "git merge BRANCH_NAME" < merge a branch with the main barnch (master branch)

**git restore** "git restore file" < if u dont like the changes u can restore the files as the previous commit 

**git remote add** "git remote add NAME REPO URL" < add remote repo and give it a name  

**git push** "git push -u NAME master" < push source code into remote repo in github 


## keep track of example 

remote -v 
````
git remote set-url origin git@github.com:amine123ait/learn_git.git
````
```
echo "FILE OR DIRE THAT WELL BE IGNORED AND NOT CHECK IN TO GITHUB REPO" > .gitignore
```
