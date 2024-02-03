---
id: 4e3f503f-5aee-4e25-b0cd-a4e4b5a97777
created: 2023-12-17 17:07
keywords: 
  - #permanent-note
---


VS Code Settings
======================================================================

Every User has its own settings stored locally and can be [synced](#user-settings-sync). 
Beside them every workspace can have additional workspace settings.  


User Settings Sync
------------------------------------------------------------

[first do empty sync] because of a bug:  

1. `Settings Sync: Turn On...`
   choose no option to sync
2. `Settings Sync: Configure...`
   select all options


in VS Code settings special values can be excluded from sync: 

~~~json 
"settingsSync.ignoredSettings": [EXCLUDE_LIST],
~~~



RESOURCES
======================================================================

[code.visualstudio.com - settings](https://code.visualstudio.com/docs/getstarted/settings)  
[code.visualstudio.com - settings sync](https://code.visualstudio.com/docs/editor/settings-sync)  

[first do empty sync]: https://github.com/microsoft/vscode/issues/102841



RESOURCES
======================================================================
