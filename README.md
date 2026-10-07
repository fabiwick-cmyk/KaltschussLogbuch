# Kaltschuss Logbuch V8 – IndexedDB

Statische iPhone-/PWA-Web-App für das Kaltschuss-Logbuch.

## Speicherung
- Einträge und Scheibenfotos werden in **IndexedDB** im Browser gespeichert.
- Beim ersten Start werden vorhandene Daten aus der früheren `localStorage`-Version `kaltschuss_v4` einmalig übernommen.
- Danach arbeitet die App nicht mehr mit `localStorage` für die Einträge.
- Die Daten bleiben an Browser/Gerät und Origin der App gebunden.

## GitHub Pages
1. Alle Dateien dieses Ordners in das Repository hochladen.
2. GitHub Pages auf Branch `main` und Ordner `/(root)` stellen.
3. Nach der Veröffentlichung die Seite öffnen.

## Dateien
- `index.html` – komplette App
- `.nojekyll` – verhindert Jekyll-Verarbeitung
- `README.md` – diese Anleitung
