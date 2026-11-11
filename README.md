# Hallo Welt PWA

Eine minimale, installierbare Progressive Web App mit Offline-Unterstützung.

## Lokal starten

Service Worker funktionieren nur über `localhost` oder HTTPS (nicht zuverlässig über `file://`).

Mit Python:

```bash
python -m http.server 8080
```

Dann im Browser öffnen: http://localhost:8080

Alternativ mit Node.js:

```bash
npx serve .
```

## Ausprobieren

1. Seite einmal online laden.
2. Browser-Entwicklertools öffnen und unter **Application** Manifest und Service Worker prüfen.
3. Seite neu laden und anschließend offline schalten – die App-Shell sollte weiter angezeigt werden.
4. Auf unterstützten Browsern erscheint die Installationsoption im Browsermenü bzw. als Installieren-Button.

Für den produktiven Einsatz die Dateien auf einem Host mit HTTPS bereitstellen.
