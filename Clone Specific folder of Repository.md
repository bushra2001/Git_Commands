##Cloning Specific Folder from Repository

###Create and initialize your new repository:

```mkdir <repo>

 cd <repo>
 
 git remote add origin -f <repo from which specific folder to be cloned>
 
 git config core.sparseCheckout true
 
 echo "<**Specific folder to be cloned**>" >> .git/info/sparse-checkout

 git pull origin master
