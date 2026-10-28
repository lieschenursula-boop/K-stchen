# Das Kästchen

Eine kleine App zum Antippen, als installierbare Web-App für Android.

## So kommt die App auf dein Handy

{Erkl.: **GitHub Pages** ist ein kostenloser Dienst von GitHub, der Webseiten aus einem Projektordner ins Internet stellt. Eine **PWA** (Web-App) ist eine Webseite, die Android wie eine richtige App aufs Startbild legt und die auch ohne Internet läuft.}

1. Auf github.com ein neues Repository anlegen, zum Beispiel `kaestchen` (öffentlich).
2. Alle Dateien aus diesem Ordner hochladen: `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` und den Ordner `icons`. Das geht über „Add file → Upload files“, oder mit Git.
3. Im Repository: **Settings → Pages**. Bei „Source“ **Deploy from a branch** wählen, Branch `main`, Ordner `/ (root)`, speichern.
4. Nach ein bis zwei Minuten steht die Adresse da: `https://DEIN-NAME.github.io/kaestchen/`
5. Diese Adresse in **Chrome auf dem Android-Handy** öffnen. Dann Menü (drei Punkte) → **App installieren** (manchmal: „Zum Startbildschirm hinzufügen“).

Danach hat die App ein eigenes Symbol, startet ohne Adressleiste und läuft auch ohne Internet.

## Spielstand

Der Spielstand liegt auf dem Gerät, das gerade spielt. Unter „Mehr“ gibt es „Als Text zeigen“ und „Aus Text laden“, damit lässt sich der Stand auf ein anderes Gerät mitnehmen oder sichern.

## Neue Version veröffentlichen

Dateien im Repository ersetzen und in `sw.js` die Zahl bei `CACHE` erhöhen (`kaestchen-v2`). Beim übernächsten Start laden die Geräte die neue Version.
