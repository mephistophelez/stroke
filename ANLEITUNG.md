# Einfach-Tablet – als Web-App über GitHub Pages

## 1. Hochladen (einmalig, ca. 10 Minuten)
1. Auf github.com ein neues **öffentliches** Repository anlegen, z.B. `einfach-tablet`.
2. „Add file“ → „Upload files“ → alle Dateien aus diesem Ordner hineinziehen
   (index.html, manifest.webmanifest, sw.js, die drei PNG-Icons) → „Commit changes“.
3. Settings → Pages → Source: „Deploy from a branch“, Branch: `main`, Ordner: `/ (root)` → Save.
4. Nach 1–2 Minuten ist die App erreichbar unter `https://BENUTZERNAME.github.io/einfach-tablet/`.

## 2. Auf dem Tablet installieren
1. Die Adresse in **Chrome** öffnen.
2. Menü (⋮) → „Zum Startbildschirm hinzufügen“ bzw. „App installieren“.
3. Die App startet jetzt im Vollbild ohne Adressleiste und funktioniert auch ohne Internet.

## 3. Bildschirm anheften (Sperre)
1. Android-Einstellungen → Sicherheit (oder „Sicherheit & Datenschutz“ → „Weitere Einstellungen“)
   → **App-Anheftung** einschalten, dabei **„Vor dem Loslösen nach PIN fragen“** aktivieren.
2. Einfach-Tablet öffnen → Übersicht der offenen Apps (Quadrat-Taste oder von unten wischen und halten)
   → auf das App-Symbol oben tippen → **„Anheften“**.
3. Loslösen (nur für Angehörige): Zurück + Übersicht gleichzeitig gedrückt halten
   (bei Gestensteuerung: von unten nach oben wischen und halten) → PIN eingeben.

Die Bezeichnungen unterscheiden sich je nach Hersteller etwas (Samsung: „Apps anheften“).

## 4. Updates
Neue index.html auf GitHub hochladen und in `sw.js` die Zeile `VERSION = 'einfach-v1'` auf `v2` usw. erhöhen.
Das Tablet holt sich die neue Version beim nächsten Start mit Internet.
Kontakte, Bilder und Einstellungen bleiben dabei erhalten (sie liegen auf dem Tablet, nicht auf GitHub).
