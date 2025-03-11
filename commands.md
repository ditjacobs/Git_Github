# Commands

`git init`: initialize a git repository; note: make sure that no git repositories exist in the current folder

`git add`: add the file to the staging area, preparing for commiting. (See more details in the concepts dictionary)

`git commit -m "meaningful msg"`: commit the file with a meaninful message explaining why/how/effects/limitations things changed. Commits the version/snapshot of the file in the timeline 

`git status`: check the status in git 

`git remote add name ssh`: creating a bridge between local and remote repository, only has to be done once

`git push`: push all COMMITED contents to Github. Note first time pushing use: `git push --set-upstream origin main`

`git push`: push contents to Github from local repository

`git pull`: pull contents from Github to local repository 

`git revert <commit ID>` => creates a new commit that is the same as the chosen one

`git clone <ssh remote>` => creates a local repository, creates "the bridge" and pulls the complete project (commit history)

`git tag name`: create a tag to the HEAD committed job

<<<<<<< HEAD
`git tag name commitID`: add a commitID to add the tag to specific commited job

`git checkout name`:to move between branches and commits

`git show`:show differences between commited jobs
`git tag commitID`: add a commitID to add the tag to specific commited job
=======
`git checkout name`:to move between branches and commits

`git show`:show differences between commited jobs

`git tag commitID`: add a commit ID to add the tag to specific commited job
>>>>>>> 0eb4f0a2e279cff4cb261f16814dd14184787896

`git branch -l`: list the local branches

`git branch -a`: list all branches, local and remote

`git push --set-upstream origin <branch name>`: push new branch and create a corresponding branch remote
<<<<<<< HEAD
=======

>>>>>>> 0eb4f0a2e279cff4cb261f16814dd14184787896
