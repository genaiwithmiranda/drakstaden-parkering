# Drakstadens Parkering – konceptförslag

Förslag på ny webbplats för Drakstadens Parkering AB i Sundsvall, framtaget av Konstig.

Hela sidan ligger i en fil, `index.html`, och fungerar i både webbläsare och mobil. Öppna filen direkt i en webbläsare, eller starta en enkel server:

```bash
python3 -m http.server 4173
```

## Innehåll

- Hero med parkeringen som meny
- Parkera i Sundsvall: korttid, långtid, motorvärmare och karta över parkeringarna
- För markägare: skyltning, bevakning, betalning
- Fått en kontrollavgift: före eller efter 1 oktober 2026
- Kontakt med formulär

## Att göra innan publicering

- Kontaktformuläret skickar inga mejl ännu, det visar bara bekräftelsen. Koppla det till en tjänst som tar emot meddelandet och mejlar det vidare (t.ex. Formspree eller webbhotellets formulärtjänst) och fyll i adressen i `FORM_URL` i `index.html`.
- Logga, foton och appikoner hämtas i dag från drakstadensparkering.se. Lägg dem som lokala filer.
- Kontaktbilden kommer från Unsplash (Martin Edholm).
- Bankgironummer, datum och texten om nollavtal ska bekräftas av kunden.
- Parkering 8 saknar adress.
- "Om oss" länkar till kundens nuvarande sajt.
- Kartan bygger på data från OpenStreetMap och ska behålla "© OpenStreetMap".
