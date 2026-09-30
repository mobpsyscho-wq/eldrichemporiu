# Eldrich Emporium

Statische Shop-Startseite (HTML, CSS, JS). Kein Build nötig.

## Struktur
- index.html – Seite
- css/style.css – Design und Animationen
- js/app.js – Filter, Demo-Warenkorb, W20, Mimic, Effekte
- images/ – Logo und Drachenbild
- _headers – Cloudflare (Caching, Sicherheit)

## Auf GitHub
1. Neues Repository anlegen (github.com > New).
2. "Add file > Upload files": alle Dateien und Ordner hochladen (index.html muss im Hauptordner liegen, nicht in einem Unterordner).
3. Commit.

## Auf Cloudflare Pages
1. Cloudflare Dashboard > Workers & Pages > Create application > Pages > Connect to Git.
2. GitHub verbinden, Repository wählen.
3. Build command: leer lassen. Build output directory: leer lassen. Root directory: leer lassen.
4. Deploy. Danach ist die Seite unter <projekt>.pages.dev erreichbar. Jede Änderung auf GitHub wird automatisch neu veröffentlicht.
5. Eigene Domain: Projekt > Custom domains.

## Wichtig
- Das ist ein Design-Prototyp. Der Warenkorb ist eine Demo, die Kasse zahlt nichts. Für echten Verkauf: Shopify-Paket nutzen oder einen Bezahldienst anbinden.
- Schriften laden noch von Google Fonts. Für Deutschland besser selbst hosten (Dateien in fonts/ ablegen, @font-face in css/style.css).
- Bildrechte prüfen (Drachenbild enthält Pikachu, Pokéball, Magic-Symbol).
- Impressum, Datenschutz, AGB, Widerruf ergänzen lassen.
