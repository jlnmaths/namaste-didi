# Namaste Didi – Rekonstruktion mit Originaltexten

Die drei HTML-Seiten enthalten die im Internet Archive sichtbaren Texte der früheren Website **im Originalwortlaut**, einschließlich der damaligen Schreibweisen, Daten und Angaben. Die Fotos und das Logo stammen aus den vom Nutzer bereitgestellten Originaldateien. Das Layout ist neu gestaltet; es ist keine pixelgenaue Reproduktion des früheren Webdesigns.

Die früher vorhandene Seite **Impressionen** ist entfernt; es gibt weder die HTML-Datei noch Navigationseinträge dorthin. Einige Fotos werden in die verbliebenen drei Seiten eingebunden.

## Seiten

- `index.html` – Home
- `projekte.html` – Spenden
- `wir.html` – Über Uns
- `styles.css` – CSS-Design
- `assets/` – Vereinslogo und bereitgestellte Fotos; WebP-Kopien zur schnelleren Auslieferung

## Vorschau

Öffnen Sie `index.html` im Browser. Alternativ kann der Ordner lokal z. B. mit `python3 -m http.server 8000` angeboten werden.

## Veröffentlichung auf GitHub Pages

1. Ein öffentliches GitHub-Repository erstellen und die Dateien und die Ordner `assets` und `dokumente` in dessen Stammverzeichnis hochladen.
2. In `Settings → Pages` die Veröffentlichung aus dem Branch `main`, Verzeichnis `/ (root)`, einstellen.
3. Unter `Settings → Pages → Custom domain` `namaste-didi.de` eintragen, **wenn Sie die Domain kontrollieren**.
4. Beim Registrar vier A-Einträge für `@` auf die IP-Adressen `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` setzen. Für `www` optional einen CNAME auf `GITHUBBENUTZERNAME.github.io` setzen. Nicht die E-Mail-Einträge MX, SPF, DKIM und DMARC entfernen.
5. `Enforce HTTPS` einschalten, sobald die GitHub-Zertifizierung abgeschlossen ist.

## Wichtig vor einer öffentlichen Veröffentlichung

- Die Texte stammen überwiegend aus 2024. Der Veranstaltungstermin 2022, die Vereinsrollen, Beiträge, Projektangaben und Spendeninformationen wurden *absichtlich nicht aktualisiert*, weil der Auftrag Originalwortlaut lautet.
- Die historische IBAN und die E-Mail-Adresse stehen deshalb wie im Original im Fußbereich. **Zuerst prüfen, ob die Angaben noch gültig sind.** Die PayPal-Schaltflächen sind ausdrücklich nicht verlinkt, weil die aktuelle Zahlungsadresse ungeprüft ist.
- Das Impressum stammt aus der vom Nutzer hochgeladenen älteren Word-Datei; die Datenschutzrichtlinien und Vereinssatzung sind lokal herunterladbar. Rechtsdokumente vor einer Neuveröffentlichung auf Aktualität und geltende Anforderungen prüfen.
- Die Seite verwendet Fotos mit Kindern. Bitte prüfen, ob erforderliche Veröffentlichungsrechte und Einwilligungen auch für die erneute Veröffentlichung vorliegen.
- Auf der Seite »Spenden« steht der Originalsatz »Links im Bild ist unsere Nepalkorrespondentin Sahin Pravin.« Das originale dazugehörige Foto konnte nicht sicher identifiziert werden. **Das daneben abgebildete Nähfoto darf daher nicht als Foto von Sahin Pravin interpretiert werden.** Ggf. das richtige Foto ergänzen oder nach Freigabe den Satz anpassen.

## Archivquellen

- [Home, 6. Dezember 2024](https://web.archive.org/web/20241206223732/https://namaste-didi.de/)
- [Spenden, 14. Juni 2024](https://web.archive.org/web/20240614101442/https://namaste-didi.de/projekte.html)
- [Über Uns, 12. August 2024](https://web.archive.org/web/20240812105130/https://namaste-didi.de/wir.html)

## Downloads im Footer

Alle fünf bereitgestellten Originaldokumente liegen **direkt im Ordner `dokumente/`** und sind von allen drei Seiten über den Footer herunterladbar:

- `dokumente/Flyer.pdf`
- `dokumente/Mitgliedsantrag.pdf`
- `dokumente/Impressum-Namaste-Didi.docx` (das Original-Impressum wurde als Word-Datei hochgeladen; die Dateiendung wurde nicht verändert)

- `dokumente/Datenschutzrichtlinien.pdf` – die vom Nutzer hochgeladene Datenschutzerklärung
- `dokumente/Vereinssatzung.docx` – die vom Nutzer hochgeladene Satzung

Die Dokumente wurden unverändert eingebunden, nicht rechtlich oder redaktionell aktualisiert. Der gelbe Hinweisstreifen „Archivfassung der ursprünglichen Website (2024)“ ist auf allen Seiten entfernt.

Die Zeile unter der unteren horizontalen Trennlinie im Footer wurde auf allen drei Seiten entfernt.

**Vor Veröffentlichung:** Prüfen Sie, ob die hochgeladenen Formulare/Anschriften, Rechtsdokumente, Kontoinformationen und die wiederverwendeten Bilder in der veröffentlichten Version noch gültig sind. Die Datenschutzinformationen auf Seite 2 des Mitgliedsantrags ersetzen nicht automatisch die Datenschutzrichtlinien für die Website.
