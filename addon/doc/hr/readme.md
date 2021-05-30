# Vremenska prognoza plus (Weather Plus) #

* Autor: Adriano Barbieri
* NVDA kompatibilnost: 2017.3 do 2019.3
* Preuzmi [stabilnu verziju][1]

# INFORMACIJE O VREMENSKOJ PROGNOZI PLUS: #

* Ovaj dodatak dodaje lokalnu temperaturu i prognozu za sljedećih 24 sata do
  9 dodatnih dana.
* Autorska prava (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Izdano pod GNU GPL (Opća javna licenca) v2
* Vremenska prognoza plus radi putem upotrebe i prisutnosti sljedećih
  usluga:
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# PRIMJENA: #

* Pritisni NVDA+w za trenutačnu temperaturu i vremenske uvjete.
* Pritisni NVDA+šift+W za 24-satnu prognozu i za prognozu do 9 dana.
* Pritisni NVDA+šift+kontrol+w za postavljanje privremenog grada.
* Pritisni NVDA+šift+kontrol+alt+w za otvaranje dijaloškog okvira s
  postavkama za Vremensku prognozu plus.
* Pritisni NVDA+alt+w za datum i vrijeme aktualiziranja izvještaja o
  vremenu.
* Pritisni kontrol+šift+w za mijenjanje između temperaturnih ljestvica u
  Fahrenheitovim stupnjevima, u Celzijevim stupnjevima i u kelvinima.

# Postavke za Vremensku prognozu plus: #

* Moraš postaviti dodatak „Vremenska prognoza plus” prije prve upotrebe! Idi u podizbornik „Postavke”, podizbornik postavki „Vremenske prognoze plus” i odaberi jednu od sljedećih opcija:
* Postavi i upravljaj gradovima … – Prikazuje ili dopušta postavljanje trenutačnog grada s popisa.
* Dokumentacija – Otvara datoteku pomoći za trenutačni jezik.
* Provjeri nadogradnje … – Obavijest o novijoj verziji.

Za dodavanje novog grada: pritisni sljedeću stavku:

* Postavi i upravljaj gradovima … – Prikazuje ili dozvoljava postavljanje
  trenutačnog grada s popisa.
* Sljedeće poruke se prikazuju samo za prvi put! Unaprijed određene postavke
  Ništa F1: pomoć za određivanje mjesta, F2: zadnji odabir pomoću
  tabulatora, F3: popisni okvir i okvir za uređivanje, F4: odredi trajanje
  Vremenske prognoze, F5: kontrole za glasnoću.
* U okviru za uređivanje upiši grad, WOEID oznaku ili odaberi grad s popisa,
  ako postoji. Napomena: Tipka F5 je dostupna, ako su zvučni efekti
  aktivirani.
* Nakon pritiskanja stavke „Postavi i upravljaj gradovima …”, naći ćeš
  sljedeće gumbe:
* Provjeri – Provjerava ispravnosti zapisa woeID oznake i nalazi njemu
  dodijeljeno ime ili obrnuto.
* Dodaj – Dodaje trenutačni grad u popis. Ovaj se gumb može aktivirati, ako
  u popisu odabereš grad, kad je upisani grad prošao test.
* Detalji – Prikazuje informacije o trenutačnom gradu. Ovaj se gumb
  aktivira, ako u popisu odabereš grad ili ako je grad prošao test.
* Odredi – Dozvoljava odrediti područje, kako bi se prilagodili zvučni
  efekti. Ovaj se gumb može aktivirati, ako su zvučni efekti instalirani i
  aktivirani i ako iz popisa odabereš grad.
* Preodredi – Predodređuje grad kao standardni, koristit će se svaki put,
  kad se dodatak ponovo pokrene. Ovaj se gumb aktivira, ako u popisu
  odabereš prethodno umetnuti grad, a nije predodređen ili ako je prošao
  test.
* Ukloni – Uklanja trenutačni grad s popisa. Ovaj se gumb može aktivirati,
  ako u popisu odabereš prethodno umetnuti grad.
* Preimenuj – Preimenuj trenutačni grad. Ovaj se gumb može aktivirati, ako u
  popisu odabereš prethodno umetnuti grad.
* Uvezi nove gradove … – Ovaj gumb dozvoljava uvoz novih gradova iz drugog
  popisa gradova s nastavkom *.zipcodes. Možeš odabrati grad koji želiš
  uvesti, označavanjem odgovarajućeg potvrdnog okvira.
* Izvezi gradove … – Dozvoljava spremanje gradova u određenu datoteku s
  nastavkom *.zipcodes. Ovaj se gumb aktivira, ako se u popis doda i spremi
  barem jedan grad.
* Temperaturna ljestvica: Koristi odabirni gumb za biranje između Celzijevih
  stupnjeva (standardno), Fahrenheitovih stupnjeva i kelvina.
* Stupnjevi prikazani kao: Koristi odabirni gumb za biranje između: Celzija
  `-` Fahrenheita `-` Kelvina (standardno) C `-` F `-` K ili neodređeno.
* Odabirni okvir: Vremenska prognoza do dana: 3; odaberi između 1 do 10
  (standardno je postavljeno na 3 dana)
* Za izvršavanje sljedećih radnji uključi ili isključi sljedeće potvrdne
  okvire:
* Kopiraj izvještaj o vremenu i vremensku prognozu, uključujući podatke o
  gradu u međuspremnik; potvrdni okvir standardno nije označen.
* Aktiviraj zvučne efekte (samo za trenutačne vremenske uvjete). Ovaj
  potvrdni okvir također omogućuje upravljanje instalacijom zvučnih
  efekata. Ako su zvučni efekti instalirani i ako je potvrdni okvir
  aktiviran, tipka F5 i postavka glasnoće postaju dostupni.
* Također će biti dostupan dodatni potvrdni okvir: Koristi samo vremenske
  efekte.
* Moguće je promijeniti ukupnu glasnoću ili promijeniti zadnje korišteni
  zvučni efekt, kao i izdvojiti ostale zvukove vlastitog okruženja. Potvrdni
  okvir standardno nije označen.
* Koristi samo vremenske efekte – Ova je opcija dostupna, ako su zvučni
  efekti aktivirani. Ako je opcija aktivirana, omogućuje preslušavanje samo
  vremenskih efekata poput kiše, vjetra, grmljavine itd., isključujući pri
  tome sve okolišne efekte. (standardno nije označeno)
* Aktiviraj čitanje sata u 24-satnom formatu – Ako potvrdni okvir nije
  označen, najavljuje sate u 12-satnom formatu, npr. 12 AM `-` 12
  PM. Potvrdni okvir je standardno označen.
* Aktiviraj gumbe pomoći u prozoru postavki; otvrdni okvir je standardno
  označen.
* Pročitaj informacije o vjetru; potvrdni okvir standardno nije označen. Ako
  je označen, možeš aktivirati i sljedeće potvrdne okvire:
* Dodaj smjer vjetra; ukazuje na smjer iz kojeg vjetar dolazi. Potvrdni
  okvir je standardno označen.
* Dodaj brzinu vjetra; ukazuje na brzinu u kilometrima na sat ili u miljama
  na sat. Potvrdni okvir je standardno označen.
* Dodaj brzinu vjetra u metrima po sekundi; potvrdni okvir je standardno
  označen.
* Dodaj osjetnu temperaturu; potvrdni okvir je standardno označen.
* Pročitaj informacije o atmosferi; potvrdni okvir standardno nije
  označen. Ako je označen, možeš aktivirati i sljedeće potvrdne okvire:
* Dodaj vrijednost za vlagu; ukazuje na vlagu u postocima. Potvrdni okvir je
  standardno označen.
* Dodaj vrijednost za vidljivost; ukazuje na vidljivost u kilometrima ili
  miljama. Potvrdni okvir je standardno označen.
* Dodaj vrijednost za atmosferski tlak; ukazuje ne atmosferski tlak u
  milimetrima ili inčima žive. Ako je označeno, uključuje dodatni potvrdni
  okvir za označavanje tlaka u milimetrima žive. Potvrdni okvir je
  standardno označen.
* Dodaj stanje barometra; potvrdni okvir je standardno označen.
* Pročitaj informacije o astronomiji; ukazuje na vrijeme izlaska i zalaska
  sunca. Potvrdni okvir standardno nije označen.
* Koristi decimalni zarez; ako je uključeno, koristit će se decimalni zarez
  umjesto točke. Potvrdni okvir standardno nije označen.
* Provjeri nadogradnje; ako je aktivirano, upozorava o novoj verziji
  dodatka. Potvrdni okvir je standardno označen.
* Potvrdi pritiskom gumba „U redu” ili prekini pritiskom gumba „Odustani”.
* Ako promijeniš popis gradova, pritiskom gumba „Odustani”, dodatak te o
  tome obavještava, te ćeš popis još uvijek moći spremiti. Napomena: tvoje
  će se postavke spremiti u datoteku s imenom:
* „Weather.ini”: postavke za pokretanje Vremenske prognoze plus.
* „Weather.volumes”: prilagođene razine glasnoće, neovisno o ukupnoj
  glasnoći.
* „Weather.zipcodes”: popis gradova s poštanskim brojevima i definicijama.
* „Weather_searchkey”: tipka za pretraživanje spremljena.

--------------------------------------------------------------------------------

# Što je novo: #

# Verzija 7.4 #

* Ispravljena je greška u funkciji za traženje grada.

# Verzija 7.3 #

* Ispravljena je neočekivana greška u slučaju upozorenja, da stranica nije
  pronađena, tijekom pretraživanja nadogradnji.

# Verzija 7.2 #

* Ispravljena je greška nakon dodavanja grada, ako se radi o prvom upisanom
  gradu, ako pritisneš gumb „U redu” i ponovo pokreneš dodatak.
* Dijaloški okvir za napredak sada ponovno pokazuje preostalo vrijeme i
  proteklo vrijeme.
* Ispravljen prijevod za talijanski u pomoći gumba „Preimenuj”.

# Version 7.1 #

* Fixed update bug.

# Version 7.0 #

* Improved search window, now it is possible to manage all the search key
  inserted, add, delete and save it from context menu.
* Improved window opening control.
* Some little bugs fixed.

# Version 6.9 #

* Implemented the recursive cities search with the valid system previously
  used in Weather_Plus Apixu version.
* Press f1 in the settings window for an explanation of the available
  commands.

# Version 6.8 #

* Aktualizirana kompatibilnost s Python 3.

# Version 6.7 #

* Fixed a bug when it is tested a new city and using it in temporary mode by
  simply press "enter" and at a later time trying to add it via the "Add"
  button.
* Added abbreviation for SOUTH GEORGIA AND THE SOUTH SANDWICH ISLANDS to the
  database, but unfortunately at the moment it seems that the cities of this
  state do not work or have incomplete data, we hope it will be solved soon.

# Version 6.5 #

* Fixed a couple of bugs in sound effects reproduction; a couple of "for"
  cycles with incorrect maximum values caused the call to a non-existent
  sound effect.
* Fixed bug in local time in "details"; 12-hour time conversion gave an
  error.
* Fixed a bug in the Yahoo Weather Forecast report; in some cities the
  forecasts start from the previous day and not from the current one. The
  correction of these cities entails the loss of the last days of forecast
  proportionate to the mismatch of dates (if the forecast days are set to
  10).

# Version 6.4 #

* Daylight saving time removed in the "Details" function.
* Poboljšana reprodukcija zvučnih efekata; sad se redovito aktualiziraju,
  ako se promijene vremenski uvjeti.

# Version 6.3 #

* Fixed encoding issues.

# Version 6.2 #

* Fixed bug in the "Add city" function.
* Fixed bug that did not assign the variable "_volume" when starting the
  addon.
* Added missing code from version 6.0; now you can recover the saved cities
  from the version that uses the Apixu API; the "Test" and "Remove" buttons
  and non-compatible cities are available in the format: "Ferrara, iter
  44.83,11.58 0" (city, geographic coordinates, area definition).

# Version 6.1 #

* Fixed 2 bugs.

# Version 6.0 #

* Vremenska prognoza plus ponovo koristi Yahoo Weather API.
* Virtually all the features of the previous version 4.8 are back and keeps
  the "Rename" button.
* Kompatibilnost s Python 3.

# Version 5.0.1 #

* Fixed bug, that returned an empty string if the wind speed in mph was 0.
* Fixed bug that caused sound effects not consistent with the time zone to
  be reproduced.
* Adjusted the number of forecast days from 9 to 6 in readme.

# Version 5.0 #

* Vremenska prognoza plus sada koristi APIXU API.

# Promjene u prozoru postavki Vremenske prognoze plus #

* Uklonjen stari potvrdni okvir za „Stanje barometra”. Zamijenjen novim
  potvrdnim okvirom „Dodaj vrijednost za oblačnost”;
* Daje postotak oblačnosti.
* Added new checkbox "Add precipitation value". It gives you the amount in
  millimeters of precipitation.
* Removed old checkbox "Indicates the wait with a beep while you search for
  the latest bulletin"; left active by default.
* Dodane su informacije o astronomiji;
* Vrijeme izlaska i zalaska mjeseca.
* Dodan gumb „Preimenuj”; za jednostavnije preimenovanje gradova.
* Improved function of the "Test" button; now accept some commands to
  facilitate the search for cities; these new commands are described in the
  help function that can be called up with F1.

# Version 4.8 #

# Promjene u prozoru postavki Vremenske prognoze plus #

* Dodan novi potvrdni okvir; „Koristi samo vremenske efekte”; to omogućuje
  filtrirati okolišne efekte.
* Improved random playback and added 71 new sound effects; you will need to
  update them by clicking twice in "enable audio effects" checkbox.
* The volume type assigned by the user, between the general and current
  audio volume, is now maintained when the configuration is saved.
* Removed useless sound during selection text in edit box by pressing
  control+a.
* Improved readability into help window invokable with F1 function key.
* Added new compatibility flag for NVDA 2019.1, and the current alpha
  versions.

# Version 4.7.7 #

* Removed unnecessary notification of download complete when the update of
  Weather Plus.
* Added 6 new sound effects; it will be necessary to update them from the
  settings of the plugin.

# Version 4.7.6 #

* Bugfix release.

# Version 4.7.5 #

* Bugfix release.

# Version 4.7.3 #

* "Details" function was updated for convenience; the information about the
  altitude are now provided by veloroutes.org. This leads to small
  differences of little relevance.

# Version 4.7.2 #

* Fixed small encoding bug.

# Version 4.7.1 #

* Fixed bug when getting the information about the time zone.

# Version 4.7 #

* Simplified the update section; now at the start, in case an update is
  available it will be possible to proceed directly through a single dialog
  box.
* Removed the file selector in the update section; now the update file is
  saved to the temporary folder, it open the possibility to install the
  update automatically, good for beginners.

# Version 4.6.9 #

* Dodan prijevod za arapski (hvala Wafik Immaculate).

# Version 4.6.8 #

* Updated localizations for Brazilian Portuguese and European Portuguese
  localizations (thanks to Alberto Mendonça).

# Version 4.6.7 #

* Improved the reading of the current time; in some cities, it was not
  correct. Added daylight saving time to the details; available only for the
  countries that adopt it.

# Version 4.6.5 #

* Fixed small bug when reading the time.

# Version 4.6.4 #

* Improved the reading of current local time; search keys are more accurate.

# Version 4.6.2 #

* Fixed bug: after a check for updates, the "set a temporary city..." menu
  was enabled even if there was no available list of cities.
* Fixed bug; unable to configure WP when the weather.ini has not been
  created yet,.

# Version 4.6 #

* Added the menu item "Set a temporary city..."; for the sake of
  completeness, now you can open the temporary city's list also from the
  menu.
* Improved management of temperature scale; now the settings window will
  always return the default value.
* Improved prevention of the multiple opening of the main windows; if one of
  these is already opened, in addition to the sound alert, puts it in
  foreground.
* Poboljšana reprodukcija zvučnih efekata; sada se redovito aktualiziraju,
  ako se promijene vremenski uvjeti.

# Promjene u funkciji gumb za detalje u prozoru postavki #

* Dodano trenutačno lokalno vrijeme.
* Fixed altitude value; now return the altitude values when the value is
  less than or equal to zero.

# Version 4.5.5 #

* Correct localization and documentation in Serbian.
* Ispravljen prijevod za njemački.

# Promjene u prozoru postavki Vremenske prognoze plus #

* Dodan novi potvrdni okvir; ,ožeš aktivirati zarez kao decimalnu oznaku,
  inače će se koristit točka.

# Version 4.5.3 #

* Ispravljena su dva izraza za ruski i ukrajinski jezik.
* Ispravljen je naslov u prozoru za „Provjeri nadogradnje”.
* Improved update algorithm.

# Verzija 4.5 #

* Dodan prečac NVDA+šift+kontrol+alt+w; otvara dijaloški okvir s postavkama
  za Vremensku prognozu plus.
* Ispravljeni neki engleski izrazi.

# Promjene u prozoru postavki Vremenske prognoze plus #

* Dodano je osam novih potvrdnih okvira. Sad je moguće još više prilagoditi
  čitanje:
* Smjer vjetra.
* Brzina vjetra.
* Osjetna temperatura.
* Vrijednost za vlagu.
* Vrijednost za vidljivost.
* Atmosferski tlak.
* Ukazuje na atmosferski tlak u milimetrima žive (mmHg).
* Stanje barometra.

# Verzija 4.4.8 #

* Dodan prijevod za poljski (hvala Zvonimir Staneczyć).
* Kompatibilnost s wx python verzijom 4.

# Verzija 4.4.1 #

* Dodana je SSL podrška.

# Verzija 4.4 #

* Ispravljena greška u čitanju nove verzije pri isteklom vremenu veze.
* Poboljšan odjeljak za nadogradnje. Dijaloški okvir se ne miješa s NVDA
  izbornikom.
* Revidiran i ispravljen prijevod za ruski.
* Dodan prijevod za ukrajinski (hvala Alex Yeshanu).

# Verzija 4.3.4 #

* Revidiran i ispravljen prijevod za njemački.

# Verzija 4.3.3 #

* Dodan prijevod za njemački (hvala Karl Eick).

# Verzija 4.3.2 #

* Dodan prijevod za rumunjski (hvala Florian Ionașcu).

# Version 4.3.1 #

* Fixed a minor bug in the function "details"; the strings "latitude" and
  "longitude" were reversed compared to the value.

# Version 4.3 #

* Weather Plus moved to the "nvda.it" as it's default hosting provider.

# Version 4.2.4 #

* Fixed a minor bug when the connection was not active.

# Version 4.2.3 #

* Now Weather Plus is able to run some connection attempts before notifying
  the malfunction of the WoeId in use, it emits a beep at each attempt; this
  beep, if you want, can be disabled by using a checkbox by Weather Plus
  settings.

# Version 4.2.2 #

* Fixed bug in the translation strings for the scale measurement. In some
  languages, Kelvin, Celsius and Fahrenheit have not been translated.

# Version 4.2.1 #

* Fixed update notice of Weather Plus during the Windows start-up; this
  happens when the button was pressed "Use currently saved settings on the
  logon and other secure screens (requires administrator privileges)" from
  the general settings of nvda, which copies the configuration, and all of
  the add-on folder systemConfig, but these are not synchronized with
  subsequent updates of the add-ons. If you have ever used at least once
  this option, you will have to do it again one last time just after to have
  up-to-date Weather Plus.

# Version 4.2 #

* Added 5 new sound effects; it will be necessary to update them from the
  settings of the plugin.
* Fixed bug in the import function; the list of cities was not sorted
  alphabetically.
* Added import mode in the import function; you may decide to completely
  replace your own list, or simply add new cities to it.
* Updated the reading of the weather forecast, current weather report;
  adding the perceived temperature (wind chill).
* Added new strings to the list weather reports.

# Version 4.1 #

* Fixed bug in the forecast for up to 10 days; now if the estimates received
  are in number less than the request of the user, the missing days are
  indicated as unknown.
* Fixed string help entry on the command nvda+shift+w.
* Revidirana i ispravljena dokumentacija.

# Version 4.0 #

* Updated some parts of code and replaced all instructions eval().

# Version 3.9.7 #

* Fixed bug during the reading of weather forecasts; now the temperatures
  are read correctly.

# Version 3.9.6 #

* Changed the rounding in the conversion of atmospheric pressure from mbar
  in inches of mercury; now the value is calculated in defect, while before
  it was in excess.

# Version 3.9.5 #

* Added 2 new strings to the list weather reports.
* Fixed 2 bugs.
* Updated running sounds for the effect in conditions of only wind; now the
  sound of the wind can vary randomly.

# Version 3.9.4 #

* Documentations, localizations for Croatian and German language were
  removed; because they are no longer supported by the respective
  translators.
* Ispravljena je greška u prijevodu za srpski.
* Updated Czech localization.
* Updated documentation and localization for Galician.

# Version 3.9 #

* Changed again API service; Weather Plus now uses the new Yahoo Weather API
  with language Yahoo!Query and JQuery:
* The api key is no longer required.
* Restored The search of the homonymous cities; it will be possible to
  choose exactly the desired city from a list.
* Optimized the output of general sounds; now they are synchronized with the
  voice synthesis and are faster.
* Improved the cache for data off-line; is zeroed every 10 minutes or only
  by changing the city.
* Barometric pressure measured in mbar, or in inches of mercury (if set to
  Fahrenheit).

# Version 3.8 #

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

# Version 3.7 #

* Dodana je mogućnost za deaktiviranje pretvaranja metara u sekundi vjetra.
* Added possibility to use units of measure in pounds per square inch.
* Fixed 2 bugs.

# Version 3.6 #

* Changed the API service (application programming interface); now WP uses
  the service offered by OpenWeatherMap.org instead of Yahoo Weather.com.
* Added Wind classification in the current bulletin.
* Added a cloudiness percentage in the current bulletin.
* Adopted the units of pressure measurement in hectopascal in the current
  bulletin.

# Promjene u prozoru postavki Vremenske prognoze plus #

* Changed insertion/search from yahoo zipcode/woeId in ID number, identifier
  of the city; ID numbers city are similar to woeid, but the woeId will no
  longer work, even the old zipcode. You will be able to rediscover a great
  part of the cities by typing the name or part of it.
* Added insertion/Search for geographical coordinates.
* Added insertion/search by postal code.
* Improved the function "details".
* Assigned to F1 key the entry/search help.
* Assigned to F4 key the controls to the forecasts from 1 to 16 days
  set. Attention, if you choose to copy to the clipboard a value greater
  than 10, it will not be read!
* Assigned F5 key for audio controls.
* Adding measurement scale degrees Kelvin.
* Added check for updates; you can set the control by settings or check
  manually from menu.
* Reassigned the button "Find your city" in "Management of your API Key...";
  allows you to enter or change the key-API.

# Version 3.5 #

* Dodan prijevod za hrvatski (hvala Gordan Radić).
* Added control for no longer valid WoeId and Zip Code found in the network;
  there have been reports of codes that have stopped working from one day to
  another, WP now warns if one of these has been inserted from the windows
  of search on the net. If this occurs using the function "Find your
  city...", please report it to me so that I can update the Weather_buffer
  and remove them from the list.
* Fixed encoding bug in the search functionality.
* Updated the window to set one temporary zip code; added feature "Find" As
  in the other windows of Weather Plus: Control+F3 = Find..., F3 = Find
  next, Shift+F3 = Find previous.

# Version 3.4 #

* Dodan prijevod za galicijski (hvala Iván Novegil).
* Dodan prijevod za portugalski (hvala Ângelo Miguel Abrantes).
* Dodan prijevod za njemački (nepotpun).

# Version 3.3 #

* Added the measure of the speed of wind in meters per second.
* Encoding fixes.

# Version 3.2 #

* Updated the reading of the weather forecast, current weather report and
  reading of the date of the current weather report; Yahoo weather forecast,
  from a bit of time and in random amounts, allows it to pass a historic
  from -10 to -5 days of weather forecast to be inserted between the updated
  data that we want to read; it was added a filter that allows you to read
  only the last weather data updated, and a discreet beep alerts when it
  intervenes; this beep, if you want, can be disabled by using a checkbox by
  Weather Plus settings. Obviously, the filtering of data sometimes involves
  a short delay in reply, but is still acceptable.
* Forecasts of the time extended to 10 days.

# Version 3.1 #

* Dodan prijevod za srpski (hvala Dejan Gašić na suradnji).
* Fixed command insert+alt+w; it did not check the validity of the zipcode
  in use and did not check if the connection was active as the other
  commands do.
* Updated the playback function of sound effects; mp3 format is now
  used. Now the files will be much smaller.
* Added 55 new sound effects; it will be necessary to update them from the
  settings of the plugin.

# Promjene u prozoru postavki Vremenske prognoze plus #

* Fixed display help on the buttons; now disables / enables real-time
  through the appropriate checkbox.
* Added 3 shortcut commands to navigate more quickly in the window:
* Tikpom F1 skače u popisni okvir i okvir za uređivanje poštanskog broja.
* Tikpom F2 vraća na zadnji odabir urađen tabulatorom.
* Tikpom F3 skače u kontrole za glasnoću (ako su zvučni efekti instalirani i
  aktivirani).
* Added shortcut commands for all checkboxes and buttons; omitted the two
  radio buttons as they are present in succession and the first is reachable
  with the command control+shift+w.
* Promjena: gumb „Odredi” je sada deaktiviran, ako zvučni efekti nisu
  instalirani i aktivirani.
* Dodane su kontrole za glasnoću; možeš podesiti ukupnu glasnoću i
  posljednji zvučni efekt; ova je opcija aktivirana, ako su zvučni efekti
  instalirani i aktivirani.
* Added ability to set the system time in 12-hour format (12:30 AM `-` 12:30
  PM) , or the 24-hour system (12:30 `-` 00:30).

# Version 3.0 #

* Dodan prijevod za slovački (hvala Vitek Jirasek na suradnji).
* Dodan prijevod za portugalski za Brazil i portugalski za Portugal (hvala
  Adair Knaesel na suradnji).
* Added new strings to the list weather reports.
* Added 171 new sound effects, now the total amount is 213.
* Added command insert+alt+w in the gesture to announce last update of
  current bulletin.
* Added scriptCategory which shifts in the correct position the rapid keys
  of Weather Plus in "Input gestures..."

# Promjene u prozoru postavki Vremenske prognoze plus #

* Added radio button to set how to indicate the temperature scale;
* Moguće je birati između:
* Celzija `-` Fahrenheita
* C `-` F
* Bez nagovještaja
* Added button "Define"; it permits to define the zone of one city between:
* Hinterland
* Maritime area
* Desert zone
* Arctic zone
* Mountain zone
* The choice will consent to Weather Plus to use more appropriate sound
  effects for every single city; this is the reason for the boost of the
  number of new sound effects in this version of the addon; many of the new
  sound effects I got them from Tapin, whom I thank sincerely.

# Version 2.9 #

* Added option when importing to select the contents of the imported file.
* Four new sounds effects were added.
* Dodan prijevod za ruski (hvala Alex Yeshanu).
* Dodan prijevod za češki (hvala Jirimu Holzingerovi).

# Version 2.8 #

* Fixed bug in "details", it used to open the window of the occurrences when
  he could not find the city.
* Fixed regexp to search for the altitude; it did not accept parameters of
  single digits.
* Improved parser of the edit box; it should find more easily the city.
* Connections now handled by urllib2, instead of urllib; this should allow
  the functioning of the addon even on a computer connected to the corporate
  network protected by proxy.
* Added feature "Find"; Control+F3 = Find..., F3 = Find next, Shift+F3 =
  Find previous.

# Version 2.7 #

* Fixed wrong name of a string "Motorcycle" in "Motorcycle00"; he asked
  updated sound effects because they could not find the file.
* Dodana je mogućnost za čitanje podataka o vjetru; smjer, brzina i
  temperatura vjetra.
* Added ability to read atmospherical information; humidity, visibility,
  pressure and state of the barometric pressure.
* Dodana mogućnost čitanja informacija o astronomiji; vrijeme izlaska i
  zalaska sunca.

# Promjene u prozoru postavki Vremenske prognoze plus #

* Added 3 checkboxes to manage their information listed above.
* Added button "Details"; provides some information such as the real name of
  the city (assigned by Yahoo Weather Forecast), the state / region and the
  nation to which it belongs; with geographic coordinates, and height above
  sea level.
* Added recognition of WoeID (location codes, eg. Bologna it corresponds to
  711080).
* Now you can type the name of the city, in this case, if any, the
  occurrences will be listed and you will be able to choose.

# Version 2.6 #

* The functions of the buttons "Add" and "Remove" were optimized in the zip
  code's list management; now the operation are a lot more fast!
* The function of the button "Test" was optimized, now it exploits until 13
  research keys; Now if it doesn't find the name of the city it is a real
  bad luck!
* The function of the button "Find your city...", now finds more countries;
  it was added an automatic test that collects the functioning zip codes,
  and it further consents a rapid visualization thanks to the creation of a
  little buffer corresponding to the name of the specific country.
* Three new sounds effects were added; it will be necessary to update them
  from the settings of the plugin.

# Version 2.5 #

* Added command in the gesture to switch temporarily the temperature scale
  from Celsius to Fahrenheit, the command is also effective in the settings
  window.
* Fixed bug, if the user did not press the "Add" or "Preset" buttons, it did
  not allow to vocalize the name of the city since it was not included in
  the list.
* Added new strings to the list weather reports.

# Promjene u prozoru postavki Vremenske prognoze plus #

* Added button to open a research web page in order to check for the
  world-wide Zip Codes.
* Added the possibility to import / export the Zip Codes from friends.
* Dodana je mogućnost za kopiranje izvještaja o vremenu ili vremenske
  prognoze u međuspremnik.
* Added possibility to listen to the meteorological audio effects, the
  option also allows the installation / upgrade of the audio effects.
* Added ability help buttons on the management of Zip Code.
* Change to the display mode of the window, the menus of nvda are
  unrestrained when it is open.

# Version 2.4.4 #

* Added 2 new strings to the list weather reports.
* Dodan prijevod za španjolski i francuski (hvala Pablo Vargas i Rémy Ruiz).

# Version 2.4.3 #

* Adding up the weather forecast for the next 4 days.
* Adding a string to the list weather report.
* The list of temporary zipcode is now ordered to each new insertion.

# Version 2.4 #

* Fixed a bug that prevented to save and manage properly the city names
  containing accented vowels.

# Version 2.3 #
* Eliminated dialog box to set the scale of temperature measurement, has now
  been added a new gui that allows you to set all in one window.
* You will then also possible to test / add / delete / preset as the default
  Zip Code collected as a list.
* Modified the dialog box for entering typed a Zip Code, now in temporary
  mode allows you to set a Zip Code previously added to the list in
  Preferences from the menu.
* Now the documentation can be read in English if the language setting is
  not included in the documents.

# Version 2.2 #

* Fixed bug that did not allow you to open the documentation for the
  definitive versions of NVDA.

# Version 2.1 #

* Fixed a bug that did not close properly the plugin, this prevented the
  NVDAupdate the icon in the system tray.

# Version 2.0 #

* Izbornik postavki „Vremenske prognoze plus” premješten u podizbornik
  „Postavke”.
* Correct input on the fly is no longer saved, so it is temporary; to call
  the city set in the preferences, press NVDA+control+f3.

# Version 1.9 #

* Added help entering functions.
* Added a new function for quick entry of Zip Code.
* Added read / write configuration weather.ini, now no longer need to edit
  the source file.
* Dodan izbornik „Vrijeme” u programskoj traci.
* Added setting submenu Zip Code .
* Added sub-setting temperature scale (Fahrenheit or Celsius).
* Dodan je izbornik „Dokumentacija”.
* Dodan prijevod za talijanski.

# Prva verzija 1.1 #

* Aktualiziran je NVDA dodatak.
* Dodana podrška za prijevode.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
