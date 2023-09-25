# Hello Git

* git clone url.com
cd into the folder youve cloned
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
   * stage commit by clicking + icon in stage/changes
   * then click dropdown arrow to 'commit and push'