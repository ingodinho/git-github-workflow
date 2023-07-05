# Workflow für ein kleines Team auf GitHub

Dies ist eine Schritt-für-Schritt-Anleitung für einen einfachen Workflow auf GitHub, der für ein kleines Team von 2 bis 3 Personen entwickelt wurde. Dieser Workflow beinhaltet das Arbeiten auf eigenen Branches und das Verwenden von Pull Requests.

## Schritt 1: Repository erstellen und einrichten

1. Erstelle ein neues Repository auf GitHub.
2. Lade die anderen Teammitglieder ein, indem du sie zu Collaborators für das Repository hinzufügst.

## Schritt 2: Projekt einrichten

1. Jedes Teammitglied klont das Repository auf seinen lokalen Computer: `git clone <repository-url>`.
2. Wechsle in das lokale Repository-Verzeichnis: `cd <repository-name>`.

## Schritt 3: Branch erstellen und wechseln

1. Erstelle einen neuen Branch für deine Arbeit: `git branch <branch-name>`.
2. Wechsele zum neuen Branch: `git checkout <branch-name>`.

## Schritt 4: Arbeit durchführen

1. Führe deine Änderungen am Code oder den Dateien aus.
2. Füge die geänderten Dateien zum Commit hinzu: `git add <file-name>` (oder verwende `git add .`, um alle geänderten Dateien hinzuzufügen).
3. Mache einen Commit mit einer aussagekräftigen Beschreibung: `git commit -m "Beschreibung der Änderungen"`.

## Schritt 5: Branch auf den Remote-Server pushen

1. Pushe deinen Branch auf den Remote-Server: `git push origin <branch-name>`.

## Schritt 6: Pull Request erstellen

1. Gehe zum Repository auf GitHub.
2. Klicke unter dem Repository-Namen auf **branches** um in die Branchübersicht zu gelangen
3. Klicke auf den **Compare & pull request**-Button neben deinem Branch.
4. Überprüfe die Änderungen im Pull Request und füge, falls notwendig, zusätzliche Informationen hinzu.
5. Klicke auf **Create pull request**, um den Pull Request zu erstellen.

## Schritt 7: Review und Zusammenführung

1. Die anderen Teammitglieder können den Pull Request überprüfen, Kommentare hinzufügen und Verbesserungsvorschläge machen.
2. Nach dem Review und eventuellen Anpassungen kann der Pull Request vom Teammitglied, das den Pull Request erstellt hat, zusammengeführt werden.
3. Der Branch wird in den Hauptzweig (normalerweise "main" oder "master") des Repositories zusammengeführt.

## Schritt 8: Lokale Kopien aktualisieren

1. Jedes Teammitglied muss seine lokale Kopie aktualisieren, um die neuen Änderungen zu übernehmen:
   - Wechsle zum Hauptzweig: `git checkout main` (oder entsprechendem Hauptzweig-Namen).
   - Aktualisiere den Hauptzweig: `git pull origin main`.
2. Wechsle anschließend mit `git checkout <branch-name>` zurück zum eigenen Branch. Führe dann den Befehl `git merge main` aus, um die aktuellsten Änderungen aus dem Hauptzweig (normalerweise "main" oder "master") in den eigenen Branch zu übernehmen. Alternativ kannst du für weitere Arbeiten auch einen neuen Branch erstellen, ähnlich wie im Schritt 3 beschrieben. Beachte jedoch, dass du in diesem Fall den nicht mehr benötigten Branch gemäß Schritt 9 löschen solltest.

## Schritt 9: Branches löschen

1. Um einen lokalen Branch zu löschen, nachdem die Änderungen übernommen worden sind, verwende den Befehl: `git branch -d <branch-name>`.