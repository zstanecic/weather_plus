# Weather Plus #

* Autor: Adriano Barbieri
* Kompatibilita s NVDA: 2017.3 až 2019.3
* Stiahnuť: [Stabilná verzia] [1]

# O WEATHER PLUS: #

* Tento plugin pridáva pre NVDA lokálnu teplotu a predpovede na 24 hodín až
  9 dní.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Vydané pod GNU GPL (General Public License) v2
* Služba Weather Plus funguje prostredníctvom a za prítomnosti nasledujúcich
  služieb:
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# POUŽITIE: #

* Stlačte NVDA + w pre aktuálnu teplotu a poveternostné podmienky.
* Stlačte NVDA + shift + W pre predpoveď na 24 hodín až 9 dní.
* Press NVDA+shift+control+w to set a temporary city.
* Press NVDA+shift+control+alt+w to open the Weather Plus settings dialog.
* Stlačte NVDA + alt + w na zistenie poslednej aktualizácie správy o počasí.
* Stlačte ctrl+ shift + w na prepnutie medzi stupňami Fahrenheita, Celsia
  alebo Kelvina.

# Weather Plus nastavenia: #

* You must set the Weather Plus addon before its first use! Go to the Preferences submenu, Weather Plus Settings submenu and choose one of the following options:
 * Set and Manage Your Cities... - Displays or allows to set the current city from a list.
 * Documentation - Opens the help file for the current language.
 * Check for Update... - Notifies about the availability of the new version.

To add a new city: press the following item:

* Nastavte a spravujte svoje mestá ... - Zobrazí alebo umožní nastaviť
  aktuálne mesto zo zoznamu.
* Nasledujúca správa sa zobrazí iba prvýkrát! Predvolené Nastavenia Žiadne
  F1: umiestnenie nápovedy, F2: posledný výber TAB, F3: zoznam a editovacie
  pole, F4: ovládanie trvania Predpovede počasia, F5: ovládanie hlasitosti
* Do textového poľa zadajte mesto, woeID alebo vyberte jedno zo zoznamu, ak
  je k dispozícii. Poznámka: Kláves F5 je k dispozícii, ak sú aktivované
  zvukové efekty.
* Po stlačení klávesy Enter na položke „Nastaviť a ovládať kód mesta ...“
  nájdete ďalšie tlačidlá ako:
* Test - Testing the validity of woeID entry and find the name of city
  assigned or vice versa.
* Add - Adds the current city into your list. This button can be activated
  if you select a city from the list, when the city entered passed the test.
* Details - Displays information about the current city. This button is
  activated if you select a city from the list, or it has passed the test.
* Definovať - Umožňuje definovať oblasť s cieľom prispôsobiť zvukové
  efekty. Toto tlačidlo sa dá aktivovať, ak sú zvukové efekty nainštalované
  a aktivované a ak je zo zoznamu vybraté mesto.
* Predvolené - Predvolené mesto je predvolené, použije sa pri každom
  reštarte doplnku. Toto tlačidlo sa aktivuje, ak vyberiete mesto, ktoré
  bolo predtým vložené do zoznamu a nie je prednastavené alebo ak prešlo
  testovaním.
* Odobrať - Odstráni aktuálne mesto zo zoznamu. Toto tlačidlo sa dá
  aktivovať, ak vyberiete mesto, ktoré bolo predtým vložené do zoznamu.
* Premenovať - Premenuje aktuálne mesto. Toto tlačidlo sa dá aktivovať, ak
  vyberiete mesto, ktoré bolo predtým vložené do zoznamu.
* Import new cities... - This button allows you to import cities from the
  another list of cities with the extension *.zipcodes; you can select the
  city you want to import, by turning on the checkbox associated with it.
* Exportovať svoje mestá ... - Umožňuje vám uložiť mestá do určeného súboru
  s príponou * .zipcodes. Toto tlačidlo sa aktivuje, ak ste do zoznamu
  pridali a uložili aspoň jedno mesto.
* Stupnica merania teploty: Pomocou prepínača vyberte medzi stupňami Celzia
  (predvolené), Fahrenheit a Kelvin.
* Degrees shown as: Use the radio button to select between: Celsius `-`
  Fahrenheit `-` Kelvin (by default) C `-` F `-` K or Unspecified.
* Combo box: Weather Forecasts up to days: 3; you can choose between 1 to 10
  (3 days by default)
* Vykonanie nasledujúcich akcií vykonáte prepnutím nasledujúcich
  začiarkávacich polí:
* Copy the weather report and weather forecast, including city details to
  clipboard; checkbox not checked (by default)
* Enable audio effects (only for the current weather conditions); this
  checkbox also allows you to manage the installation of sound effects; if
  the sound effects are installed and the checkbox is activated, the F5 key
  and the volume setting becomes available.
* There will also be available an additional checkbox: "Use only weather
  effects".
* You can change the overall volume or change the last heard sound effect
  and filter out the others sounds in your environment. Checkbox is not
  checked by default.
* Use only weather effects - This option is available if sound effects are
  enabled; if is enabled, allows to listen only weather effects such as
  rain, wind, thunder, etc., filtering out all environmental
  ones. (unchecked by default)
* Enable the reading of the hours in 24-hour format. - If this checkbox is
  unchecked, announces the time in 12-hour format for example, 12 AM `-` 12
  PM. Checkbox is checked (by default)
* Enable help buttons in the settings window; checkbox checked (by default)
* Read wind information; checkbox not checked (by default). If this checkbox
  is enabled, you can also activate the following checkboxes:
* Add wind direction; indicates the provenance of the wind. Checkbox checked
  (by default)
* Add speed of the wind; indicates the speed in kilometers or miles per
  hour. Checkbox checked (by default)
* Add speed in meters per second of the wind; checkbox checked (by default)
* Add perceived temperature; checkbox checked (by default)
* Read atmospherical information; checkbox not checked (by default). If
  enabled, you can also check the following checkboxes:
* Add humidity value; indicates the humidity in percent. Checkbox checked
  (by default)
* Add visibility value; indicate in kilometres or miles the distance
  visible. Checkbox checked (by default)
* Add atmospheric pressure value; indicates the atmospheric pressure in
  millibars or inches of mercury. If it's checked, enable an additional
  checkbox that allows you to indicate the pressure in millimeters of
  mercury. Checkbox checked (by default)
* Pridať stav barometrického tlaku; začiarkávacie pole začiarknuté
  (predvolené)
* Read astronomical information; indicates the time of sunrise and
  sunset. Checkbox not checked (by default)
* Use the comma to separate decimals; if enabled, uses the comma as a
  decimal separator, otherwise, use the point. Checkbox not checked (by
  default)
* Check for upgrade; if is activated this alerts when there is an update of
  the addon. Checkbox checked (by default)
* Stlačením tlačidla OK potvrďte akciu alebo tlačidlom Zrušiť akciu zrušte.
* If you have modified the cities list, by pressing "Cancel", you will be
  remembered and you can still save it. Note: your settings will be save in
  the file named:
* "Weather.ini": prvotné nastavenia Weather Plus.
* "Weather.volumes": Vlastné nastavenie úrovne hlasitosti nezávisle na
  hlasitosti pre všetky zvukové efekty.
* "Weather.zipcodes": zoznam miest s ich PSČ a popisom.
* „Weather_searchkey“: vyhľadávaný kľúč bol uložený.

--------------------------------------------------------------------------------

# Čo je nové: #

# Version 7.4 #

* Fixed a bug in a city search function.

# Verzia 7.3 #

* Opravená neočakávaná chyba v prípade, že sa stránka pri vyhľadávaní
  aktualizácií nenašla.

# Verzia 7.2 #

* Fixed bug after adding a city, if it is the first one entered if you press
  ok button and restart the add-on.
* Teraz sa v okne priebehu znova zobrazuje zostávajúci čas a uplynutý čas.
* Correct Italian translation in the help of the Rename button.

# Verzia 7.1 #

* Opravená chyba aktualizácie.

# Verzia 7.0 #

* Vylepšené okno vyhľadávania, teraz je možné spravovať celý vložený  kľúč,
  je možné ho pridať, odstrániť a uložiť ho z kontextového menu.
* Vylepšené ovládanie otvárania okien.
* Some little bugs fixed.

# Verzia 6.9 #

* Implementovalo sa vyhľadávanie rekurzívnych miest pomocou platného
  systému, ktorý sa predtým používal vo verzii Weather_Plus Apixu.
* Stlačením klávesu f1 v okne nastavení získate vysvetlenie dostupných
  príkazov.

# Verzia 6.8 #

* Updated compatibility for Python 3.

# Verzia 6.7 #

* Opravená chyba pri testovaní nového mesta v dočasnom režime jednoduchým
  stlačením klávesu „Enter“ a neskorší pokus o pridanie pomocou tlačidla
  „Pridať“.
* Do databázy bola pridaná skratka pre JUŽNÚ GEORGIU A JUŽNÉ SANDWICHOVÉ
  OSTROVY, bohužiaľ v súčasnosti sa zdá, že mestá týchto štátov nefungujú
  alebo nemajú úplné dáta, dúfame však, že toto sa čoskoro vyrieši.

# Verzia 6.5 #

* Opravená chyba pri reprodukcii zvukových efektov; Niekoľko cyklov typu
  „for“ s nesprávnymi maximálnymi hodnotami spôsobilo vyvolanie
  neexistujúceho zvukového efektu.
* Fixed bug in local time in "details"; 12-hour time conversion gave an
  error.
* Fixed a bug in the Yahoo Weather Forecast report; in some cities the
  forecasts start from the previous day and not from the current one. The
  correction of these cities entails the loss of the last days of forecast
  proportionate to the mismatch of dates (if the forecast days are set to
  10).

# Verzia 6.4 #

* Daylight saving time removed in the "Details" function.
* Improved audio effects reproduction; now they update regularly if the
  weather conditions change.

# Verzia 6.3 #

* Opravené problémy s kódovaním.

# Verzia 6.2 #

* Fixed bug in the "Add city" function.
* Opravená chyba, ktorá pri spustení addonu nepriradila premennú "_volume".
* Added missing code from version 6.0; now you can recover the saved cities
  from the version that uses the Apixu API; the "Test" and "Remove" buttons
  and non-compatible cities are available in the format: "Ferrara, iter
  44.83,11.58 0" (city, geographic coordinates, area definition).

# Verzia 6.1 #

* Opravené 2 chyby.

# Verzia 6.0 #

* Weather Plus sa vracia k používaniu Yahoo Weather API.
* Prakticky všetky funkcie predchádzajúcej verzie 4.8 sú späť a je ponechané
  tlačidlo "Premenovať".
* Kompatibilný s Pythonom 3.

# Verzia 5.0.1 #

* Opravená chyba, ktorá vracala prázdny reťazec pri rýchlosti vetra 0 míľ za
  hodinu.
* Opravená chyba, ktorá spôsobovala nesúlad prehrávaných zvukových efektov s
  časovým pásmom.
* Adjusted the number of forecast days from 9 to 6 in readme.

# Verzia 5.0 #

* Weather Plus now uses the APIXU API.

# Zmeny v okne Weather Plus nastavenia #

* Odobraté staré začiarkávacie pole "Stav barometrického tlaku". Nahradené
  novým začiarkávacim poľom „Pridať hodnotu oblačnosti“;
* V percentách poskytuje  oblačnosť.
* Pridané nové začiarkavacie pole „Pridať hodnotu zrážok“. Udáva množstvo
  zrážok v milimetroch.
* Removed old checkbox "Indicates the wait with a beep while you search for
  the latest bulletin"; left active by default.
* Added the astronomic information;
* Čas východu a západu mesiaca.
* Added new button "Rename"; to rename cities more conveniently.
* Improved function of the "Test" button; now accept some commands to
  facilitate the search for cities; these new commands are described in the
  help function that can be called up with F1.

# Verzia 4.8 #

# Zmeny v okne Weather Plus nastavenia #

* Added new checkbox; "Use only weather effects"; this allows you to filter
  out all other environmental effects.
* Improved random playback and added 71 new sound effects; you will need to
  update them by clicking twice in "enable audio effects" checkbox.
* The volume type assigned by the user, between the general and current
  audio volume, is now maintained when the configuration is saved.
* Odstránený nepotrebný zvuk počas výberu textu v editačnom poli  pri
  stlačení kláves control + a.
* Vylepšená čitateľnosť okna nápovedy, ktorú je možné vyvolať funkčným
  klávesom F1.
* Pridaný nový príznak kompatibility pre NVDA 2019.1 a súčasné verzie alfa.

# Verzia 4.7.7 #

* Odstránené oznámenie, o dokončenom sťahovaní pri aktualizácii programu
  Weather Plus.
* Added 6 new sound effects; it will be necessary to update them from the
  settings of the plugin.

# Verzia 4.7.6 #

* Bugfix release.

# Verzia 4.7.5 #

* Bugfix release.

# Verzia 4.7.3 #

* "Details" function was updated for convenience; the information about the
  altitude are now provided by veloroutes.org. This leads to small
  differences of little relevance.

# Verzia 4.7.2 #

* Opravená malá chyba kódovania.

# Verzia 4.7.1 #

* Opravená chyba pri získavaní informácií o časovom pásme.

# Verzia 4.7 #

* Simplified the update section; now at the start, in case an update is
  available it will be possible to proceed directly through a single dialog
  box.
* Removed the file selector in the update section; now the update file is
  saved to the temporary folder, it open the possibility to install the
  update automatically, good for beginners.

# Verzia 4.6.9 #

* Added Arabic localization (thanks to Wafik Immaculate).

# Verzia 4.6.8 #

* Updated localizations for Brazilian Portuguese and European Portuguese
  localizations (thanks to Alberto Mendonça).

# Verzia 4.6.7 #

* Improved the reading of the current time; in some cities, it was not
  correct. Added daylight saving time to the details; available only for the
  countries that adopt it.

# Verzia 4.6.5 #

* Opravená malá chyba pri oznamovaní času.

# Verzia 4.6.4 #

* Vylepšené oznamovanie aktuálneho miestneho času; tlačidlá vyhľadávania sú
  presnejšie.

# Verzia 4.6.2 #

* Opravená chyba: po kontrole aktualizácii, bolo povolené menu "nastaviť
  dočasné mesto aj keď nebol k dispozícii žiaden zoznam miest.
* Opravená chyba; nie je možné konfigurovať WP keď ešte nebol vytvorený
  súbor weather.ini,.

# Verzia 4.6 #

* Added the menu item "Set a temporary city..."; for the sake of
  completeness, now you can open the temporary city's list also from the
  menu.
* Improved management of temperature scale; now the settings window will
  always return the default value.
* Improved prevention of the multiple opening of the main windows; if one of
  these is already opened, in addition to the sound alert, puts it in
  foreground.
* Improved audio effects; now are based on the current local time from the
  city in use.

# Zmeny v podrobnostiach funkcií okna nastavenia #

* Pridaný aktuálny miestny čas.
* Fixed altitude value; now return the altitude values when the value is
  less than or equal to zero.

# Verzia 4.5.5 #

* Correct localization and documentation in Serbian.
* Opravená lokalizácia v nemčine.

# Zmeny v okne Weather Plus nastavenia #

* Added new checkbox; you can enable the comma as the decimal separator,
  otherwise the separator will be the point.

# Verzia 4.5.3 #

* Correct 2 strings in Russian and Ukrainian localizations.
* Corrected title of the Check for upgrade window.
* Improved update algorithm.

# Verzia 4.5 #

* Added hotkey NVDA+shift+control+alt+w; it Opens the Weather Plus settings
  dialog.
* Opravené niektoré anglické reťazce.

# Zmeny v okne Weather Plus nastavenia #

* Added 8 new checkboxes; it is now possible to further customize the
  readout:
* Wind direction.
* Wind speed.
* Pocitová teplota.
* Hodnota vlhkosti.
* Hodnota viditeľnosti.
* Hodnota atmosférického tlaku.
* Udáva atmosférický tlak v milibaroch alebo palcoch ortuti (mmHg).
* Stav barometrického tlaku.

# Verzia 4.4.8 #

* Pridaný preklad do poľštiny (vďaka Zvonimirovi Staneczymuć).
* Compatibility with wx python version 4.

# Verzia 4.4.1 #

* Added SSL support.

# Verzia 4.4 #

* Opravená chyba pri čítaní reťazca novej verzie počas časového limitu
  pripojenia.
* Improved the upgrade section; now the dialog do not interferes with the
  nvda menu.
* Revised and corrected Russian localization.
* Pridaný ukrajinský preklad (vďaka Alexovi Yeshanuovi).

# Verzia 4.3.4 #

* Revidovaná a opravená nemecká lokalizácia.

# Verzia 4.3.3 #

* Pridaná lokalizácia do nemčiny (vďaka Karlovi Eickovi).

# Verzia 4.3.2 #

* Pridaná lokalizácia do rumunčiny (vďaka Florianovi Ionascuovi).

# Verzia 4.3.1 #

* Fixed a minor bug in the function "details"; the strings "latitude" and
  "longitude" were reversed compared to the value.

# Verzia 4.3 #

* Weather Plus moved to the "nvda.it" as it's default hosting provider.

# Verzia 4.2.4 #

* Fixed a minor bug when the connection was not active.

# Verzia 4.2.3 #

* Now Weather Plus is able to run some connection attempts before notifying
  the malfunction of the WoeId in use, it emits a beep at each attempt; this
  beep, if you want, can be disabled by using a checkbox by Weather Plus
  settings.

# Verzia 4.2.2 #

* Fixed bug in the translation strings for the scale measurement. In some
  languages, Kelvin, Celsius and Fahrenheit have not been translated.

# Verzia 4.2.1 #

* Fixed update notice of Weather Plus during the Windows start-up; this
  happens when the button was pressed "Use currently saved settings on the
  logon and other secure screens (requires administrator privileges)" from
  the general settings of nvda, which copies the configuration, and all of
  the add-on folder systemConfig, but these are not synchronized with
  subsequent updates of the add-ons. If you have ever used at least once
  this option, you will have to do it again one last time just after to have
  up-to-date Weather Plus.

# Verzia 4.2 #

* Added 5 new sound effects; it will be necessary to update them from the
  settings of the plugin.
* Fixed bug in the import function; the list of cities was not sorted
  alphabetically.
* Added import mode in the import function; you may decide to completely
  replace your own list, or simply add new cities to it.
* Updated the reading of the weather forecast, current weather report;
  adding the perceived temperature (wind chill).
* Pridané nové reťazce do zoznamu weather reports.

# Verzia 4.1 #

* Fixed bug in the forecast for up to 10 days; now if the estimates received
  are in number less than the request of the user, the missing days are
  indicated as unknown.
* Opravený reťazec nápovedy v príkaze nvda + shift + w.
* Revidovaná a aktualizovaná dokumentácia.

# Verzia 4.0 #

* Updated some parts of code and replaced all instructions eval().

# Verzia 3.9.7 #

* Fixed bug during the reading of weather forecasts; now the temperatures
  are read correctly.

# Verzia 3.9.6 #

* Changed the rounding in the conversion of atmospheric pressure from mbar
  in inches of mercury; now the value is calculated in defect, while before
  it was in excess.

# Verzia 3.9.5 #

* Pridané 2 nové reťazce do zoznamu správ o oznamovaní počasia.
* Opravené 2 chyby.
* Updated running sounds for the effect in conditions of only wind; now the
  sound of the wind can vary randomly.

# Verzia 3.9.4 #

* Documentations, localizations for Croatian and German language were
  removed; because they are no longer supported by the respective
  translators.
* Fixed bug in Serbian localization.
* Aktualizovaná česká lokalizácia.
* Updated documentation and localization for Galician.

# Verzia 3.9 #

* Opäť zmenená služba API; Weather Plus teraz používa nové Yahoo Weather API
  s jazykom Yahoo! Query a JQuery:
* The api key is no longer required.
* Restored The search of the homonymous cities; it will be possible to
  choose exactly the desired city from a list.
* Optimized the output of general sounds; now they are synchronized with the
  voice synthesis and are faster.
* Improved the cache for data off-line; is zeroed every 10 minutes or only
  by changing the city.
* Barometric pressure measured in mbar, or in inches of mercury (if set to
  Fahrenheit).

# Verzia 3.8 #

* Data accuracy fixes.
* Enabled the automatic setting of the language; now the API sends the data
  of the weather conditions in the language set by nvda.
* Added the cache for bulletin and weather forecasts; if not changed the
  city, degree scale or the days of forecast set, you will be able to read
  the data for 10 minutes even when connection off-line. The cache is reset
  at each change described above. This is because the bulletins do not
  change in this period of time and to reduce the frequent calls to the API,
  maybe playing with sound effects.
* Improved searching for updates; now once downloaded, it will be activated
  to its installation, or in the case of a portable version of nvda it will
  be opened the folder where you saved the update.
* Updated all sounds; now the sounds are in the wav format.

# Verzia 3.7 #

* Pridaná možnosť vypnúť pri vetre prepočet v metroch za sekundu.
* Pridaná možnosť používať mernú jednotku libra na palec štvorcový.
* Opravené 2 chyby.

# Verzia 3.6 #

* Changed the API service (application programming interface); now WP uses
  the service offered by OpenWeatherMap.org instead of Yahoo Weather.com.
* Do aktuálnej správy bola pridaná klasifikácia vetra.
* Do aktuálnej správy pridaná oblačnosť v percentách.
* V súčasnej správe boli prijaté jednotky na meranie tlaku v hektopascaloch.

# Zmeny v okne nastavenia Weather Plus #

* Changed insertion/search from yahoo zipcode/woeId in ID number, identifier
  of the city; ID numbers city are similar to woeid, but the woeId will no
  longer work, even the old zipcode. You will be able to rediscover a great
  part of the cities by typing the name or part of it.
* Pridané vloženie / hľadanie geografických súradníc.
* Pridané vkladanie / vyhľadávanie podľa poštového smerovacieho čísla.
* Vylepšená funkcia „podrobnosti“.
* Assigned to F1 key the entry/search help.
* Assigned to F4 key the controls to the forecasts from 1 to 16 days
  set. Attention, if you choose to copy to the clipboard a value greater
  than 10, it will not be read!
* Klávese F5 priradené ovládanie zvuku.
* Pridaná stupnica na meranie v Kelvinoch.
* Added check for updates; you can set the control by settings or check
  manually from menu.
* Reassigned the button "Find your city" in "Management of your API Key...";
  allows you to enter or change the key-API.

# Verzia 3.5 #

* Pridaný preklad do Chorvátčiny (vďaka Gordanovi Radičović).
* Added control for no longer valid WoeId and Zip Code found in the network;
  there have been reports of codes that have stopped working from one day to
  another, WP now warns if one of these has been inserted from the windows
  of search on the net. If this occurs using the function "Find your
  city...", please report it to me so that I can update the Weather_buffer
  and remove them from the list.
* Opravená chyba kódovania vo funkcii vyhľadávania.
* Updated the window to set one temporary zip code; added feature "Find" As
  in the other windows of Weather Plus: Control+F3 = Find..., F3 = Find
  next, Shift+F3 = Find previous.

# Verzia 3.4 #

* Pridaný preklad do Galicijčiny (vďaka Ivánovi Novegilovi).
* Pridaný preklad do Portugalčiny (vďaka Ângelovi Miguelovi Abrantesovi).
* Pridaný preklad do Nemčiny (neúplný).

# Verzia 3.3 #

* Pridané meranie rýchlosti vetra v metroch za sekundu.
* Encoding fixes.

# Verzia 3.2 #

* Updated the reading of the weather forecast, current weather report and
  reading of the date of the current weather report; Yahoo weather forecast,
  from a bit of time and in random amounts, allows it to pass a historic
  from -10 to -5 days of weather forecast to be inserted between the updated
  data that we want to read; it was added a filter that allows you to read
  only the last weather data updated, and a discreet beep alerts when it
  intervenes; this beep, if you want, can be disabled by using a checkbox by
  Weather Plus settings. Obviously, the filtering of data sometimes involves
  a short delay in reply, but is still acceptable.
* Predpovede sa časovo predĺžili na 10 dní.

# Verzia 3.1 #

* Added translation in Serbian (thanks to the kind cooperation of Dejan
  Gasic).
* Fixed command insert+alt+w; it did not check the validity of the zipcode
  in use and did not check if the connection was active as the other
  commands do.
* Updated the playback function of sound effects; mp3 format is now
  used. Now the files will be much smaller.
* Added 55 new sound effects; it will be necessary to update them from the
  settings of the plugin.

# Zmeny v okne nastavenia Weather Plus #

* Fixed display help on the buttons; now disables / enables real-time
  through the appropriate checkbox.
* Pridané 3 skratkové príkazy na rýchlejšiu navigáciu v okne:
* F1 skočí do zoznamu a do editačného poľa s PSČ.
* F2 sa vráti na posledný výber dosiahnutý pomocou TAB.
* F3 skočí na ovládanie hlasitosti (ak sú zvukové efekty nainštalované a
  aktivované).
* Added shortcut commands for all checkboxes and buttons; omitted the two
  radio buttons as they are present in succession and the first is reachable
  with the command control+shift+w.
* Zmenené, tlačidlo "definovať" je teraz deaktivované, ak zvukové efekty nie
  sú nainštalované a aktivované.
* Added volume controls; you can adjust the overall volume and the last
  heard sound effect; this option is enabled if the sound effects are
  installed and activated.
* Pridaná možnosť nastaviť systémový čas v 12-hodinovom formáte (12:30 AM
  `-` 12:30 PM) , alebo 24-hodinovom formáte (12:30 `-` 00:30).

# Verzia 3.0 #

* Added the Slovak translation (thanks to the kind cooperation of Vitek
  Jirasek).
* Pridaný preklad do brazilskej portugalčiny a európskej portugalčiny (vďaka
  láskavej spolupráci Adaira Knaesela).
* Pridané nové reťazce do zoznamu weather reports.
* Pridaných 171 nových zvukových efektov, teraz je konečný počet 213.
* Pridaná klávesová skratka insert+alt+w v gestách pre ohlásenie poslednej
  aktualizácie súčasnej správy o počasí.
* Pridaný scriptCategory, ktorý posunie skratkové klávesy doplnku Weather
  Plus na správnu pozíciu (vo vstupných príkazoch)...

# Zmeny v okne nastavenia Weather Plus #

* Pridaný prepínač na nastavenie spôsobu oznamovania teplotnej stupnice;
* Na výber je:
* Celsius `-` Fahrenheit
* C `-` F
* Žiadna indikácia
* Added button "Define"; it permits to define the zone of one city between:
* Vnútrozemie
* Prímorská oblasť
* Púštna zóna
* Arktická zóna
* Horská zóna
* The choice will consent to Weather Plus to use more appropriate sound
  effects for every single city; this is the reason for the boost of the
  number of new sound effects in this version of the addon; many of the new
  sound effects I got them from Tapin, whom I thank sincerely.

# Verzia 2.9 #

* Pridaná možnosť zvolenia obsahu súboru, z ktorého sa importujú kódy mesta.
* Boly pridané štyri nové zvukové efekty.
* Pridaný preklad do ruštiny (vďaka Alexejovi Ješhanovi).
* Pridaný preklad do češtiny (vďaka Jiřimu Holzingerovi).

# Verzia 2.8 #

* Opravená chyba v detailoch pri otvorení okna s výskytmi pri hľadaní mesta.
* Fixed regexp to search for the altitude; it did not accept parameters of
  single digits.
* Improved parser of the edit box; it should find more easily the city.
* Connections now handled by urllib2, instead of urllib; this should allow
  the functioning of the addon even on a computer connected to the corporate
  network protected by proxy.
* Pridaná funkcia „Nájsť“; Control + F3 = Nájsť ..., F3 = Nájsť ďalšie,
  Shift + F3 = Nájsť predchádzajúce.

# Verzia 2.7 #

* Fixed wrong name of a string "Motorcycle" in "Motorcycle00"; he asked
  updated sound effects because they could not find the file.
* Added ability to read about wind; direction, speed and temperature of the
  wind.
* Added ability to read atmospherical information; humidity, visibility,
  pressure and state of the barometric pressure.
* Added ability to read the Astronomic information; time of sunrise and
  sunset.

# Zmeny v okne nastavenia Weather Plus #

* Added 3 checkboxes to manage their information listed above.
* Added button "Details"; provides some information such as the real name of
  the city (assigned by Yahoo Weather Forecast), the state / region and the
  nation to which it belongs; with geographic coordinates, and height above
  sea level.
* Pridané rozpoznávanie WoeID (lokalizačné kódy, napr. Bologna, zodpovedá
  711080).
* Teraz môžete zadať názov mesta. V tomto prípade, ak sú nejaké výskyty,
  budú uvedené a budete si môcť vybrať.

# Verzia 2.6 #

* The functions of the buttons "Add" and "Remove" were optimized in the zip
  code's list management; now the operation are a lot more fast!
* Funkcia tlačidla „Testovanie“ bola optimalizovaná, teraz využíva až 13
  prehľadávacich kláves; Ak sa nenájde názov mesta, je to skutočne smola!
* The function of the button "Find your city...", now finds more countries;
  it was added an automatic test that collects the functioning zip codes,
  and it further consents a rapid visualization thanks to the creation of a
  little buffer corresponding to the name of the specific country.
* Three new sounds effects were added; it will be necessary to update them
  from the settings of the plugin.

# Verzia 2.5 #

* Pridaná klávesová skratka na prepínanie medzi jednotkami teploty
  Fahrenheit a Celzius, teploty je tiež možné prepínať i v nastaveniach.
* Opravená chyba, keď používateľ pridal mesto do zoznamu či obľúbených a to
  už bolo zaradené, program však neohlásil, že už tam je.
* Pridané nové reťazce do zoznamu weather reports.

# Zmeny v okne nastavenia Weather Plus #

* Pridané tlačidlo na otvorenie webovej stránky pre hľadania kódov miest pre
  rôzne krajiny a mestá.
* Pridaná možnosť importu /exportu kódov miest.
* Pridaná možnosť skopírovania ohlásenej predpovede do schránky.
* Pridaná možnosť inštalácie, počúvania a odinštalácie zvukových efektov.
* Pridaná možnosť nápovedy do okna s kódmi miest.
* Zmenený režim zobrazenia okna, menu NVDA je neobmädzené, keď je otvorené.

# Verzia 2.4.4 #

* Pridané 2 nové reťazce do zoznamu správ o oznamovaní počasia.
* Pridané preklady do španielčiny a francúzštiny vďaka Pablovi Vargasovi a
  Rémymu Ruizovi)

# Verzia 2.4.3 #

* Pridaná predpoveď počasia na 4 dni dopredu
* Pridanie reťazcov pre ohlasovanie počasia
* Zoznam s dočasnými kódmi miest je vždy zoradený po pridaní nového

# Verzia 2.4 #

* Opravená chyba, kedy nešlo uložiť mesto kvôli špeciálnym znakom.

# Verzia 2.3 #
* Odstránené dialógové okno pre nastavenie rozsahu merania teploty, teraz
  bol pridaný nový gui, ktorý vám umožní nastaviť všetko v jednom okne.
* Je možné pridávať, testovať, vymazávať a pridávať do obľúbených ako
  predvolené kódy miest
* Upravené dialógové okno pre zadanie napísaných Zip Code, teraz v dočasnom
  režime umožňuje nastaviť Zip Code, ktoré predtým boli pridané do zoznamu v
  nastaveniach z ponuky.
* Teraz je možné čítať dokumentáciu v angličtine, ak nie je dostupná
  lokalizovaná dokumentácia.

# Verzia 2.2 #

* Opravená chyba, kedy nešlo otvoriť nápovedu v stabilných verziách NVDA

# Verzia 2.1 #

* Opravená chyba, kedy sa doplnok nekorektne zatváral a bránil tak
  aktualizácii položky NVDA v systémovom panely

# Verzia 2.0 #

* Presunuté menu Weather do menu nastavenia a opravené ukladanie dočasného
  mesta
* Correct input on the fly is no longer saved, so it is temporary; to call
  the city set in the preferences, press NVDA+control+f3.

# Verzia 1.9 #

* Added help entering functions.
* Added a new function for quick entry of Zip Code.
* Added read / write configuration weather.ini, now no longer need to edit
  the source file.
* Pridané menu doplnku i do menu NVDA v oznamovacej oblasti.
* Added setting submenu Zip Code .
* Added sub-setting temperature scale (Fahrenheit or Celsius).
* Added menu Documentation.
* Pridaný preklad taliančiny.

# Počiatočná verzia 1.1 #

* Updated the NVDA-addon.
* Bola pridaná podpora prekladu.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
