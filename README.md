# Kaltschuss Logbuch – PWA

Diese Version basiert auf der vorhandenen HTML-App und ergänzt sie um die PWA-Schicht:
- installierbares App-Icon
- Standalone-Darstellung
- Offline-Cache per Service Worker
- lokale Datenhaltung wie bisher per localStorage
- Fotoaufnahme/-auswahl und manuelle Treffererfassung

## Auf dem iPhone
1. Die Dateien auf einen HTTPS-Webserver legen.
2. Die Adresse in Safari öffnen.
3. „Teilen“ → „Zum Home-Bildschirm“.
4. „Hinzufügen“ wählen und anschließend das neue Kaltschuss-Icon starten.

Wichtig: Eine PWA muss für die Installation über HTTPS ausgeliefert werden (localhost ist nur für Entwicklung ausreichend).

## Daten
Die Logbuchdaten bleiben im Browser-Speicher des jeweiligen Geräts. Es gibt in dieser Version keine automatische Cloud-Synchronisation zwischen Freunden.

## Treffererfassung
Die PWA arbeitet lokal/offline. Treffer werden direkt auf dem Scheibenfoto durch Tippen gesetzt und können korrigiert werden. Es wird bewusst keine externe KI-API mit Zugangsdaten in den Client eingebaut.

## Hinweis zur Prognose
Die Prognose ist auf neutrale Beschreibung von Trefferlage/Streuung und Zusammenhängen mit Wetterdaten beschränkt; konkrete Ziel- oder Haltepunktanweisungen sind nicht Bestandteil dieser Version.
