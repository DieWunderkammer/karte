# Wunderkammer – Schulen-Tracking Karte

Live unter: **https://diewunderkammer.github.io/karte/**

Interaktive Karte aller Schulen, die für *Die Wunderkammer der Lehrmittel* kontaktiert wurden. Pins sind farbcodiert nach Status (grün = Material abgeholt, gelb = offen, grau = kein Material, rot = Absage). Beim Klick auf einen Pin erscheint eine Infobox mit Kontaktdaten und einem „Navi starten"-Button, der Google/Apple Maps mit der Schule als Ziel öffnet.

## Technik

Statische HTML-Seite mit [Leaflet](https://leafletjs.com/) und [OpenStreetMap](https://www.openstreetmap.org/) Tiles. Keine Abhängigkeiten, kein API-Key, kein Tracking.

## Update-Workflow

Die Daten in `index.html` werden automatisch aus der Master-Excel regeneriert, sobald neue Schulantworten in Gmail eintreffen.
