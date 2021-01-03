# Creating a new file or uploading an existing file.

## Create a new repository on the command line
```
echo "# example" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/bushra2001/example.git

git push -u origin main
```                
## push an existing repository from the command line
```
git remote add origin https://github.com/bushra2001/example.git

git branch -M main

git push -u origin main
```
