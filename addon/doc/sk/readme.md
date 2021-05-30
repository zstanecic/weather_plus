# Počasie Plus #

* Autor: Adriano Barbieri
* Funguje s NVDA od verzie 2017.3
* Stiahnuť: [Stabilnú verziu] [1]

# O doplnku #

* Poskytuje informácie o aktuálnom počasí a predpoveď počasia až na 9 dní
  dopredu.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Vydané pod licenciou GNU GPL (General Public License) verzia 2
* Doplnok využíva tieto služby:
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# POUŽITIE: #

* nvda+W: Oznámi informáciu o aktuálnom počasí.
* NVDA+shift+W: Oznámi predpoveď počasia až na 9 dní dopredu.
* NVDA + shift + ctrl + w: Umožňuje nastaviť dočasné mesto.
* NVDA + shift + ctrl + alt + w: Otvorí nastavenia doplnku.
* NVDA + alt + w: Oznámi dátum a čas poslednej aktualizácie informácií o
  počasí.
* ctrl+ shift + w: prepína medzi oznamovaním teploty v stupňoch Celsia alebo
  Farenheita.

# Nastavenia: #

* Skôr, než začnete doplnok používať, je potrebné nastaviť parametre. V menu Možnosti aktivujte podmenu počasie a tam vyberte jednu z možností:
* Spravovať mestá: Umožní nastaviť mesto, pre ktoré sa budú zobrazovať informácie o počasí.
* Nápoveda: Zobrazí dokument s pomocníkom v aktuálnom jazyku.
* Skontrolovať aktualizácie: Skontroluje a umožní nainštalovať novú verziu doplnku.

Nové mesto na sledovanie pridáte nasledovne:

* Aktivujte položku Spravovať mestá.
* Zobrazí sa táto správa: Predvolené mesto nie je. f1: Pomocník, f2: Oznámy
  aktuálne vybratú záložku, f3: presunie kurzor na editačné pole alebo
  zoznam, f4: Nastaví dĺžku predpovede počasia, F5: Nastavenie úrovne
  hlasitosti.
* Do textového poľa zadajte mesto, woeID alebo vyberte mesto zo
  zoznamu. Poznámka: Kláves F5 funguje len ak sú aktivované zvukové efekty.
* Po aktivovaní položky spravovať mestá sú dostupné tieto možnosti:
* Otestovať: Skontroluje názov mesta, alebo hodnotu woeID. Vyhľadá názov
  mesta podľa woeID alebo overí woeID podľa názvu mesta.
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
* Jednotky merania teploty: Pomocou prepínača vyberte medzi stupňami Celzia
  (predvolené), Fahrenheita alebo Kelvina.
* Zobraziť stupne ako: Pomocou prepínača vyberte medzi Celzia `-`
  Fahrenheita `-` Kelvina (redvolené) C` -` F `-` K alebo neurčovať.
* Dĺžka predpovede: Nastavte počet dní predpovede počasia. Maximálne 9.
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
* Oznamovať astronomické informácie: Oznamuje čas východu a západu
  slnka. Predvolene vypnuté.
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
* "Weather_searchkey": Uložené vyhľadávané reťazce.

--------------------------------------------------------------------------------

# Novinky #

# Verzia 7.4 #

* Opravené problémy s vyhľadávaním miest.

# Verzia 7.3 #

* Opravená chyba s aktualizáciami.

# Verzia 7.2 #

* Opravená chyba, ktorá astala pri uložení prvého mesta, potvrdní a
  reštartovaní doplnku.
* V okne s aktualizáciou sa opäť zobrazuje uplynutý a zostávajúci čas.
* opravený taliansky preklad.

# Verzia 7.1 #

* Opravené problémy s aktualizáciou.

# Verzia 7.0 #

* Upravené okno vyhľadávania. Reťazce hľadania je mpridať a vymazať z
  kontextovej ponuky.
* Upravené ovládanie okien.
* opravené drobné chyby.

# Verzia 6.9 #

* Pridané vyhľadávanie rekurzívnych miest pomocou platného systému, ktorý sa
  predtým používal vo verzii Weather_Plus Apixu.
* Stlačením klávesu f1 v okne nastavení získate vysvetlenie dostupných
  príkazov.

# Verzia 6.8 #

* Upravené pre Python3.

# Verzia 6.7 #

* Opravená chyba, ktorá nastala pri otestovaní kódu mesta a zaradení mesta
  do zoznamu s dočasnými mestami klávesom enter a súčasne opakovaným
  zaradením do zoznamu tlačidlom pridať.
* Do databázy bola pridaná skratka pre JUŽNÚ GEORGIU A JUŽNÉ SANDWICHOVÉ
  OSTROVY, bohužiaľ v súčasnosti sa zdá, že mestá týchto štátov nefungujú
  alebo nemajú úplné dáta, dúfame však, že toto sa čoskoro vyrieši.

# Verzia 6.5 #

* Opravené chyby so zvukovými efektmi. Mali sme chybu v cykle a tak doplnok
  volal aj neexistujúce zvuky.
* Opravená chyba v miestnom čase v podrobnostiach o meste. Chyba nastávala
  len pri použití 12-hodinového formátu.
* Opravená chyba pri práci so službou Yahoo Weather Forecast. Doplnok dával
  predpoveď z predchádzajúceho dňa.

# Verzia 6.4 #

* Z podrobností bola odstránená informácia o používaní Letného času.
* Upravené spracovanie zvukov, zvuky sa zmenia pri zmene počasia.

# Verzia 6.3 #

* Opravené problémy s kódovaním.

# Verzia 6.2 #

* Opravené problémy s pridávaním mesta.
* Opravená chyba s nesprávnou hlasitosťou zvukov po štarte doplnku.
* Pridaný chýbajúci kód z verzie 6.0; Teraz môžete obnoviť uložené mestá z
  verzie používajúcej API Apixu. Mestá sú vo formáte  "Ferrara, iter
  44,83,11,58 0“ (mesto, geografické súradnice, oblasť).

# Verzia 6.1 #

* Opravené dve chyby.

# Verzia 6.0 #

* Opäť používame Yahoo Weather API.
* Prakticky všetky funkcie predchádzajúcej verzie 4.8 sú späť a je ponechané
  tlačidlo "Premenovať".
* Kompatibilný s Python 3.

# Verzia 5.0.1 #

* Opravená chyba, ktorá vracala prázdny reťazec pri rýchlosti vetra 0 míľ za
  hodinu.
* Opravená chyba, ktorá spôsobovala nesúlad prehrávaných zvukových efektov s
  časovým pásmom.
* Upravený počet dní predpovede počasia z 9 na 6 v súbore nápovedy.

# Verzia 5.0 #

* Používame APIXU API.

# Zmeny v oknách s nastaveniami. #

* Odstránené políčko "Stav barometrického tlaku". Nahradené novým "Pridať
  hodnotu oblačnosti";
* Oznamuje oblačnosť v percentách.
* Pridané nové začiarkavacie pole „Pridať hodnotu zrážok“. Udáva množstvo
  zrážok v milimetroch.
* Odstránené začiarkavacie pole "Oznámiť čakanie pípnutím pri hľadaní
  najnovšej správy"; V predvolenom nastavení je aktívne.
* Pridané astronomické informácie;
* Čas východu a západu mesiaca.
* Pridaná možnosť premenovať mestá.
* Vylepšená funkcia tlačidla „Test“; Teraz sú akceptované niektoré príkazy
  na uľahčenie vyhľadávania miest; Tieto nové príkazy sú opísané vo funkcii
  pomocníka, ktorú je možné vyvolať pomocou F1.

# Verzia 4.8 #

# Zmeny v oknách s nastaveniami. #

* pridaná možnosť prehrávať len zvuky počasia.
* Vylepšené náhodné prehrávanie a pridaných 71 nových zvukových efektov; Pre
  ich aktualizáciu Bude potrebné odčiarknuť a opätovne začiarknuť
  začiarkávacie políčko povoliť zvukové efekty.
* Opravené ukladanie hlasitosti nastavenej používateľom.
* Odstránený nepotrebný zvuk počas výberu textu v editačnom poli  pri
  stlačení skratky ctrl+a.
* Vylepšená čitateľnosť okna nápovedy, ktorú je možné vyvolať skratkou F1.
* Pridaný nový príznak kompatibility pre NVDA 2019.1 a súčasné alpha verzie.

# Verzia 4.7.7 #

* Odstránené oznámenie o dokončenom sťahovaní aktualizácie.
* Pridaných 6 nových zvukových efektov. Je potrebné ich aktualizovať v
  nastaveniach.

# Verzia 4.7.6 #

* Opravené chyby.

# Verzia 4.7.5 #

* Opravené chyby.

# Verzia 4.7.3 #

* Z dôvodu prehľadnosti bola funkcia „podrobnosti“aktualizovaná; Informácie
  o polohe GPS poskytuje teraz veloroutes.org. To vedie k malým nevýznamným
  rozdielom.

# Verzia 4.7.2 #

* Opravená malá chyba kódovania.

# Verzia 4.7.1 #

* Opravená chyba pri získavaní informácií o časovom pásme.

# Verzia 4.7 #

* Zjednodušená sekcia aktualizácie. Keď je k dispozícii aktualizácia, bude
  možné pokračovať priamo prostredníctvom jediného dialógového okna.
* Odstránená možnosť vybrať súbor s aktualizáciou. Súbor sa automaticky
  stiahne do dočasného priečinka.

# Verzia 4.6.9 #

* Pridaný preklad do Arabčiny (vďaka Wafikovi Immaculateovi).

# Verzia 4.6.8 #

* Aktualizované lokalizácie do brazílskej portugalčiny a európskej
  portugalčiny (vďaka Albertovi Mendonçaovi).

# Verzia 4.6.7 #

* Vylepšené oznamovanie aktuálneho času; V niektorých mestách to nebolo
  správne. Pridaný letný čas k detailom; Dostupné iba pre krajiny, ktoré ho
  prijali.

# Verzia 4.6.5 #

* Opravená malá chyba pri oznamovaní času.

# Verzia 4.6.4 #

* Vylepšené oznamovanie aktuálneho miestneho času; reťazce vyhľadávania sú
  presnejšie.

# Verzia 4.6.2 #

* Po kontrole aktualizácii viac nie je možnéaktivovať tlačidlo nastaviť
  dočasné mesto, ak nie je vybraté mesto v zozname.
* Opravená chyba s nastavením doplnku ak nie je ešte vytvorený súbor s
  nastaveniami weather.ini.

# Verzia 4.6 #

* Pridaná položka "Nastaviť dočasné mesto ..."; Kvôli úplnosti je teraz
  možné dočasný zoznam miest otvoriť aj z ponuky.
* Vylepšené ovládanie stupnice teploty; Okno nastavení teraz vždy vráti
  predvolenú hodnotu.
* Vylepšená prevencia viacnásobného otvárania hlavných okien; Ak je niektoré
  z nich už otvorené, okrem zvukovej výstrahy bude zamerané.
* Vylepšené zvukové efekty; Teraz vychádzajú z aktuálneho miestneho času
  mesta.

# Zmeny v časti podrobnosti o meste. #

* Pridaný aktuálny miestny čas.
* Opravená hodnota nadmorskej výšky;Teraz vracia hodnoty nadmorskej výšky,
  ak sa jej hodnota rovná alebo je menšia ako nula.

# Verzia 4.5.5 #

* Opravený návod a preklad v Srbčine.
* Opravený nemecký preklad.

# Zmeny v oknách s nastaveniami. #

* pridaná možnosť použiť na oddelenie celých a desatinných čísel desatinnú
  čiarku.

# Verzia 4.5.3 #

* opravené 2 reťazce v ruskom a Ukrajinskom preklade.
* Opravený titulok okna kontrola aktualizácie.
* Vylepšený algoritmus aktualizácie.

# Verzia 4.5 #

* Pridaná skratka ctrl+shift+alt+nvda+W na otvorenie nastavení doplnku.
* Opravené niektoré anglické reťazce.

# Zmeny v oknách s nastaveniami. #

* Pridaných 8 nových začiarkavacích polí. Môžete zapnúť oznamovanie táchto
  údajov:
* Smer vetra.
* rýchlosť vetra.
* Pocitová teplota.
* Vlhkosť.
* Viditeľnosť.
* Hodnota atmosférického tlaku.
* Udáva atmosférický tlak v palcoch ortuti (mmHg).
* Stav barometrického tlaku.

# Verzia 4.4.8 #

* Pridaný preklad do poľštiny (pripravil Zvonimir Staneczyć).
* Kompatibilné s wx python verzia 4.

# Verzia 4.4.1 #

* Pridaná podpora SSL.

# Verzia 4.4 #

* Opravená chyba pri čítaní reťazca novej verzie počas časového limitu
  pripojenia.
* Vylepšená sekcia aktualizácie; Teraz dialóg nezasahuje do ponuky NVDA.
* Opravený Ruský preklad.
* Pridaný ukrajinský preklad (pripravil Alex Yeshanu).

# Verzia 4.3.4 #

* Opravený nemecký preklad.

# Verzia 4.3.3 #

* Pridaný preklad do nemčiny (Karl Eick).

# Verzia 4.3.2 #

* Pridaná lokalizácia do rumunčiny (vďaka Florianovi Ionascuovi).

# Verzia 4.3.1 #

* Opravená menšia chyba v podrobnostiach miest. Prehodili sa nám hodnoty
  zemepisnej dĺžky a šírky.

# Verzia 4.3 #

* Doplnok presunutý na nvda.it.

# Verzia 4.2.4 #

* Opravené drobné problémy s pripojením.

# Verzia 4.2.3 #

* Doplnok sa opakovane pokúša overiť WoeId a predvolene toto oznamuje
  zvukom. Zvukový signál sa dá vypnúť.

# Verzia 4.2.2 #

* Opravená chyba v preklade pri stupnici meraní. V niektorých jazykoch
  neboli preložené Kelvin, Celzius a Fahrenheit.

# Verzia 4.2.1 #

* Opravené oznámenie o aktualizácii Weather Plus počas spúšťania systému
  Windows; Nastalo po stlačení tlačidla "použiť aktuálne nastavenia NVDA na
  prihlasovacej a zabezpečených obrazovkách (vyžaduje administrátorské
  práva)" vo všeobecných nastaveniach nvda. Nastavenia doplnku boli
  skopírované, ale neboli synchronizované s nastaveniami doplnku v
  používateľskom profile NVDA. Odporúčame skopírovať dáta doplnku znovu.

# Verzia 4.2 #

* Pridaných 5 nových zvukových efektov, efekty je potrebné aktualizovať v
  nastaveniach doplnku.
* Opravená chyba vo funkcii importu; Zoznam miest nebol abecedne
  usporiadaný.
* Pri importe odteraz môžete úplne nahradiť svoj vlastný zoznam alebo do
  neho jednoducho pridávať nové mestá.
* Aktualizované oznamovanie predpovede počasia, Pridanie pocitovej teploty
  (ochladzovanie vetrom).
* Pridané nové reťazce do správ o počasí.

# Verzia 4.1 #

* Opravená chyba v predpovedi na 10 dní. Ak je počet prijatých dát nižší ako
  požiadavka používateľa, chýbajúce dni sa označia ako neznáme.
* Opravený reťazec nápovedy v príkaze nvda + shift + w.
* Aktualizovaná používateľská príručka.

# Verzia 4.0 #

* Aktualizované niektoré časti kódu a nahradené všetky inštrukcie eval().

# Verzia 3.9.7 #

* Opravená chyba oznamovania predpovede počasia, teploty sú oznamované
  správne.

# Verzia 3.9.6 #

* Opravená konverzia z milibarov na jednotky ortuti.

# Verzia 3.9.5 #

* Pridané 2 nové reťazce do zoznamu správ o oznamovaní počasia.
* Opravené dve chyby.
* Aktualizované zvuky vetra, pridaná možnosť náhodne meniť zvuk vetra.

# Verzia 3.9.4 #

* Odstránenie nemeckého a Chorvátskeho prekladu, nakoľko ich autory viac
  neprekladajú.
* Opravená chyba v srbskej lokalizácii.
* Aktualizovaný český preklad.
* Aktualizovaný návod a preklad do Galijcijčiny.

# Verzia 3.9 #

* Odteraz používame nové Yahoo Weather API s jazykom Yahoo! Query a JQuery:
* Nevyžaduje sa viac vlastný kľúč.
* Obnovené Hľadanie miest, zo zoznamu je možné vybrať presné miesto.
* Upravené prehrávanie efektov, je stabilnejšie a synchronizované s hlasovým
  výstupom.
* Vylepšená vyrovnávacia pamäť pre dáta off-line; Vynulujú sa každých 10
  minút alebo pri zmene mesta.
* barometrický tlak meraný v milibaroch alebo v palcoch ortuti (ak je
  nastavený na stupne Fahrenheita).

# Verzia 3.8 #

* Spresnené získavanie údajov.
* API posiela informácie o počasí podľa jazyka NVDA.
* Pridaná vyrovnávacia pamäť pre správy a predpovede počasia; Ak sa nezmení
  mesto, stupnica alebo nastavené dni prognózy, budete si môcť údaje
  prečítať po dobu 10 minút, aj keď vypadne pripojenie k
  internetu. Vyrovnávacia pamäť sa vynuluje pri každej vyššie uvedenej
  zmene. Je to z toho dôvodu, že sa správy v tomto časovom období nemenia a
  redukujeme tak časté volania API.
* Vylepšené vyhľadávanie aktualizácií; Po stiahnutí sa spustí inštalácia a v
  prípade prenosnej verzie sa otvorí priečinok so súborom doplnku.
* Aktualizované všetky zvuky. Teraz sú zvuky vo formáte wav.

# Verzia 3.7 #

* Pridaná možnosť vypnúť pri vetre prepočet v metroch za sekundu.
* Pridaná možnosť používať mernú jednotku libra na palec štvorcový.
* Opravené dve chyby.

# Verzia 3.6 #

* Používame služby OpenWeatherMap.org namiesto Yahoo Weather.com.
* Pridané informácie o smere vetra.
* pridaná oblačnosť.
* Pridané informácie o tlaku v hektopaskaloch.

# Zmeny v okne s nastaveniami #

* Upravené hľadanie. Viac nie je potrebné zadávať čísla, stačí zadávať názvy
  miest.
* Pridané hľadanie podľa súradníc.
* Pridané hľadanie podľa poštového smerového čísla.
* Vylepšená funkcia podrobnosti.
* Kláves F1 zobrazí v okne s nastaveniami nápovedu.
* Klávesom F4 je možné upraviť rozsah predpovede do 16 dní. Do schránky sa
  ale dá skopírovať len prvých desať dní.
* Klávesom F5 môžete upraviť úroveň hlasitosti zvukových efektov.
* Pridaná stupnica na meranie v Kelvinoch.
* Pridaná kontrola aktualizácií; Kontrolu môžete nastaviť v nastaveniach
  alebo spustiť ručne z ponuky.
* Vrátili sme tlačidlo "nájsť svoje mesto" v časti s nastavením kľúča.

# Verzia 3.5 #

* Pridaný preklad do Chorvátčiny (vďaka Gordanovi Radičović).
* Odstránené Woeid, ktoré viac nefungujú. Doplnok upozorní, ak takéto ID
  zadáte. Ak narazíte na nefunkčné kódy, informujte autora.
* Opravená chyba kódovania vo funkcii vyhľadávania.
* Aktualizované okno na nastavenie jedného dočasného PSČ; Pridaná funkcia
  „Nájsť“ Rovnako ako v ostatných oknách doplnku: Ctrl + F3 = Nájsť, F3 =
  Nájsť ďalšie, Shift + F3 = Nájsť predchádzajúce.

# Verzia 3.4 #

* Pridaný preklad do Galicijčiny (vďaka Ivánovi Novegilovi).
* Pridaný preklad do Portugalčiny (vďaka Ângelovi Miguelovi Abrantesovi).
* Pridaný preklad do Nemčiny (neúplný).

# Verzia 3.3 #

* Pridané meranie rýchlosti vetra v metroch za sekundu.
* Opravené problémy s kódovaním.

# Verzia 3.2 #

* Aktualizované oznamovanie súčasnej predpovede a oznamovanie aktuálneho
  stavu a dátumu predpovede počasia. Yahoo weather forecast občas a úplne
  náhodne vkladá medzi dáta aj informácie o počasí z predošlých dní. Doplnok
  na toto upozorňuje pípaním. Upozornenie je možné vypnúť v
  nastaveniach. Filtrovanie dát chvíľu trvá, ale pauzy nie sú veľké.
* Poskytujeme predpoveď až na 10 dní.

# Verzia 3.1 #

* Pridaný preklad do srbčiny (vďaka láskavej spolupráci Dejana Gasica).
* Po stlačení nvda+alt+w doplnok najprv overí, či je správne zadané psč a či
  je dostupné pripojenie na internet.
* zvukové efekty sú vo formáte mp3 a sú menšie.
* Pridaných 55 nových zvukových efektov, je potrebné ich aktualizovať z
  nastavení doplnku.

# Zmeny v okne s nastaveniami #

* Opravené správy s nápovedou pri tlačidlách v okne nastavení. Nápovedu je
  odteraz možné zapnúť a vypnúť v reálnom čase.
* Pridané 3 skratkové príkazy na rýchlejšiu navigáciu v okne:
* F1 skočí do zoznamu a do editačného poľa s PSČ.
* F2 sa vráti na posledný výber dosiahnutý pomocou TAB.
* F3 skočí na ovládanie hlasitosti (ak sú zvukové efekty nainštalované a
  aktivované).
* Pridané skratkové príkazy pre všetky začiarkávacie polia a tlačidlá;
  Vynechané sú dva prepínače, ktoré sú za sebou a prvý sa dá nájsť skratkou
  ctrl+ shift + w.
* Tlačidlo nastaviť zvukové efekty sa nedá aktivovať, ak nie sú
  nainštalované zvukové efekty.
* pridaná možnosť upraviť hlasitosť pre všetky zvukové efekty alebo pre
  jednotlivé zvuky. Možnosť je dostupná len ak sú už nainštalované zvukové
  efekty.
* Pridaná možnosť nastaviť zobrazenie času v 12-hodinovom formáte (12:30 AM
  `-` 12:30 PM) , alebo 24-hodinovom formáte (12:30 `-` 00:30).

# Verzia 3.0 #

* Pridaný preklad do slovenčiny (vďaka láskavej spolupráci Vítka Jiráska).
* Pridaný preklad do brazilskej portugalčiny a európskej portugalčiny (vďaka
  láskavej spolupráci Adaira Knaesela).
* Pridané nové reťazce do správ o počasí.
* Pridaných 171 nových zvukových efektov, teraz je konečný počet 213.
* Pridaná klávesová skratka nvda+alt+w na oznáenie posledneja aktualizácie
  správy o počasí.
* Pridaná správna kategória pre doplnok do dialógu klávesové skratky.

# Zmeny v okne s nastaveniami #

* Pridaný prepínač na nastavenie spôsobu oznamovania teploty;
* Na výber je:
* Celsius `-` Fahrenheit
* C `-` F
* bez oznamovania
* Pridaná možnosť definovať zónu mesta. Dostupné sú možnosti:
* Vnútrozemie
* Prímorská oblasť
* Púštna zóna
* Arktická zóna
* Horská zóna
* Toto spôsobí prispôsobenie zvukových efektov pre konkrétne mesto. Preto
  stúpol aj počet zvukových efektov. Efekty poskytol Tapin.

# Verzia 2.9 #

* Pridaná možnosť zvolenia obsahu súboru, z ktorého sa importujú kódy mesta.
* štyri nové zvukové efekty.
* Pridaný preklad do ruštiny (priipravil Alex Yeshanu).
* Pridaný preklad do češtiny (vďaka Jiřímu Holzingerovi).

# Verzia 2.8 #

* Tlačidlo Podrobnosti viac neotvorí okno v prípade, že nebolo vybraté
  mesto.
* Opravený regexp na hľadanie súradníc; Nepríjmal parametre jednotlivých
  číslic.
* opravené spracovanie textového poľa, teraz by ste ľahšie mali vyhľadať
  požadované mesto.
* Pripojenie k serverom zabezpečuje knižnica urllib2 a nie urllib. Takto
  funguje pripojenie k službám aj cez proxy.
* Pridaná funkcia Nájsť. Ctrl+F3 = Nájsť, F3 = Nájsť ďalšie, Shift + F3 =
  Nájsť predchádzajúce.

# Verzia 2.7 #

* Opravené nesprávne meno reťazca "Motorcycle" v "Motorcycle00"; čo
  spôsobovalo nemožnosť nájsť príslušný efekt.
* Pridaná možnosť oznamovať informácie o vetre; Smer, rýchlosť a teplotu
  vetra.
* Pridaná možnosť oznamovať atmosférické informácie; Vlhkosť, viditeľnosť,
  tlak a stav barometrického tlaku.
* Pridaná možnosť oznamovať astronomické informácie;  Čas východu a západu
  slnka.

# Zmeny v okne s nastaveniami #

* Oznamovanie vyššie spomenutých údajov sa dá zapnúť a vypnúť príslušnými
  políčkami v nastaveniach.
* Pridané tlačidlo podrobnosti o meste. Poskytuje úplný názov mesta, ( Podľa
  služby Yahoo Weather Forecast), štát / región a národnosť, ku ktorej
  patrí, súradnice a  informácie o nadmorskej výške.
* Pridané rozpoznávanie WoeID (lokalizačné kódy, napr. Bologna, zodpovedá
  711080).
* Teraz môžete zadať názov mesta. Dopllnok vyhľadá výskyty a môžete si
  vybrať požadované správne mesto.

# Verzia 2.6 #

* Zrýchlené pridávanie a odstraňovanie miest.
* Testovanie mesta sa pokúša hľadať 13 krát po sebe. Ak sa to nepodarí, je
  jasné, že mesto skutočne nie je možné nájsť.
* Funkcia tlačidla "Nájsť mesto ..." teraz nájde viac krajín; Bola pridaná
  automatická skúška, ktorá zhromažďuje funkčné PSČ a ďalej udeľuje rýchlu
  vizualizáciu vďaka vytvoreniu malého buffera so zodpovedajúcim názvom
  konkrétnej krajiny.
* Pridané tri nové zvukové efekty, je potrebné aktualizovať v nastaveniach
  doplnku.

# Verzia 2.5 #

* Pridaná klávesová skratka na prepínanie medzi jednotkami teploty
  Fahrenheit a Celzius, teploty je tiež možné prepínať v nastaveniach.
* Ak používateľ nestlačí tlačidlo pridať alebo Predvoliť, stále je možné v
  zozname vidieť mesto.
* Pridané nové reťazce do správ o počasí.

# Zmeny v okne s nastaveniami #

* Pridané tlačidlo na otvorenie webovej stránky pre vyhľadania kódov miest
  pre rôzne krajiny a mestá.
* Pridaná možnosť importu /exportu kódov miest.
* Pridaná možnosť skopírovania ohlásenej predpovede do schránky.
* Pridaná možnosť inštalácie, počúvania a odinštalácie zvukových efektov.
* Pridaná možnosť nápovedy do okna s kódmi miest.
* Upravený vzhľad okien doplnku.

# Verzia 2.4.4 #

* Pridané 2 nové reťazce do zoznamu správ o oznamovaní počasia.
* Pridané preklady do španielčiny a francúzštiny, (pripravili Pablo Vargas a
  Rémy Ruiz).

# Verzia 2.4.3 #

* Pridaná predpoveď počasia na 4 dni dopredu.
* Pridanie reťazcov pre ohlasovanie počasia.
* Zoznam s dočasnými kódmi miest je vždy zoradený po pridaní nového mesta.

# Verzia 2.4 #

* Opravená chyba, kedy nešlo uložiť mesto kvôli špeciálnym znakom.

# Verzia 2.3 #
* Odstránené dialógové okno pre nastavenie rozsahu merania teploty, teraz sa
  všetko nastavuje v jednom okne.
* Pridané mesto do zoznamu je možné otestovať a nastaviť ako predvolené.
* Upravené zadávanie PSČ mesta. Umožňuje nastaviť PSč, ktoré ste už vybrali
  v zozname v ponuke.
* Teraz je možné čítať dokumentáciu v angličtine, ak nie je dostupná
  lokalizovaná dokumentácia.

# Verzia 2.2 #

* Opravená chyba, kedy nešlo otvoriť nápovedu v stabilných verziách NVDA.

# Verzia 2.1 #

* Opravená chyba, kedy sa doplnok nekorektne zatváral a bránil tak
  aktualizácii položky NVDA na systémovom panely.

# Verzia 2.0 #

* Presunutá položka nastavenia.
* Správne údaje sa ákladajú až po aktivovaní príslušného tlačidla. Ak
  potrebujete vyvolať mesto pred uložením nastavení, stlačte ctrl+nvda+F3.

# Verzia 1.9 #

* Pridané nápovedy pre nastavenia.
* Pridaná nová funkcia pre zadanie psč.
* Nastavenia sa ukladajú do ini súboru, nie je potrebné upravovať zdrojový
  kód.
* Pridané menu doplnku i do menu NVDA v oznamovacej oblasti.
* Pridané nastavenie pre zadanie psč.
* Pridané nastavenie na prepínanie stupňov (Celzius alebo Fahrenheit).
* Pridaná nápoveda.
* Pridaný preklad do taliančiny.

# Prvé vydanie 1.1 #

* Aktualizovaný doplnok.
* Bola pridaná podpora prekladu.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
