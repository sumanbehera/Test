To map remote repository to the local repository

git remote add <alias name> <remote repository address>
git remote add sp https://github.com/sumanbhr231/spring-petclinic.git

To check if any url is mapped to local repository below command is used
git remote -v
if no result returns, means nothing is mapped.

Now we want to push command from local repository to remote repository
git push <alias> <branch>
git push sp master

Git Flow
========

git init: Through this git initialised

git status: through this file is tracked in which state after creation

git add: this is used to move the changes from working area to staging area
 
git commit: this is used to move the changes from staging area to local repository

git remote add: this is used to map the remote repository with local repository

git push: this is used to push the changes from local repository to remote repository
