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

Das Einfügen dieser Links wirst du jedoch so oft ausführen, dass es sinnvoll ist hierfür ein [Snippet](../../vs-code/snippets.md) plus [Shortcut](../../vs-code/keyboard-shortcuts.md) anzulegen. 



Multi-Ebenen Links
------------------------------------------------------------
Mit optional auch mehrfach vorangestellten `../` (`../../`) lassen sich auch Dateien auf übergeordneten Ebenen finden. 
`Strg + Space` öffnet hier auch Intellisense und erleichtert den Bau der Verknüpfung.  

### Knowledge Base link
Absolute Links ab Workspace-Root funktionieren auch:  
[Test](/coding/vs-code/plugins/markdown-paste.md)  

    [Test](/coding/markdown/markdown-paste-plugin.md)  

Gerade in komplexen Strukturen ist es sinnvoll hierüber den Link zu erstellen. 
Der Befehl `File: Copy Relative Path of Active File` kopiert diesen Pfad in die Zwischenablage und wird direkt in das Snippet `markdown link knowledge base` eingefügt.  
Auch hierfür ist das Snippet mit einem Shortcut garniert sehr hilfreich.  



Dateien verschieben
------------------------------------------------------------
Werden Dateien im VS Code Datei-Explorer umbenannt oder verschoben, werden normalerweise die relativen Pfade im Quelltext angepasst. 
Dieser Prozess sollte aber ab und zu überprüft werden. 
Oft hilft hier schon ein Neustart von VS Code. 



Links zu Überschriften
------------------------------------------------------------
Es können auch Links zu Überschriften erstellt werden. 
Diese werden einfach mit Raute angegeben. 

    [Abschnitt 1](#dateien-verschieben)

Obiger Link führt einfach zum [vorherigen Abschnitt](#dateien-verschieben) 
und kann natürlich auch auf andere Dateien verweisen:  

    [Description](/README.md#benefits-of-note-taking)




RESOURCES
======================================================================
