Hello Git and Github

git reset HEAD 7digit of last commit  //Go back to last commit, resotre the file before change
git reset --hard commit_id // work the same way
git checkout HEAD <file name>     // Show the file under current commit
git checkout -- <file name>

git log //check all the commit in the pwd
git reflog //check all the history ever presented
git add <file names> or . // add files in staging


git show HEAD <file name> //See what happened to the file
git checkout HEAD <file name> //Go back to previous commit
git reset HEAD <file name> // Unstage , remove it from current staging
 
git branch //check what branch you are on
git branch name //create a new branch
git checkout name //switch to new branch
git merge name // switch back to master and merge the content from new branch
//if there is a conflict, git will show different version in the file, simply delete the one you don't want and make a new commit
git branch -d name //delete the branch after you finishing merge the content


Teamwork
git clone remote_location clone_name  //HAVE A DUPILICATE file on local git
git remote -v  //list the content of remote git
git fetch  //if the remote do anything change
git merge origin/master     //merge the remote to local branch

git push origin your_branch_name  // update the branch you create, not the whole git.

git clone: Creates a local copy of a remote.
git remote -v: Lists a Git project’s remotes.
git fetch: Fetches work from the remote into the local copy.
git merge origin/master: Merges origin/master into your local branch.
git push origin <branch_name>: Pushes a local branch to the origin remote.
