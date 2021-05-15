# The Most Used Git's Commands
This repository contain the most used git commands

## Help
##### General
      git help

##### Especific Command
      git help add
      git help commit
      git help <any-command>
      
## Configuration
#### General
##### Set User's Name
      git config --global user.name "Your Name"
      
##### Set User's Email
      git config --global user.email <Your-Email>
      
##### Set User's Editor
      git config --global core.editor <Your-Editor>
      
##### Set Merge's Tool
      git config --global merge.tool vimdiff
      
##### Set Files to Ignore
      git config --global core.excludesfile ~/.gitignore
      
##### List Your Git's Config
      git config --list
      
## Local Repository
#### Create a New Local Repository
      git init
       
#### Verify Files and/or Directories Status
      git status
      
#### Add Files and/or Directories to Staged Area
##### Add an Especific File
      git add <file-name>
      
##### Add an Especific Directory
      git add <repository-name>
      
##### Add All Files and Directories
      git add -A
     
##### Add an Especific File Listed on .gitignore (Local or Global)
      git add -f <file-name>
      
#### Remore Files and/or Directories from Staged Area
##### Remove an Especific File
      git rm <file-name>
      
##### Remove an Especific Directory
      git rm -r <directory-name>
      
#### Commit Files/Directories
##### Commit an Especific File
      git commit <file-name>
      
##### Commit Some Files
      git add <first-file-name> <second-file-name>...
      
##### Commit an Especific Directory
      git commit <directory-name>
      
##### Commit All Staged Files and Directories with a Message (After Added Files and Directories on Staged Area with Git Add)
      git commit -m "You Commit's Message"
      
#### View History
##### Show History
      git log
      
##### Show History with Diff of the Last Two Changes
      git log -p 2
     
##### Show History Summary (Full Hash, Author, Date, Comment and Change Number (+/-))
      git log --stat
      
##### Display Summary Information in one Line (Full Hash and Comment)
      git log --pretty=oneline
