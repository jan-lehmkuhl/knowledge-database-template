---
id: 22abc513-31f9-424b-b1a1-4594b53af330
created: 2023-01-10 07:35
keywords: 
  - #not-started
  - #permanent-note
---


Test Procedure Markdown Link Updates
======================================================================

During file movement markdown links should be adapted by [VS Code Link Updates](link-updater.md).  

Commit already staged files. 
[Stash](/coding/git/commands/stash/README.md) all changes in this git repository before executing.  

    git commit 
    git add * 
    git stash push



Move/Rename Files
------------------------------------------------------------

### Testfile  
[Link Updater (relative link)](./link-updater.md)  
[Link Updater (absolute link)](/coding/editors/vs-code/features/link-updater.md)  

The file is also referenced in: 
* [VS Code Plugin: Link Updater](/coding/languages/markdown/links.md#dateien-verschieben)  


### Test Procedure:  
1. Move Testfile in a subfolder "tasks".  
2. save and close all open editor tabs (Ctrl +Shift +W)  
3. rename Test-File  

4. check for: 
    * new links 
    * inside links

5. move file back  
6. check for: 
    * no changes there



Move/Rename Folder
------------------------------------------------------------

#not-working

### Testfolder with File
[images/markdown-dummy.md](images/markdown-dummy.md)  

This file is referenced in: 
* [link-updater](link-updater.md)  


### Test Procedure:  
1. rename testfolder
2. check links in referenced files
3. move testfolder into subfolder
4. check links in referenced files



Debugging
------------------------------------------------------------
* Try restarting VS Code



RESOURCES
======================================================================

earlier done by a [plugin](../../../editors/vs-code/plugins/markdown-link-updater.md)  
