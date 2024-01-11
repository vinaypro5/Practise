Git-Practice1
creating repo for git practice

this repo contains basic shell scripts and python scripts

UNDERSTANDING THE WORKSPACE AND STAGING AREA AND LOCAL REPOSITORY*

Creating workspace

git initialization

Creating files with some content in the working directory

Adding these files to staging area

Git Configurations before first commit

Commit those changes to local repository.

CREATING WORKSPACE : mkdir cd

GIT INITIALIZATION: git init

CREATING FILES: by using nano/touch/vim we can create files and insert content (nano/vim).

ADDING FILES TO THE STAGING AREA: git add . (it refers all files in that folder) git add (refers only given file name)

GIT CONFIGURATION: git config --global user.name "git userid" git config --globaluser.email "git email"

COMMIT : commit the changhes with command git commit -m "need to give commit message here"

###########################################################################

To check last modify by user for ecah line of a file use command = git blame file_name
switch to a new branch in one step - git checkout or git swith -c branch_name
