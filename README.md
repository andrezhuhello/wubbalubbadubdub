# This is a cheat list for anything i learned about git  

check git version:  
$ git --version  

------

clone github repository to local directory  
  1) git clone git@github.com:userhandle/repositoryname

------

how to initialize git repository locally:  
  1)  git init -b main  
  2)  $ git add .  
      \# Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'
  4)  git commit -m "First commit"  
      \# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.

------

link local repository to github repository:
  1) git remote add origin <REMOTE_URL>  
    \# Sets the new remote  
  2) git remote -v  
    \# Verifies the new remote URL
  3) git push origin main
    \# Pushes the changes in your local repository up to the remote repository you specified as the origin   

------




