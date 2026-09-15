# Wacht und betet

Gebetstimer: drei Gebetszeiten, Stoppuhren, Tagesvers, Wochen- und
Monatsübersicht. Ziel ist eine Stunde Gebet am Tag.

Unter "Einstellungen" auf der Startseite: Namen und Themen der drei
Gebetszeiten ändern, Dauer und Tagesziel anpassen, Daten als JSON
sichern und einlesen sowie die Geräte-Synchronisierung einrichten.

Eine einzige Datei (`index.html`), kein Build, keine Abhängigkeiten.
Ohne Synchronisierung bleiben die Daten nur im Browser des Geräts.

## Auf GitHub Pages veröffentlichen

1. Diese Dateien in ein Repository laden (`index.html` muss im Wurzelverzeichnis liegen).
2. Im Repository: Settings → Pages.
3. Unter "Build and deployment" als Source **Deploy from a branch** wählen,
   Branch `main` und Ordner `/ (root)`, dann Save.
4. Nach ein bis zwei Minuten ist die Seite unter
   `https://<benutzername>.github.io/<repository>/` erreichbar.

Die Datei `.nojekyll` sorgt dafür, dass GitHub die Seite unverändert ausliefert.
