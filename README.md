# Kaltschuss Logbuch – PWA

## Installation auf dem iPhone
1. Lade den kompletten Inhalt dieses Ordners auf einen HTTPS-Webhost hoch. Die Dateien `index.html`, `manifest.webmanifest`, `service-worker.js` und der Ordner `icons` müssen zusammen im selben Verzeichnis liegen.
2. Öffne die HTTPS-Adresse in Safari.
3. Tippe auf „Teilen“ → „Zum Home-Bildschirm“ → „Hinzufügen“.

## Speicherung und Backups
- Einträge und Bilder werden lokal in IndexedDB auf diesem Gerät gespeichert.
- Bestehende Daten aus `localStorage` (`kaltschuss_v4`) werden beim ersten Start nach Möglichkeit automatisch übernommen.
- Unter „Einträge“ → „Datenverwaltung“ kannst du ein JSON-Backup exportieren und später wieder importieren.
- Beim Import kannst du die aktuellen Einträge ersetzen oder importierte Einträge hinzufügen.
- Backups enthalten auch die Bilder. Bewahre sie an einem sicheren Ort auf.

Hinweis: Lokale Browserdaten sind kein Ersatz für regelmäßige Backups. Verwende die PWA möglichst immer unter derselben HTTPS-Adresse und im selben Browserprofil.
