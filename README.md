# script-group
for scripts

# Adding Scripts to group repo
1. Created the repo
2. Added collaborators
3. Added dev branch
```powershell
git checkout -b dev
```
4. Cloned repo to 
```powershell
git clone "link"
```
5. Created feature branch from dev branch
```powershell
git checkout dev
git checkout -b feature-branch
```
6. Set upstream to track local branch from origin
```powershell
git push -u origin feature-branch
```
7. Added files
```powershell
git add .
```
8. Committed and pushed files
```powershell
git commit -m "added feature"
```
9. Created pull request to merge from feature branch into dev branch
10. Merged branches 