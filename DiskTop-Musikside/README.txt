DISKTOP MUSIKSIDE — Pant og Ansvar
==================================

Dette er en statisk hjemmeside, der kan hostes gratis på GitHub Pages.
Den indeholder den uploadede MP3, en responsiv mørk lilla/blå side, afspiller,
downloadlink, individuel sangside (?song=pant-og-ansvar) og en formular til
lokal tilføjelse af MP3-numre.

VIGTIGT OM NYE SANGE
Den statiske demo gemmer numre, der tilføjes i formularen, i IndexedDB i den
browser, hvor de blev tilføjet. De bliver IKKE uploadet til internettet og er
ikke synlige for andre besøgende. Fælles offentlig upload kræver en backend,
login og et fil-lager. Den eksisterende Pant og Ansvar MP3 er offentlig del af
webprojektet, når projektet publiceres.

PUBLICERING GRATIS MED GITHUB PAGES
1. Opret/log ind på https://github.com/
2. Opret et nyt repository, fx disktop-musik.
3. Upload indholdet af denne mappe (index.html, style.css, app.js, songs/ og README.txt).
4. Gå til Settings → Pages.
5. Under Build and deployment vælg Deploy from a branch, branch main, folder /(root), og gem.
6. GitHub viser en offentlig adresse, normalt https://DIT-BRUGERNAVN.github.io/disktop-musik/.
7. Test både forsiden og sangsiden: adressen ovenfor og adressen med ?song=pant-og-ansvar.

QR-KODE OG URL
En QR-kode til den rigtige offentlige URL kan først laves, når GitHub Pages-adressen
findes. Brug den endelige URL til at lave QR-koden, så koden virker på telefoner.

NOTE
Google Fonts indlæses fra nettet; hvis de ikke kan hentes, bruger siden fallback-skrifttyper.
