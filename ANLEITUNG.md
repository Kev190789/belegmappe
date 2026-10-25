# Belegmappe – auf GitHub Pages stellen und aufs Handy installieren

## 1. Repository anlegen (einmalig)
1. Auf github.com anmelden → oben rechts **+** → **New repository**.
2. Name: `belegmappe`, Sichtbarkeit **Public** (für kostenloses GitHub Pages nötig. Öffentlich ist nur der App-Code, deine Belege nie, die bleiben auf dem Handy).
3. **Create repository**.

## 2. Dateien hochladen
1. Im neuen Repository auf **uploading an existing file** klicken.
2. Diese Dateien aus dem Ordner `belegmappe-app` hineinziehen:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`
3. Unten **Commit changes**.

## 3. GitHub Pages einschalten
1. Im Repository **Settings** → links **Pages**.
2. Bei *Source*: **Deploy from a branch**, Branch **main**, Ordner **/ (root)** → **Save**.
3. Nach 1–2 Minuten steht oben die Adresse, z. B. `https://DEINNAME.github.io/belegmappe/`.

## 4. Auf dem Android-Handy installieren
1. Die Adresse in **Chrome** öffnen.
2. Oben auf **App installieren** tippen (oder Chrome-Menü ⋮ → **App installieren** / **Zum Startbildschirm hinzufügen**).
3. Fertig: „Belegmappe“ liegt als App auf dem Startbildschirm und funktioniert auch offline.

## Bedienung
- **Foto**: Rechnung fotografieren. Jedes Foto wird gespeichert, auch wenn du die App schließt.
- **Galerie**: vorhandene Fotos auswählen.
- **PDF erstellen** → **Teilen** (Mail, WhatsApp, Outlook …) oder **Speichern** (Ordner „Downloads“).
- **Neue Abrechnung beginnen** löscht alle Belege für den nächsten Monat.

## Später etwas ändern
Geänderte Dateien im Repository erneut hochladen. Wenn `sw.js` geändert wurde, darin `VERSION` hochzählen (z. B. `belegmappe-v2`), damit das Handy die neue Version holt. Die App zweimal öffnen, dann ist das Update da.
