# Steps to make a local repo and push it to GitHub : 
### first step is to make empty repo on GitHub 
### second step is to make local repo on on your computer :
- make an empty directory using command `mkdir directory name`
- go into this directory using command `cd directory name`
- use command `git init` to make new repo
- use command `echo "# w" file-name.md` to make markdown file
- use command `git add .` to track all untracked files
- use command `git commit -am "initial commit"` to make new commit

### third step is to push this repo on GitHub :
- use command `git remote add origin URL` to link the local repo with the remote one
- use command `git branch -M main` to change the name of the master branch
- use command `git push -u origin main` to push to empty GtiHub repo
