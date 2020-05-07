# GIt-utils
# Git rebase easy steps


## INITIALISE GIT BASH ON THE SPECIFIED FOLDER

for creating new branch:

                      
                                               
                                                 git checkout -b <branch_name>
                                                 git branch
                                               
jump back to master branch:
 
                                                 git checkout master
                                                 vi <filename>
                                                 //edit the contents of the file
                                                 git add .
                                                 git commit -m "commit message"
                                                 git log
                                                 

checkout to the feature branch:

                                                 git checkout <feature_branch>
                                                 vi <filename>
                                                 //edit the contents
                                                 git add .
                                                 git commit -m "commit message"
                                                 git rebase master
                                                 
