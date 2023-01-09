<h1 align="center">Git Push - Git Clone</h1>

### Connect and Create new repo
Create a new repository on the command line
```
echo "# Repo Name" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin "repo URL"
git push -u origin main
```
#### Next ```commit``` steps:
```
git add .
git commit -m "Updating"
git push
```
### Clone repo to a new workstation
```
git clone "repo URL"
```
Creates a folder with the repo name with initialized git folder.
#### Next ```commit``` steps:
```
git add .
git commit -m "Updating"
git push
```
