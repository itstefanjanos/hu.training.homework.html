# HTML/CSS házi feladat

* [x] Hozz létre Eclipse-ben egy új Static Web Project-et, amiben megcsinálod a 
feladatot.
* [x] A CSS külön fájlban kapjon helyet, és hivatkozd be.

`<link rel="stylesheet" type="text/css" href="valami.css">`

# Feladat:

* [x] Készíts egy weboldalt a kedvenc ételedről. 
* [x] Az oldal tartalmazza az oldal tetején az étel nevét,
* [x] alatta egy táblázatban a hozzávalókat,
* [x] majd az alatt egy paragrafusban az étel receptjét. 

# Elvárások:

* [x] Az oldalnak állíts be egy címet, ami megjelenik a böngésző fejlécébe. (head - title)
* [x] Az oldalnak legyen háttérszíne.
* [x] Cseréld le a betűtípust a dokumentumon belül, ha szükséges a betű színét is (a háttérszín miatt).
* [x] Az oldalon a tartalom egy 70% széles blokkban kapjon helyet, aminek eltérő a háttérszíne. A blokknak adj padding-ot.
* [x] A címhez használj valamilyen címsort (heading-et).
* [x] A cím alatt szerepeljen egy rövid leírás az életről.
* [x] A leírás alatt szerepeljen egy kép az ételről, aminek változtasd meg a méretét, illetve adj keretet (border).
* [x] A kép alatt szerepeljen egy táblázat, aminek az egyik oszlopában a hozzávalók nevét, a másikban a szükséges mennyiség szerepeljen.
* [x] Legyen fejrésze (head) a táblázatnak.
* [x] A táblázat minden páratlan sorát színezd át másik színűre. Ehhez használd az odd pszeudo szelektor: `table tr:nth-child(odd)`
* [x] A táblazat alatt pedig egy fieldset html elemben szerepeljen az elkészítési mód. A címe (legend) legyen: Elkészítés
* [x] Az egymás alatt szereplő elemek (cím, kép, táblázat) között használj térköz (margin).
* [x] Írj egy javascript függvényt `<script>` tag-ek között, amivel kiírod a console-ra (`console.log()`) a címnek (heading) megadott értéket (innerHtml). Ez script az oldal aljára (elkészítés fieldset alá) tett gomb megnyomására fusson le (onclick).
         pl. `<button onclick="logTitle()">Cím kiírása</button>`

# Megjegyzés:
A formázásokat minden esetben CSS segítségével végezd. 
Nem kell túl bonyolítani a formázásokat, a fenti leírásnak feleljenek meg.

Jó munkát!