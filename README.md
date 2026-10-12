# SEK Nordbayern Kaltschuss Logbuch – V11

Alle Dateien direkt ins Stammverzeichnis des GitHub-Repositorys hochladen.

V11: neue Kopfzeile mit Logo und dezenter Nürnberger Skyline, Home-Screen-Icons, manuelle Kameraaufnahme aus der Live-Vorschau, reparierter Export, Maßstabshinweis nur unter „Scheibe“, Wetterautomatik ohne Wind. Waffenverwaltung, IndexedDB, Import, Treffererkennung und ±20-m-Filter bleiben erhalten.

Hinweis: Die dauerhafte Kameraberechtigung wird von iOS/Safari verwaltet und kann von einer Web-App nicht erzwungen werden.


Korrektur: Das vom Nutzer bereitgestellte Originalabzeichen wird nun als Header-Logo und als Home-Bildschirm-/PWA-Icon verwendet. Die Kopfzeile enthält rechts eine dezente stilisierte Nürnberger Silhouette mit Kaiserburg.

V12: Munitionsauswahl direkt unter der Waffe im Reiter Erfassen. Bereits gespeicherte Munition wird waffenspezifisch vorgeschlagen; bestehende Einträge bleiben unverändert.


V12 Plus: Scheibenfilter für Waffe, Munition, Temperatur (±5 °C) und Entfernung (±20 m), mit gut sichtbarer Filterzusammenfassung. Windfeld beim Erfassen entfernt; bestehende historische Winddaten bleiben erhalten. Treffererkennung verwendet strengere Konfidenzbewertung und zeigt automatische Positionen ausdrücklich als zu prüfenden Vorschlag. Manuelle Korrektur bleibt möglich.


V13: Im Reiter Prognose gibt es nun den Button „Wetter automatisch vom aktuellen Standort“. Er fragt mit Standortfreigabe Open-Meteo ab und übernimmt Temperatur sowie Luftdruck in die Prognosefelder. Das bisherige Prognoseverfahren bleibt unverändert.


V14: Lokale statistische Prognose mit separater Waffenauswahl und passender Munitionsauswahl. Kein externer KI-Aufruf. Wetterabruf aus V13 bleibt unverändert. Benötigt mindestens drei historische Einträge mit derselben Waffe und Munition. Optionaler Entfernungsfilter ±20 m.


V15: Grafische Darstellung der lokalen statistischen Prognose auf derselben 10x10-cm-Kaltschussscheibe wie im Scheibenreiter. Blauer Marker = prognostizierter Gruppenmittelpunkt, gestrichelter blauer Kreis = gewichtete Streuung historischer Gruppenmittelpunkte (kein Konfidenzintervall). Bei weniger als drei Messungen keine Grafik. Änderungen an Prognosefiltern/Wetterfeldern verbergen eine veraltete Prognose bis zur Neuberechnung.
