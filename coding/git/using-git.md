---
id: ac639fab-4e1d-4f61-bd7f-2ef20074d346
created: 2023-12-16 14:53
keywords: 
  - #permanent-note
---


Common commands git
======================================================================

The most important part in using `git` is to be aware of the actual status of git ([see](#get-an-overview)). 
This should be done during all other executions. 

Furthermore I listed here some my most common commands & tools I use. 



Add content to git
----------------------------------------------------------------------

### initialize the repository

    git init

Creates an git repository in the actual folder 
(dont forget `mkdir` and `cd` before). 
The success is seen in the terminal output and in the new folder `.git` inside the actual folder. 


### stage content
Before you can finally commit changes to the repository the have to be collected ("staged"). 

    git add FILETOSTAGE

After staging this can be checked by `git status` ([see](#git-status)). 


### commit content
This creates the actual contribution to the repository by committing the previously staged content. 

    git commit -m "COMMITMESSAGE"

Be accurate in formulating the commit message. 
This is what everyone sees.


### reset last commit
As long you have not shared your commits ([pushen](#push-content)), you can undo them.

    git reset --soft HEAD~1 

Please be very careful and keep the [overview](#get-an-overview) over your repository. 


### push content
If you contribute to a shared online repository, this is the final step to publish your commits: 

    git push



Get an overview
----------------------------------------------------------------------

You can do so with `git gui` and `gitk` but I prefer to use some combined terminal command which might be also helpful for you.

### git status

`git status` is the most important command, which displays similar details like `git gui`. 
After some time you dont need the explanations around `git status` and the short form is more convenient

    git status --short 


### git log --graph

`git log` tells you something about the latest commits (like `gitk`). 
The option `--graph` adds some nice views about the course of the commits. 

    git log --graph --oneline --all



.gitignore
----------------------------------------------------------------------

If you place a `.gitignore` file inside a project or subfolder, you can specify special files which should not be tracked. 
This is important for calculated data, which has no need to be versioned.  
(see [workflow-gitignore](https://gitlab.com/schlupp/example-cfdof-workflow/blob/master/.gitignore))  

To create a `.gitignore` might be difficult in a GUI especially in Windows. 
In this case use the command `touch` in "git bash" or WSL:  

    cd SOME_FOLDER
    touch .gitignore



use .gitconfig
----------------------------------------------------------------------

Personally I use a much more complex command for `git status` or `git log --graph` by naming some aliases which I can call instead. 
Below are some examples from my `.gitconfig` file. 

~~~bash
[alias]
    s = status
    lognice =   log --graph --abbrev-commit --decorate --pretty=tformat:'%C(dim cyan)%h%C(reset)%C(bold yellow)%<(2,trunc)%d%C(reset) %C(dim green)%<(12,trunc)%aN%C(reset) %C(cyan)%s%C(reset) -%C(yellow)%d%C(reset) %C(dim red)(%ar) '
~~~

With them I can use 

    git s

instead of the longer `git status`




RESOURCES
======================================================================
