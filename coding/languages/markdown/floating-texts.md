---
id: 7dae5f13-1ac6-481d-a36d-1787b4f0bbbe
created: 2022-10-28 20:50
keywords: 
  - #not-started
  - #permanent-note
---


Fließtexte
======================================================================

### One Sentence per Line
In Markdown Files sollte jeder Satz eine einzelne Zeile bekommen. 
In der gerenderten Ansicht wird hier allerdings kein Zeilenumbruch eingefügt ([next chapter](#two-spaces-for-a-paragraph)). 

Diese Zeilenaufteilung ist für die Versionsverwaltung besser, aber es lassen sich so auch Texte im Source Code besser lesen. 
Außerdem erleichtert dies das Text umschreiben gewaltig. 


### Two Spaces for a Paragraph
Um nach einem Satz einen Zeilenumbruch zu forcieren kann man zwei Leerzeichen (`  `) ans Zeilenende anfügen.  
Oder man kann eine extra Leerzeile einfügen. 
Diese Möglichkeiten existieren auch in Auflistungen. 

Es ist darauf zu achten dass die Leerzeichen beim speichern nicht gelöscht werden. 
Diese Einstellung wird häufig für Source Code verwendet. 
Wenn dieses so ist, kann diese [Einstellung](../../vs-code/settings.md) für Markdown in VS Code deaktiviert werden mit:  

~~~json
    "[markdown]": {
        "files.trimTrailingWhitespace": false,
    },
~~~




RESOURCES
======================================================================
