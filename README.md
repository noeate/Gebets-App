# Wacht und betet

Gebetstimer: drei Gebetszeiten, Stoppuhren, Tagesvers, Wochen- und
Monatsübersicht. Ziel ist eine Stunde Gebet am Tag.

Unter "Einstellungen" auf der Startseite: Namen und Themen der drei
Gebetszeiten ändern, Dauer und Tagesziel anpassen, Daten als JSON
sichern und einlesen sowie die Geräte-Synchronisierung einrichten.

Die App läuft offline und lässt sich auf den Home-Bildschirm legen.
Ohne Synchronisierung bleiben die Gebetszeiten nur im Browser des Geräts.

## Auf GitHub Pages veröffentlichen

1. Alle Dateien ins Repository laden (`index.html` im Wurzelverzeichnis).
2. Im Repository: Settings → Pages.
3. Unter "Build and deployment" als Source **Deploy from a branch** wählen,
   Branch `main` und Ordner `/ (root)`, dann Save.
4. Nach ein bis zwei Minuten ist die Seite unter
   `https://<benutzername>.github.io/<repository>/` erreichbar.

Nach einem Update einmal mit Strg+F5 neu laden, damit die neue Fassung
den zwischengespeicherten Stand ablöst. Die Kennung in `sw.js`
(`gebetstimer-v2`) wird bei künftigen Änderungen hochgezählt.
