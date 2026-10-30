# Tellerblick

Mahlzeit fotografieren, Kalorien und Makros schätzen lassen, Komponenten anpassen und ein Tagebuch führen. Die App läuft komplett im Browser und lässt sich auf dem Handy installieren.

## Auf GitHub Pages veröffentlichen

1. Neues Repository anlegen und alle Dateien dieses Ordners hochladen (`index.html`, `shim.js`, `sw.js`, `manifest.webmanifest`, Ordner `icons`).
2. Im Repository unter **Settings → Pages** bei „Branch“ `main` und den Ordner `/ (root)` wählen und speichern.
3. Nach ein bis zwei Minuten ist die App unter `https://DEIN-NAME.github.io/REPO-NAME/` erreichbar.

## Auf dem Handy installieren

- **iPhone (Safari):** Teilen-Symbol → „Zum Home-Bildschirm“.
- **Android (Chrome):** Menü → „App installieren“ oder „Zum Startbildschirm hinzufügen“.

## Ohne KI rechnen

Die App enthält eine Liste häufiger Lebensmittel mit groben Richtwerten. Unter „Erfassen“ kannst du Text wie „4 Scheiben Vollkornbrot, 40 g Camembert, 1 Banane“ eintragen und auf „Kalorien schätzen“ tippen. Bei von Hand angelegten Zeilen füllt die App Gramm und Nährwerte aus, sobald du einen Namen wie „Skyr“ eingibst. Was nicht in der Liste steht, trägst du selbst ein.

## Foto-Erkennung

**Kostenlos über den Claude-Chat (ohne Schlüssel):** Unter „Erfassen“ öffnest du „Foto im Claude-Chat auswerten“, kopierst die Anweisung, schickst sie zusammen mit deinem Foto in der Claude-App oder bei claude.ai an Claude und fügst die Antwort wieder in die App ein. Danach kannst du jede Komponente anpassen.

**Direkt in der App (optional, kostet API-Guthaben):** Unter **Optionen** lässt sich ein Anthropic-API-Schlüssel eintragen (console.anthropic.com, Bereich API Keys, am besten mit Ausgabenlimit). Dann startet die Erkennung direkt nach dem Foto. Der Schlüssel liegt nur im Browser (localStorage) und wird nur an api.anthropic.com gesendet.

## Daten

Unter **Export** gibt es JSON und CSV (Tage, Mahlzeiten, Komponenten mit Gramm, kcal, Eiweiß, Kohlenhydraten, Fett). Fotos sind nicht enthalten. Sichere die Daten regelmäßig, denn sie liegen nur im Browser dieses Geräts.
