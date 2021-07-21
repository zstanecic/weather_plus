# Počasie Plus #

* Autor: Adriano Barbieri
* NVDA compatibility: 2017.3 to beyond
* Stiahnuť: [Stabilnú verziu] [1]

# O doplnku #

* This plugin adds local temperature and forecasts to 24 hours up to 2
  additional days and hourlyforecast for NVDA.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Vydané pod licenciou GNU GPL (General Public License) verzia 2
* Doplnok využíva tieto služby:
* [https://www.weatherapi.com/](https://www.weatherapi.com/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# POUŽITIE: #

* nvda+W: Oznámi informáciu o aktuálnom počasí.
* Press NVDA+shift+W to get 24 hours forecast and forecast up to 2 days.
* Press NVDA+shift+W twice to get hourlyforecast of temperature and
  atmospheric conditions.
* NVDA + shift + ctrl + w: Umožňuje nastaviť dočasné mesto.
* NVDA + shift + ctrl + alt + w: Otvorí nastavenia doplnku.
* NVDA + alt + w: Oznámi dátum a čas poslednej aktualizácie informácií o
  počasí.
* ctrl+ shift + w: prepína medzi oznamovaním teploty v stupňoch Celsia alebo
  Farenheita.

# Nastavenia: #

* You must set the Weather Plus addon before its first use! Go to the Preferences submenu, Weather Plus Settings submenu and choose one of the following options:
 * Set and Manage Your Cities... - Displays or allows to set the current city from a list.
 * Set a temporary city... - Displays and allows to set one temporary city from a list if available.
 * Documentation - Opens the help file for the current language.
 * Check for Update... - Notifies about the availability of the new version.

Nové mesto na sledovanie pridáte nasledovne:

* Aktivujte položku Spravovať mestá.
* Zobrazí sa táto správa: Predvolené mesto nie je. f1: Pomocník, f2: Oznámy
  aktuálne vybratú záložku, f3: presunie kurzor na editačné pole alebo
  zoznam, f4: Nastaví dĺžku predpovede počasia, F5: Nastavenie úrovne
  hlasitosti.
* In the edit box, enter a City or choose one from the list, if
  available. Note: The F5 key is available if the sound effects are
  activated.
* Po aktivovaní položky spravovať mestá sú dostupné tieto možnosti:
* Test - Test the validity of the city and find the data of it.
* Pridať: pridá aktuálne mesto do zoznamu. Toto tlačidlo sa dá aktivovať, ak
  je vybraté mesto zo zoznamu, a ak ste zadané mesto otestovali.
* Podrobnosti: zobrazuje informácie o aktuálnom meste. Toto tlačidlo sa dá
  aktivovať, ak je zo zoznamu vybraté mesto alebo ak ste ho už otestovali.
* Nastavenie zvukových efektov: Umožňuje definovať oblasť s cieľom
  prispôsobiť zvukové efekty. Toto tlačidlo sa dá aktivovať, ak sú zvukové
  efekty nainštalované a aktivované a ak je zo zoznamu vybraté mesto.
* Predvolené mesto: Ak nastavíte mesto ako predvolené, použije sa pri každom
  reštarte doplnku. Toto tlačidlo sa dá aktivovať, keď vyberiete mesto,
  ktoré bolo predtým vložené do zoznamu a nie je zatiaľ predvolené alebo ak
  prešlo testovaním.
* Odstrániť: Odstráni aktuálne mesto zo zoznamu. Toto tlačidlo sa dá
  aktivovať, ak vyberiete mesto, ktoré bolo predtým vložené do zoznamu.
* Premenovať: Premenuje aktuálne mesto. Toto tlačidlo sa dá aktivovať, ak
  vyberiete mesto, ktoré bolo predtým vložené do zoznamu.
* Importovať: Toto tlačidlo umožňuje importovať mestá z iného zoznamu miest
  s príponou * .zipcodes. Počas importu môžete začiarknuť mestá, ktoré
  chcete importovať.
* Exportovať: Umožňuje vám uložiť mestá do súboru s príponou *
  .zipcodes. Exportovať môžete len vtedy, ak je v zozname aspoň jedno mesto.
* hourly forecast setting... - This button allows you to choose the contents
  of the hourly forecast report.
* Jednotky merania teploty: Pomocou prepínača vyberte medzi stupňami Celzia
  (predvolené), Fahrenheita alebo Kelvina.
* Zobraziť stupne ako: Pomocou prepínača vyberte medzi Celzia `-`
  Fahrenheita `-` Kelvina (redvolené) C` -` F `-` K alebo neurčovať.
* Combo box: Weather Forecasts up to days: 1; you can choose between 1 to 3
  (1 days by default)
* Combo box: API response language: English, en; you can choose the language
  of the weather conditions text.
* Dostupné sú aj tieto začiarkávacie polia:
* kopírovať predpoveď počasia, aktuálne počasie a informácie o meste do
  schránky - predvolene vypnáté
* Predpoveď oznamovať aj Zvukom: Po začiarknutí môžete spravovať zvukové
  efekty. Ak sú nainštalované zvukové efekty a pole je začiarknuté, môžete
  upravovať hlasitosť zvukov klávesom F5.
* Pribudne tiež začiarkávacie políčko Neprehrávať zvuky Prostredia.
* Môžete zmeniť celkovú úroveň hlasitosti, prípadne upraviť hlasitosť pre
  jednotlivé udalosti. Predvolene nie je začiarknuté.
* Neprehrávať zvuky Prostredia: Táto možnosť je k dispozícii, ak sú zvukové
  efekty povolené. Po začiarknutí sa budú prehrávať len zvuky počasia (dážď,
  búrka, vietor) a nie zvuky prostredia. Predvolene je vypnuté.
* Používať 24-hodinový formát: Ak je odčiarknuté, oznamuje čas v
  12-hodinovom formáte, napríklad 12 AM `-` 12 PM. Predvolene je zapnuté.
* Povoliť texty Pomocníka v oknách s nastaveniami: Predvolene je zapnuté.
* Oznamovať poveternostné podmienky: Predvolene je vypnuté. Po zapnutí budú
  dostupné tieto možnosti:
* Oznamovať smer vetra: bude oznamovať pri počasí aj smer vetra. Predvolene
  zapnuté.
* Oznamovať rýchlosť vetra: Bude oznamovať rýchlosť vetra v mýľach alebo
  kilometroch za hodinu. Predvolene zapnuté.
* Oznamovať rýchlosť vetra v metroch za sekundu: Predvolene zapnuté.
* Add wind gust speed of the wind; checkbox checked (by default)
* Oznamovať pocitovú teplotu: Predvolene zapnuté.
* Oznamovať atmosferické informácie: Predvolene je vypnuté. Po zapnutí budú
  dostupné tieto možnosti:
* Oznamovať vlhkosť: Oznamuje vlhkosť vzduchu v percentách. Predvolene
  zapnuté.
* Oznamovať Viditeľnosť: Oznamuje viditeľnosť v míľach alebo
  kilometroch. Predvolene zapnuté.
* Oznamovať hodnotu Atmosferického tlaku: Oznamuje stav tlaku v milibaroch
  alebo palcoch ortuti. Predvolene je zapnuté. Po začiarknutí je tiež možné
  začiarknuť oznamovanie tlaku v milimetroch ortuti.
* Oznamovať barometrický tlak: Predvolene zapnuté.
* Add cloudiness value; check box checked (by default)
* Add precipitation value; check box checked (by default)
* Add ultraviolet radiation value; check box checked (by default)
* Read astronomical information; indicates the time of sunrise and sunset
  and the time of moonrise and moonset. Checkbox not checked (by default)
* Desatinné čísla oddeľovať čiarkou: Ak je začiarknuté, použije na oddelenie
  celých a desatinných čísel desatinnú čiarku (,). Predvolene je vypnuté a
  používa sa bodka (.)
* Skontrolovať aktualizácie: Skontroluje dostupnosť novej verzie doplnku.
* Nastavenia uložíte tlačidlom OK a zrušíte tlačidlom Zrušiť.
* Ak ste upravili zoznam s mestami a aktivujete tlačidlo Zrušiť, doplnok vás
  upozorní, že ste zabudli uložiť zmeny. Nastavenia sa ukladajú do súborov:
* "Weather.ini": prvotné nastavenia doplnku.
* "Weather.volumes": Nastavenia hlasitosti pre jednotlivé udalosti.
* "Weather.zipcodes": zoznam miest.
* "Weather.default": Your default city.
* "Weather_searchkey": Uložené vyhľadávané reťazce.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
