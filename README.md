# Git-Project History

ls -ltr
mkdir Final-Project
cd Final-Project/
mkdir Git
cd Git/
git init Production/
cd Production/
vim index.html
git add .
git commit -m "Initial Version"
git branch
git checkout -b Testing
git checkout -
git checkout Dev
git branch
git checkout -b Feature-1
git checkout Dev
git checkout -b Feature-2
git branch
vi index.html
git add .
git commit -m "Added first <H1> tag"
vi index.html
git add .
git commit -m "Several <P> tags added"
vi index.html
git status
git add .
git commit -m "Content Updated"
git status
git checkout Dev
git diff Dev..Feature-2
git checkout Feature-1
vi index.html
git add .
git commit -m "Body STYLES added"
git checkout Dev
git merge Feature-2
git diff Dev..Feature-2
git diff Dev..Feature-1
git rebase Feature-1
git diff Dev..Feature-1
git status
vi index.html
git tag -a REL01.00.00 -m "This is Release version 1.0.0"
git checkout Testing
git diff Testing..Dev
git merge Dev
git diff Testing..Dev
git checkout master
git diff master..Testing
git merge Testing
git checkout Feature-1
vi index.html
git status
git add .
git commit -m "<H1> STYLES added"
git checkout Dev
git diff Dev..Feature-1
git merge Feature-1
vi index.html
git tag -a REL02.00.00 -m "This is Release version 2.0.0"
git checkout Testing
git diff Testing..Dev
git merge Dev
git checkout master
git merge Testing
git checkout Testing
vi index.html
git add .
git commit -m "Left Body padding added"
git tag -a REL02.00.01 -m "This is Release version 2.0.01"
git checkout Dev
git merge Testing
vi index.html
git checkout master
git merge Testing
vi index.html
git status
