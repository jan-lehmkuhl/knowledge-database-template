---
id: 5026a3ea-d360-4080-8e43-9fd1802c9a1e
created: 2023-12-16 17:44
keywords: 
  - #permanent-note
---


Example
======================================================================

To make your first steps with git you can try following commands. 
These commands can be executed and will show you some basic stuff.  


init repository
------------------------------------------------------------

    # create and goto new directory
    cd ~/tmp
    mkdir test
    cd test

    # creates a git repository in the current folder
    git init


first commit
------------------------------------------------------------

### change file
    nano file1.txt

change some lines and save the file afterwards

    git status


### stage file 
add `file1.txt` or their changes to the staging area  

    git add file1.txt
    git status 


### commit staged changes
    git commit -m "first commit"
    git status 
    git log


second commit
------------------------------------------------------------

    nano file1.txt
    git status
    git add file1.txt
    git status
    git commit -m "second commit"
    git log --oneline


checkout an old commit 
------------------------------------------------------------

    git log --graph --oneline --all

The numbers before the commit message are the commit hashs. 
They are unique identifier for every commit. 

    git checkout HASH_FROM_OLD_COMMIT

    # review content
    cat file1.txt

    # checkout latest commit
    git checkout master
    cat file1.txt




RESOURCES
======================================================================
