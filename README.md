# Assignment: Data-Manager in Javascript (oder Typescript)

### Entwickle einen Datei-Manager in JS mit folgender Funktionen

* Benutzer soll Datein und Verzeichnisse:
  * Erstellen
  * Durchsuchen
  * Bearbeiten
  * Löschen
  * Kopieren 
  * Verschieben
  * Umbenennen
* können


* Der Benutzeroberfläche soll über die Befehlszeile (Terminal, CLI) erfolgen,
mit klaren Befehlen und Rückmeldungen. 
* Tipp: Stellt euch die was der Benutzer machen könnte wie kann ich das verhindern? 
Unerwartete eingaban etc.

* Empfohlene Libaries:
  * Readline
  * fs
  * path 

### **Bouns**: 
* Der Benutzer soll mit einem Befehl Inhalte von Files displayen können
* Der Benutzer soll mit einem Befehel directory-size sehen können in Bytes (bsp: 2048 Bystes)
* Der Benutzer soll mit einem Befehel file-size sehen können in Bytes (bsp: 2048 Bystes)



### Beispiel Anwendung:

```sql
Willkommen zum erweiterten Datei-Manager.

> create-file example.txt
Datei "example.txt" erfolgreich erstellt.

> create-directory new-folder
Verzeichnis "new-folder" erfolgreich erstellt.

> list
Verzeichnisinhalt:
- example.txt (Datei)
- new-folder (Verzeichnis)

> copy-file example.txt copy-of-example.txt
Datei "example.txt" erfolgreich nach "copy-of-example.txt" kopiert.

> move-file copy-of-example.txt new-folder/copied-example.txt
Datei "copy-of-example.txt" erfolgreich nach "new-folder/copied-example.txt" verschoben.

> rename-file new-folder/copied-example.txt renamed-example.txt
Datei "new-folder/copied-example.txt" erfolgreich in "new-folder/renamed-example.txt" umbenannt.


// Bonus Anfang
> get-file-size example.txt
Dateigröße von "example.txt": 1024 Bytes.

> get-directory-size new-folder
Größe von "new-folder": 2048 Bytes.

> display-file-content example.txt
Inhalt von "example.txt":
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
...
// Bonus Ende

> delete-file example.txt
Datei "example.txt" erfolgreich gelöscht.

> delete-directory new-folder
Verzeichnis "new-folder" erfolgreich gelöscht.


```
