# Labo 2 - reflecties

Naam: Maysa Cheqrouni

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: Selecteert alle links (a) die binnen een lijstitem (li) van een ongeordende lijst (ul) in de navigatie (nav) van de header staan.
- b. `article > p`: Selecteert alle paragrafen die rechtstreeks binnen een article staan
- c. `.uren li:nth-child(3)`: Selecteert de lijstitems binnen .uren die het derde kind van hun ouder zijn
- d. `h2 ~ p`: Selecteert alle paragrafen die na een h2 staan en dezelfde ouder hebben.
- e. `.rassen li:first-child`: Selecteert alle lijstitems binnen .rassen die het eerst kind vna hun ouder zijn.

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |groen | herkomst |groen | juist |
| 2 |blauw|volgorde|blauw |juist |
| 3 |rood |specifiteit |rood |juist |
| 4 |rood | volgorde |rood |juist |
| 5 |rood|specifiteit |blauw |fout |
| 6 |blauw |specifiteit |blauw |juist |
| 7 |rood |herkomst |rood |juist |
| 8 |rood |herkomst |blauw |fout |
| 9 |blauw |specifiteit |rood |fout |
| 10 | blauw |volgorde |groen |fout |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
nav a: selecteert alle links binnen navigatie. geen class omdat de HTML al een nav-element bevat.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
de regel .kaart li:nth-child(odd) - ik begreep niet echt goed hoe het werkte

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
