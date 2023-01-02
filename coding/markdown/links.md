---
id: 009fa10b-4263-4644-9a24-73f3aadc282e
created: 2022-10-31 16:53
keywords: 
  - #not-started
  - #permanent-note
authors:
  - Jan Lehmkuhl
---


Markdown Links
======================================================================

In Markdown können Links verwendet werden um auf URLs oder andere lokale zu verweisen und sind damit die Grundlage für eine verknüpfte Wissensdatenbank. 
Die Syntax ist dabei: 

    [Captian](URL)

Die [Markdown Übersichtsseite](README.md) wurde hier mit `[Markdown Übersichtsseite](README.md)` in den Fließtext eingebaut.  


Multi-Ebenen Links
------------------------------------------------------------

Mit optional auch mehrfach vorangestellten `../` (`../../`) lassen sich auch Dateien auf übergeordneten Ebenen finden. 
`Strg + Space` öffnet hier auch die Fuzzy-Suche und erleichtert den Bau der Verknüpfung. 

Absolute Links ab Workspace-Root funktionieren auch:  
[Test](/coding/markdown/markdown-paste-plugin.md)  

    [Test](/coding/markdown/markdown-paste-plugin.md)  


### Dateien verschieben
Werden Dateien im VS Code Datei-Explorer umbenannt oder verschoben, werden die relativen Pfade im Quelltext angepasst. 
Es müssen im Anschluss nur alle geänderten Dateien gespeichert werden. 
Wird ein zweifaches Verschieben hintereinander ohne speichern angewendet, gehen die Links verloren. 



RESOURCES
======================================================================
