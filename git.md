// revert all changes before getting update
git fetch
git reset --hard origin/branchName
git pull

// check all branches
git branch -a

// stash my changes to a new branch
git stash
git checkout -b newBranchName
git stash pop

// move around branches
git checkout branchName

// pull branch only
git pull --branch branchName

// merge branch
git checkout main
git pull
git merge branchName

// delete branch locally
git branch -d branchName
git branch -D branchName // force

// delete branch remote 
git push origin --delete branchName

// clone only the branch
git clone --branch branchName gitadress

// add extra remote to push to 2 remote in 1 push
git remote -v
git remote set-url --add --push origin git@git.address
git remote set-url --add --push origin git@github.com:address
