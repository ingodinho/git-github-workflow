## Wichtige Git-Befehle

### Git initialisieren

- `git init` - Initialisiert ein neues Git-Repository im aktuellen Verzeichnis.

### Änderungen erfassen

- `git add <file>` - Fügt eine Datei oder Änderungen zu einem Commit hinzu.
- `git diff` - Zeigt die Unterschiede zwischen dem Arbeitsverzeichnis und dem Repository an.
- `git diff --cached` - Zeigt die Unterschiede zwischen dem Staging-Bereich und dem Repository an.

### Commits erstellen

- `git commit -m "<message>"` - Erstellt einen Commit mit einer aussagekräftigen Nachricht.

### Remote-Repository verwalten

- `git remote add <name> <url>` - Verknüpft ein Remote-Repository mit einem Namen und einer URL.
- `git remote remove <name>` - Entfernt die Verknüpfung zu einem Remote-Repository.
- `git remote rename <old-name> <new-name>` - Benennt ein Remote-Repository um.
- `git remote` - Zeigt eine Liste der Remote-Repositories an.
- `git remote -v` - Zeigt eine detaillierte Liste der Remote-Repositories mit ihren URLs an.

### Branches verwalten

- `git branch` - Zeigt alle Branches im Repository an.
- `git branch <name>` - Erstellt einen neuen Branch.
- `git branch -d <name>` - Löscht einen lokalen Branch.
- `git branch -M <new-name>` - Benennt den aktuellen Branch um.
- `git checkout <branch>` - Wechselt zu einem anderen Branch.
- `git merge <branch>` - Führt Änderungen aus einem anderen Branch in den aktuellen Branch zusammen.

### Synchronisieren mit Remote-Repository

- `git push <remote> <branch>` - Überträgt lokale Commits auf das Remote-Repository.
- `git pull <remote> <branch>` - Aktualisiert die lokale Kopie mit den neuesten Änderungen aus dem Remote-Repository.

### Git-History anzeigen

- `git log` - Zeigt die Commit-History an.
- `git log --oneline` - Zeigt die Commit-History in einer kompakten Form an.

### Weitere hilfreiche Befehle

- `git status` - Zeigt den Status der Arbeitskopie und des Repositories an.
- `git clone <url>` - Klonen eines Remote-Repositorys auf den lokalen Computer.

