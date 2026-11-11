# Kompas online zetten en installeren

Kompas is een installeerbare web-app. Hij moet op een https-adres staan voor je hem op je gsm kunt installeren.

## Online zetten met GitHub Pages (gratis)

1. Maak op github.com een nieuwe repository, bijvoorbeeld `kompas`.
2. Upload alle bestanden uit deze map (Add file → Upload files), behalve dit leesmij-bestand als je dat niet wilt.
3. Ga naar Settings → Pages, kies bij Branch `main` en map `/ (root)`, en bewaar.
4. Na een minuut staat de app op `https://<jouw-gebruikersnaam>.github.io/kompas/`.

Netlify of Vercel werken ook: sleep de map in hun uploadscherm.

## Installeren op je gsm

- iPhone: open het adres in Safari, tik op Deel en kies "Zet op beginscherm".
- Android: open het adres in Chrome, tik op het menu met de drie puntjes en kies "App installeren".

## Goed om te weten

- Alles wat je invult (klanten, notities, cases) blijft op je toestel en staat niet in deze bestanden. Maak back-ups via Meer → Back-up.
- Het adres zelf is publiek. Zet dus geen klantgegevens in de code.
- Bij een nieuwe versie: vervang de bestanden en verhoog `VERSION` in `sw.js`.
