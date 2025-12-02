git init
Initialize git in a repository (Make sure its not already initiated by using "git status")

git status
lists files that have changed and their state

git add
adds files to the current stage

git commit -m "message"
create a commit with all staged files, sum up all changes in "message"

git log
lists all commits

git restore <commit hash>
reverts back the the specified commit

git remote add origin <git SSH>
adds the remote repository as "origin"

git remote -v
to check if the step above worked (should display a fetch and a pull address)

git push -u origin main
pushes the commit to the remote repository on github (for example), the -u allows you to push with just "git push" in the future

git pull
downloads the current state of files in the remote repository down to your local folder
