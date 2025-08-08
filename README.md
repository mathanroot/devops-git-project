# DevOps Git Project

Select the project folder
then 
```bash

git init 
```
Create README.md
```bash
echo "# DevOps Git Project" > README.md
```
add README.md file to github repo
```bash
git add README.md
git commit -m "Initial commit with README"
```
Add into GITHUB REPO 
```bash
git remote add origin https://github.com/username/devops-git-project.git

# Pull remote changes into your local main
git pull origin main --rebase
git push -u origin main
```
Create dev branch and feature branch 
```bash
git checkout -b dev
git push -u origin dev
```
Create feature branch from dev
```bash

git checkout -b feature
git push -u origin feature
```
#used for pull requests

Create a file and push into dev or feature branches in github repo

```bash
touch feature.txt
```
Stage the file
```bash
git add features.txt
```
Commit the change
```bash

git commit -m "Add features.txt"
```

Push to GitHub
```bash
git push -u origin feature
```
#then pull requests sends to github repo and confirm for the requests....

# ADD gitignore
```bash
git add .gitignore
git commit -m "Add .gitignore"
git push
```



