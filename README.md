# KI Studio

Moderne, responsive KI-Musikstudio-Webseite.

## Lokal starten
Einfach `index.html` im Browser öffnen. Für GitHub Pages:
1. Repository **Settings → Pages** öffnen.
2. **Deploy from a branch** auswählen.
3. Branch `main`, Ordner `/ (root)), dann **Save**.

## Funktionen
- Song-Generator-Oberfläche (Song, Instrumental, Songidee)
- Genre-, Stimmen- und Sprachauswahl
- Lyrics-Editor mit TXT-Export
- Browser-Drum-Pads und Beat-Loop (Web Audio)
- Mehrspur-Projektvorschau
- Projekte lokal speichern und wiederherstellen

## Echte KI-Generierung
Die Oberfläche löst aktuell noch keine KI-Generierung aus. Dafür muss ein Backend mit einem Song-/Gesangsgenerierungsdienst verbunden werden. API-Schlüssel gehören ausschließlich auf den Server und niemals in den Browser. Es werden keine kostenpflichtigen API-Aufrufe ausgelöst.

## Datenschutz
Projekte liegen aktuell nur im `localStorage` des verwendeten Browsers. Benutzerkonten und Cloud-Synchronisierung sind nicht enthalten.