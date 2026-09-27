ENGLISH VOCABULARY TRAINER – PWA

Dateien:
- index.html
- app.js
- manifest.webmanifest
- service-worker.js
- icon.svg

WICHTIG:
Eine installierbare PWA muss über HTTPS oder localhost geöffnet werden.
Nur die index.html direkt als Datei (file://) zu öffnen reicht für die
Android-Installation und den Service Worker nicht aus.

Android:
1. Den gesamten Ordner auf einen HTTPS-Webserver hochladen.
2. Die HTTPS-Adresse in Chrome öffnen.
3. "App installieren" bzw. "Zum Startbildschirm hinzufügen" wählen.

PC-Test:
Im Ordner einen lokalen Webserver starten, z.B.:
python -m http.server 8000
Dann http://localhost:8000 öffnen.

Die Vokabeln werden lokal im Browser/auf dem Gerät gespeichert.
