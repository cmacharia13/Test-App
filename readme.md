# Hello Git

* git clone (url.com)
* cd . into the folder youve cloned
* git status 
* git add readme.md
* git commit -m "Readme file updaated"
* git remote add origin https://github.com/cmacharia13/Test-App.git // already cloned repo we dont need origin but can do it just be to safe.
* git push -u origin main

* 'git add' can have multiple endings:
 * git add readme.md
   * adds a single file to staging area
 * git add readme.md index.ts
  * add two files to staging area
 * git add.
  * this will add all changed files to the staging area
 * git add *
  * add all changes in the curent  directory but not the sub directory
 * git add - add OR git add -A
  * adds hidden files but try not to add them. .gitignore is an exception

  # VS
  * Using git change = can use GUI instead of command line interface
  * if you dont see git change = view-git changes

  # VS Code
  * on left side, theres a git symbol = git gui tool
  * shows changes you have made in application
 * to commmit the change 
   * type a message for Git to highlight whats been change: 'readme updated with instructions'
   * stage commit by clicking + icon in changes
   * then click dropdown arrow to 'commit and push'

## Version Numbers of Applications
* 1.0.0
* The far right 0.0.1 <- Is a minor change to the applcation
* 0.0.2 <- A minor change from 0.0.1
* The middle number 0.1.0 <- is a bigger change but not a drastic move
* The first number 2.0.0 <- is a major release of an application / programme / software tool
* https://support.apple.com/en-gb/HT213407#1601 for reference

## Branching
* We can use brnaching to allow engineers to try different solutions without causing issues on the main codebase
* git branch example
* git checkout example

* To merge with main, we need to do the following:
* git checkout main
* git pull origin main // to get the latest from main
* git merge example
* git push origin main
* Sometimes, we don't need to keep the test branch alive, so we can delete the branch:
* git branch -d example
* git branch -D example // this will force the branch to delete even if there are unmerged changes

## Going back on previous commits
* git checkout -b old-commit (commit hash number)