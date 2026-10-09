# DayFlow Web-App

Mobile-first Progressive Web App für Tagesplanung, Aufgaben, Kalendertermine und Rennrad-/Lauftraining.

## Lokal testen
Öffne `index.html` in einem Browser. Für Offline-Funktion und „Zum Home-Bildschirm“ muss die App über HTTPS bereitgestellt werden; Service Worker funktionieren nicht bei jeder lokalen Datei-URL.

## Auf dem iPhone installieren
1. Stelle die Dateien auf einer HTTPS-Adresse bereit (z. B. GitHub Pages oder ein Static-Hosting-Anbieter).
2. Öffne die Adresse in Safari.
3. Tippe auf „Teilen“ → „Zum Home-Bildschirm“ → „Hinzufügen“.

## Daten
Einträge werden in `localStorage` des Browsers gespeichert. Sie werden nicht synchronisiert oder in einer Cloud gesichert. Website-Daten löschen kann Einträge entfernen. Export/Import ist in dieser ersten Version noch nicht enthalten.
