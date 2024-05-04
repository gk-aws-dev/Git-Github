# Stages/Structure for the Git: 

## Working directory: 
- This is your local directory where you make the project (write code) and make changes to it. suppose we edit any file and saved then it will come in wrking directory

## Staging Area (or index): 
- this is an area where you first need to put your project before committing. This is used for code review by other team members.
- by using ```git add .``` command we can move our project from working to stage directory.

## Local Repository: 
- this is your local repository where you commit changes to the project before pushing them to the central repository on Github. This is what is provided by the 
  distributed version control system. This corresponds to the .git folder in our directory.
- ```git commit -m "your message here"``` with this command we can make commit for the our project.
- ```git status``` this command will give us the status for the project as where our project is.

## Push to github
``` git push origin master``` with this command we can push our commited project into github.

-----------------------------------------------------------------------------------------------

```
// transfers your project from working directory
// to staging area.
git add .

// transfers your project from staging area to 
// Local Repository.
git commit -m "your message here"


// transfers project from local to central repository.
// (requires internet)
git push
```
