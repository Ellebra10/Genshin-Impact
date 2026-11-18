# Teyvat-Kompass

Private Übersicht für Genshin Impact (Spieldaten 7.2): Charaktere, Waffen, Artefakte, Guides, Team-Ideen, Farm-Liste, Wish-Planer.

## Auf GitHub Pages veröffentlichen
1. Alle Dateien aus diesem Ordner ins Repository legen (index.html muss ganz oben liegen).
2. Im Repository: Settings -> Pages -> Branch `main`, Ordner `/ (root)` -> Save.
3. Nach etwa einer Minute läuft die Seite unter `https://<dein-name>.github.io/<repo-name>/`.

## Deine Account-Daten
- Im Repository liegen **keine** persönlichen Daten: nur Spieldaten (`data.json`, `guides.json`) und die Seite.
- Deine Daten speichert die Seite nur im Browser des Geräts (localStorage). Wer die Seite öffnet, sieht eine leere Seite, nicht deinen Account.
- Daten holen: Teyvat-Kompass in Claude -> Daten laden -> "Daten kopieren". Dann hier -> Daten laden -> einfügen -> "Übernehmen". Vitrine-Text und Scanner-Datei (GOOD) gehen hier auch.
- Lade niemals eine Sicherung deiner Daten oder `genshin-hoyolab.json` ins Repository hoch.
- Browserdaten löschen entfernt auch die Kompass-Daten. Vorher "Sicherung kopieren".

## Was hier nicht geht
- Der Knopf "Aktualisieren" (braucht die Claude-App).

## Bilder
Das Symbol der Seite (Browser-Tab, gespeicherte Verknüpfung, App) liegt in `icons/`, `favicon.ico` und `manifest.webmanifest`.
Charaktere, Waffen und Artefakte zeigen automatisch die Spiel-Icons (von enka.network, Ersatzquelle gi.yatta.moe). Die Dateinamen stehen fest in `index.html`; für neue Charaktere oder Waffen dort `ICON_C` bzw. `ICON_W` ergänzen.

## Eigene Bilder
Bilder kannst du in der Seite hochladen oder auf einen Charakter ziehen. Sie werden verkleinert und nur in deinem Browser gespeichert, nicht im Repository.

## Lokal testen
Im Ordner `python -m http.server` starten und `http://localhost:8000` öffnen. Ein Doppelklick auf index.html reicht nicht, weil die Seite `data.json` nachlädt.
