# Reinbouw & Glas go-live

Go-live-pagina voor de Meta-campagne van Reinbouw & Glas (video's, statische ads en teksten).
Statische site zonder build-stap; Vercel serveert `index.html` vanuit de root. Zelfde opzet als Golive-malermo.

## Stand (11-11-2026)
Opzet, huisstijl (logo en kleuren van Reinbouw & Glas) en placeholders staan. De inhoud volgt nog van GrowGuide:

- [x] video 1 (Nieuw dubbel glas?, 19,6 s) in 9:16, 1:1 en 1,91:1; afspelen via video/video1-9x16.mp4 (720p), originelen in files/
- [x] video 2 (Glas, houtrot en kitwerk, 19,2 s, versie 2 sinds 12-11) in 9:16, 1:1 en 1,91:1
- [x] video 3 (Kan jouw kozijn nog blijven?, 18,8 s) in 9:16, 1:1 en 1,91:1
- [ ] per video: titel, lengte, omschrijving, tekst in beeld met tijden
- [x] statische ad 1 (Glasvervanging) in 1:1, 9:16 en 1,91:1
- [x] statische ad 2 (Houtrot- en kozijnherstel) in 1:1, 9:16 en 1,91:1
- [x] statische ad 3 (Wat kost nieuw glas?) in 1:1, 9:16 en 1,91:1 → PNG's in `files/`, webp-voorbeelden in `img/`
- [ ] per statische ad: titel, citaat, product
- [x] tekst 1 en 2 voor de video's (primaire tekst, kop, beschrijving; voor alle video's)
- [ ] tekst 3 voor de video's
- [x] per statische ad 3 eigen teksten (invalshoek, primaire tekst, kop, beschrijving)
- [ ] beschrijving en knop bij de video's; knop bij de statische ads (bestemming = formulier in Meta, geen landingspagina)
- [ ] status "Wacht op bestanden" → "Klaar om live te gaan", "Nog aan te leveren" → "Alles is binnen"

Alle placeholders staan in `index.html` met een `<!-- PLACEHOLDER ... -->`-commentaar erboven en de classes
`missing`, `wait` of `pending`. Kopieerknoppen staan op `disabled` tot de tekst er is.

Opgesteld door GrowGuide.
