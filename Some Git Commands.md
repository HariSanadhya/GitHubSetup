# GitHubSetup

## create a new repository on the command line

create a new repository using the GITHUB and copy the git path for that repository.
goto the desired location on your system and initialize git repository **git init**
Now initialize the remote git path into a variable - **git remote add origin <GIT URL>**. Here origin is the variable name. it can be anything. 

**git pull origin master** - to pull from github to local drive 

<b>git add \<FILENAME\> OR git add * </b> to add a specific file or all the files in the local drive's current location to the list of files to be moved to github repository 

**git commit -m "commit message" ** Commits the changes that are to be moved to github. Files are not yet moved. 

**git push -u origin master** - pushes the commited changes to Github repository

**git remote -v** gives the list of all the remote variables created and their values (git url's that they refer to)
