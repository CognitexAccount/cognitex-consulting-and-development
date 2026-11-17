# Cognitex – Website

Website der Cognitex GmbH: Wir begleiten Bildungsanbieter durch das KI-Zeitalter, mit Beratung zu KI in Lehre und Prüfung und mit der Entwicklung digitaler Prüf- und Bewertungslösungen.

## Aufbau

Statische Website ohne Build-Schritt: eine einzige `index.html` mit eingebettetem CSS und JavaScript.

```
index.html                     Alle Seiten, Styles und Skripte
assets/cognitex-logo-mark.png  Logo (Kopf-Symbol), auch als Favicon
assets/simon-roesgen.jpg       Foto Über uns
assets/pruefungssimulation.jpg Screenshots der Prüfungssimulation
```

Die Unterseiten (Start, Leistungen, Beratung, Entwicklung, Über uns, Kontakt, Impressum) liegen als Abschnitte in `index.html` und werden über den Anker in der URL umgeschaltet, z. B. `/#beratung`.

## Lokal ansehen

`index.html` im Browser öffnen, oder:

```
npx serve .
```

## Konfiguration

- **Terminbuchung:** HubSpot-Link `https://meetings-eu1.hubspot.com/simon-roesgen` (alle „Termin buchen"-Buttons)
- **E-Mail:** `kontakt@cognitex.de`
- **Datenschutz:** verlinkt aktuell auf `https://cognitex.de/datenschutz`

## Offene Punkte

- Kontaktformular versendet noch nicht (Prototyp). Für den Livebetrieb einen Formular-Dienst anbinden (z. B. HubSpot Forms, Formspree) oder das Formular entfernen.
- Datenschutzerklärung als eigene Seite übernehmen.
- Impressum prüfen: „§ 5 TMG" ist seit Mai 2024 durch § 5 DDG ersetzt; die angegebene „Umsatzsteuer-ID" hat das Format einer Steuernummer.
