---
id: 1aff7050-b765-49d6-bfe5-56251b1aaab8
created: 2023-12-10 17:27
keywords: 
  - #permanent-note
---


Open Folder as Workspace
======================================================================

A [Visual Studio Code](README.md) "workspace" is the folder that is opened in a VS Code window (instance).  

To open a folder as workspace search command `File: Open Folder...` and choose in the following pop-up window your desired folder. 
After opening the workspace you will see the files and folders in the explorer of VS Code. 


.vscode in root
------------------------------------------------------------

If you want to open the [knowledge base template](https://github.com/jan-lehmkuhl/knowledge-database-template) you should ensure, that the folder `.vscode` is in the root level of your workspace. 
This specific folder contains settings like [code-snippets](snippets.md) which VS Code needs to load for an adequate using of this template. 

To control if you have opened the correct folder, you can open the terminal with the [command](command-palette.md) `Terminal: Create New Terminal (In Active Workspace)`. 
The new terminal starts in your workspace root folder, which you should see directly or get with: 

    # bash
    pwd

    # powershell
    $pwd.Path

    # windows command prompt
    echo %cd%




RESOURCES
======================================================================

[code.visualstudio.com - workspaces](https://code.visualstudio.com/docs/editor/workspaces)    
[code.visualstudio.com - multi root workspaces](https://code.visualstudio.com/docs/editor/multi-root-workspaces)  
