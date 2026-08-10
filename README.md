# Flare for Pilots – Website

Support-, Datenschutz- und Impressumsseite der iOS-App **Flare for Pilots**.

Reines HTML und CSS, keine Abhängigkeiten, kein Build-Schritt. Die Seiten passen sich
automatisch dem hellen und dunklen Modus an.

| Datei | Zweck | Wofür Apple die URL braucht |
|---|---|---|
| `index.html` | Startseite mit Support-Kontakt und FAQ | **Support URL** in App Store Connect |
| `datenschutz.html` | Datenschutzerklärung nach DSGVO | **Privacy Policy URL** in App Store Connect |
| `impressum.html` | Impressum nach § 5 DDG | gesetzlich vorgeschrieben |
| `style.css` | gemeinsame Gestaltung | – |

## Änderungen

Die Dateien sind die Kopie aus `Flare/docs/` im App-Projekt. Wird dort etwas geändert,
muss es hier nachgezogen werden – und umgekehrt. Der Text der Datenschutzerklärung ist
inhaltlich identisch mit `PrivacyView` in `Flare/Legal.swift`; weichen die beiden
voneinander ab, ist das ein Fehler.

## Veröffentlichen

Über GitHub Pages: Repository-Einstellungen → *Pages* → Source *Deploy from a branch* →
Branch `main`, Ordner `/ (root)`. Nach ein bis zwei Minuten ist die Seite unter
`https://<benutzername>.github.io/<repository>/` erreichbar.
