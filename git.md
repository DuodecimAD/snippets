## Git snippets

### Revert all changes before getting update
git fetch  
git reset --hard origin/branchName  
git pull

### Stash my changes to a new branch
git stash  
git checkout -b newBranchName  
git stash pop

### Move around branches
git checkout branchName

### Pull branch only
git pull --branch branchName

### Clone only the branch
git clone --branch branchName git@git.

### Add extra remote to push to 2 remote in 1 push
git remote -v  
git remote set-url --add --push origin git@git.  
git remote set-url --add --push origin git@github.com:
