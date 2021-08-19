# github-testing
This is a temporary repo for experimenting with github workflow

Commiting changes made on your computer
STEPS
1. git clone ${copied url from github repo}
2. move all files to the automatically generated folder
(don't forget to cd to that directory before continuing^^)
3. git status command: self-explanatory ^^
4. add files you want to commit
   git add index.html
   git add styles.css
   git add index.js
   or simply: git add . (for adding all)
(you can check your status after this to be sure)
5. git commit -m "adding project files"
   this will initialise a git commit (like how you'd do with GUI)
   add -m for commit message
6. git push: for confirming your commit

EXTRA STUFF TO KNOW
- with git clone command you can copy everything in the github repo to your computer (so it work the other way around too)
- git commands will not work unless you're in a directory that has a .git in it (obviously)

git pull: to copy changes to your computer that were uploaded to the repo (updates files on your computer)

BRANCHES/MERGING

- changes shouldn't be made directly to the main branch, instead create a new side branch
- creating a new side branch:
1. git branch: for listing all existing branches
2. git branch ${side branch name} for creating a new branch
3. git checkout 4{side branch name} to switch to the new branch
4. use git push --set-upstream origin ${side branch name} if asked
5. git add <file name>
6. git commit, git push
7. pull request will appear on github that needs to be approved and merged (under Pull requests tab)
8. side branch can be kept or deleted merging

*** extra notes:
- use got branch -d <branch name> to delete the local branch on your PC