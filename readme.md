git status -> to see the files and status under respective folder/directory.

git add . -> to add all files into staged layer
git add <fileName.ext> to add respective file
git commit "Message" to commit the files

git remote add origin -> <GitHub repo path>
git push origin <branch name> ex: master

git log -> to see the logs
git stash -> to get all the docs which are committed (to get clean copy with current chnages pushing to backstage)
git stash clear -> to clear the back staged stahsh files.
git stash pop -> to pull the back staged files

git branch <branchname> -> to add a branch
git checkout <branchName> -> to work with new branch or staging ares
git add .
git commit -> (this commiyts to new branch>
git checkout master/main -> to work with main/master branch we have to checkout
git commit
git merge <branchname> -> merging new branch commits to main/master branch


-Fork the community/organisation repo to your accound
-git clone <oraganisation repo url> in cmd to work in local
url which i jhave forked is called upstream url we can connect to upstream by below cmd
-git remote add upstream <forking repo url>
-git remote -v (to see all origin and upstream repos)



-git create brnch <branch name> ->and procced to chnages.
- git add and git commit -m to branch name < as pull requests has to be made from respective branches to avoid multi nerging>
-git checkout origin
-git reset --hard upstream/main ( to sync the main of forked from upstream)