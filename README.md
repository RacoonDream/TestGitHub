# TestGitHub
Trying GitHub
Lessons Learned:

ctrl+shift+p - command window of vscode

git clone
give ur github url
give ur local repository folder.

This will  copy your github repository
artifacts into your local repository.

Then work on this, commit local and then publish to github (origin/master)



local commit done. (by clicking tick mark in source control section)


Publish Change (bottom left) (up and down arrow)


It may ask your git hub username and password




Learn to branch:

1. 
Create the branch in local via console-
or do it by ide

git checkout -b [name of your new branch]

2.
To change local branch

git checkout [your new branch]
 eg:git checkout StagingLocal.

3. To push your new Local branch to remote - i,e create a branch on remote from
git terminal window

git push -u origin <New Remote Branch Name> 
keep the remote branch name same as ur local name to reduce headache

general syntax is 

git push -u <remotename i.e origin> <branch>
once done, next time just git push



Push a local repository to a new github repository:

1. open your existing project in vscode

2. open terminal

3. git init
This will initilize the local directory as a Git repository

4. git add .
Add the files in the local repo and stages them for commit

5. git commit -m "Remark like 1st commit"

# Commits the tracked changes and prepares
 them to be pushed to a remote repository. 
To remove this commit and modify the file,
 use 'git reset --soft HEAD~1' and commit and add the file again.

6. get ur remote repository url

7. git remote add origin <remote repo url>
 
 if remote origin already added then
 $git remote -v (to know the already assigned url)
 
 $ git remote set-url origin <ur git repositry repo url>
 
8.git push origin master
# Pushes the changes in your local repository up to 
the remote repository you specified as the origin
