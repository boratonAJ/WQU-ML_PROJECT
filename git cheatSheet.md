* # setting ssh key:
    * # on linux and mac
            * ls -al ~/.ssh : test the presence of a .ssh file
            * cd ~/.ssh
            * ssh-keygen -t rsa -b 4096 -C "<any comment| email>" : 
                * -t for the type of algorithm 
                * -b for the number of bit of the key 
                * -C comment
            * 
            
* # git Config:
        * git config --global <particular global variable to edit <value> >
        * git config --edit --global 
            * show all the global variables to be edited in a text editor 
* # git add
        * git add .
        * git add -A
        * git add <name of file>

* # git commit:
        * git commit -m "<commmit message>": commit your add changes to ur select branch
        * git commit -am "<commmit message>": add file changes into the staging area and commit that into the local repository branch"
* # git status:
        * show the status of ur present files in relation to the past file
* # git log:
        * show you the state of all commits carried out( show you all existing snapshots taken)
        * show your the various branch names and commit name 
* # git branch:
        * git branch "<name of new branch>"
* # git checkout:
        * git checkout "<name of branch>" : checkout a particular branch
        * git checkout -b "name of branch" : creates a new branch then check it out 
* # git switch:
        * git switch <commit>
        * git switch -c <new_branch_name>
* # git diff:
        * git diff <branch 1>..<branch 2>: difference between the file changes of latest commit  of two braches
        * git diff <branch 1>...<branch 2>: difference between the files changes of branch 2 and the common parent node(commit) of both 1 and 2 
        * git log  <branch 1>..<branch 2>: difference between the commit history of two branches
        * git diff <branch 1>..<branch 2> -- <filename>: compare between one file of two branches 
* # git clone:
        * git clone <url>: clones a remote repository to your local machine
        should not be used with git init 
        use git clone a file that lacks the .git file
* # git submodule:
        * git submodule add <url>
        
* # git fetch:
        * git fetch <url>: used to fetch update from a cloned remote repository. This should alway be done before a push is done
* # git merge:
        * merges your fetch repository to your local repository to make sure no conflicts have taken place
        
* # git pull:
        * git fetch + git merge 
        
* # git push:
        * git push -u [origin] <branch>: Pushing up to a github remote repository branch

* # 
        