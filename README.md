# crispy-doodle
Github Test

Version Control System
> Track changes
> Easily swap versions
> Undo changes
> Ideal for team

GitHub
> Remote Repository
> Only stores code

Install Git
Configure with GitHub

Initialise (Adds .git folder)
> git init

Clone
> git clone ssh_url
Adds .git folder
Adds Remote

Git Structure
> Working Directory
  = git add  (Indexing/Staging)
  = git commit (HEAD)
  = git push (GitHub - clone)
  = git remote add origin ssh_url (GitHub - init)
  = git pull (copies from remote)

>Branches
  = git branch feature_a
  = git checkout feature_a
  = git checkout -b feature_a
  = git merge feature_a


1. create new file test.html
2. git add test.html
3. git commit -m "added test file"
4. Edit test file
5. git diff
6. git add .
7. git commit -m "second commit"
8. git push
9. git checkout -b <branch_name>
10. add file
11. commit
12. No store branch
> git push --set-upstream origin store
13. to merge
> git checkout master
> git status   -- to see in which branch
> git merge store
> git push

If merge conflict
change store in main
Go to store
change & commit
push
change to master
merge
see message
change
add
commit



