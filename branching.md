# creating a new branch
HP@LAPTOP-GHNT2I05 MINGW64 ~/Desktop/learning-git (main)
$ git branch
* main

HP@LAPTOP-GHNT2I05 MINGW64 ~/Desktop/learning-git (main)
$ git checkout 
Your branch is up to date with 'origin/main'.

HP@LAPTOP-GHNT2I05 MINGW64 ~/Desktop/learning-git (main)
$ git checkout -b new-branch
Switched to a new branch 'new-branch'

# switching between branches

$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-GHNT2I05 MINGW64 ~/Desktop/learning-git (main)
$ git checkout new-branch
Switched to branch 'new-branch'




# git pull
you do git pull when you want to pull all the updates that where made to the code on github


for mdoified files only :
git commit -am "messages"

-a - add
-m - message


git reset or git reset filename is used to undo your last git add 
or last git commit  -- git reset HEAD~1 / HEAD
