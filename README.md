# Git und GitHub: erste Arbeitskopie

Data Analytics · WS 2026/27

Git hält Änderungen an Dateien fest. Ein Repository enthält die Dateien und ihre Versionsgeschichte. GitHub speichert eine gemeinsame Kopie. Ein Commit beschreibt einen gespeicherten Arbeitsstand; ein Branch ermöglicht Änderungen, bevor sie in den Hauptstand übernommen werden.

## Vorbereitung

Voraussetzung: Ein GitHub-Konto mit Zugriff auf diese Vorlage. Für diese Übung genügt der Browser.

## Eigene Arbeitskopie

1. Auf GitHub „Use this template“ und „Create a new repository“ wählen.
2. Einen eigenen Repository-Namen vergeben und die Sichtbarkeit „Private“ wählen.
3. Das eigene Repository mit GitHub Desktop oder dem vorhandenen Git-Werkzeug klonen.
4. Ein Terminal im geklonten Projektordner öffnen.

Bei einer Zuweisung über GitHub Classroom stattdessen die dort erzeugte Arbeitskopie verwenden.

## Erste Änderung

1. Im eigenen Repository einen Branch namens `erste-aenderung` erstellen.
2. Die Datei `PROJEKT.md` öffnen.
3. Die Fragestellung und das gewünschte Ergebnis in eigenen Worten ergänzen.
4. Die Änderung mit der Nachricht „Fragestellung ergänzen“ committen.
5. Einen Pull Request vom eigenen Branch nach `main` öffnen.
6. Im Reiter „Files changed“ die Änderung prüfen.
7. Den Pull Request in das eigene `main` zusammenführen.
8. Die Commit-Historie öffnen und die Änderung nachvollziehen.

Prüfkriterium: `PROJEKT.md` enthält die eigene Fragestellung im Hauptbranch. Der Pull Request zeigt die zugehörige Änderung.

## Lokale Arbeit

Für die späteren Python-Übungen wird das eigene Repository auf den Rechner geklont. Ein lokaler Commit wird erst durch Push auf GitHub übertragen. `.venv`, Zugangsdaten und vertrauliche Daten gehören nicht in ein Repository.

Weitere Erklärungen: [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow) und [Repository klonen](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

Grundlage: github-starter-course aus data-analytics-ws2425.
