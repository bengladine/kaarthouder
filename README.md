# Kaartjes – klantenkaarten PWA

Statische webapp, geen server nodig. Alle kaarten blijven lokaal op je telefoon (IndexedDB).

## Online zetten (GitHub Pages)
1. Nieuwe repo, bv. `kaarthouder`, en upload alle bestanden uit deze map.
2. Settings → Pages → Branch `main`, map `/ (root)` → Save.
3. Open `https://<gebruiker>.github.io/kaarthouder/` in Chrome op je telefoon.
4. Menu ⋮ → "Toevoegen aan startscherm" / "App installeren".

Na installatie werkt de app offline. De app staat ook in het Android-deelmenu:
deel een screenshot naar "Kaartjes" en de kaart wordt meteen toegevoegd.

## Updaten
Pas `VERSION` in `sw.js` aan (bv. `kaartjes-v2`) bij elke wijziging, anders blijft de oude versie in de cache.

## Back-up
Menu ⋮ → Back-up exporteren. Doe dit af en toe: wis je de browsergegevens of wissel je van telefoon, dan zijn de kaarten weg.
