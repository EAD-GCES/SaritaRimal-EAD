How to be a contributor to open-source projects?
Sign in to GitHub
Fork the project repository
Clone your fork (git clone URL_of_fork)
Navigate to your local repository(cd NAME_OF_REPOSITORY.)
Check that your fork is the "origin" remote (git remote -v) or (git remote add origin URL_OF_FORK.)
Add the original project repository as the "upstream" remote (git remote add upstream URL_OF_PROJECT.)
Pull the latest changes from upstream into your local repository (git pull upstream main)
Create a new branch (git checkout -b BRANCH_NAME)
Make changes in your local repository
Commit your changes (git add -A) and (git commit -m "DESCRIPTION OF CHANGES")
Push your changes to your fork (git push origin BRANCH_NAME.)
Begin the pull request
Create the pull request
Review the pull request by the owner
Add more commits to your pull request
Discuss the pull request
Delete your branch from your fork
Delete your branch from your local repository (git checkout master) and (git branch -D or -d BRANCH_NAME)
Synchronize your fork with the project repository (git pull upstream master in project repo) and (git push origin master in your fork)