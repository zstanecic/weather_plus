# Weather Plus #

* Autore: Adriano Barbieri
* Compatibilità con NVDA: dalla 2017.3 alla 2019.3
* Scarica: [versione stabile][1]

# A PROPOSITO DI WEATHER PLUS: #

* Questo plugin aggiunge temperatura locale e previsioni a 24 ore fino a
  ulteriori 9 giorni per NVDA.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Rilasciato sotto licenza GNU GPL (General Public License) v2

* Weather Plus funziona attraverso l'uso e la presenza dei seguenti servizi:
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# USAGE: #
* Press NVDA+w to get the information about current temperature and weather
  conditions.
* Press NVDA+shift+W to get 24 hours forecast and forecast up to 9 days.
* Press NVDA+shift+ctrl+w to set a temporary city.
* Premere NVDA + shift + control + alt + w per aprire la finestra
  impostazioni di Weather Plus.
* Press NVDA+alt+w to get the date and time, when the weather report was
  updated.
* Press control+shift+w to toggle between Fahrenheit, Celsius or Kelvin
  temperature scales.

# Weather Plus setup: #

* You must set the Weather Plus addon before its first use! Go to the
  Preferences submenu, Weather Plus Settings submenu and choose one of the
  following options:


* Set and Manage Your Cities... - Displays or allows to set the current city
  from a list.
* Documentation - opens the help file for the current language.
* Check for Update... - notifies about the availability of the new version.

To add a new city: press the following item:

* Set and Manage Your Cities... Displays or allows to set the current city
  from a list

* The following message is displayed only for the first time! Settings
  Preset None F1: help placing, F2: last TAB selection, F3: list and edit
  box, F4: control duration Weather Forecast, F5: volume controls.

* In the edit box, enter a City, woeID or choose one from the list, if
  available. Note: The F5 key is available if the sound effects are
  activated.

* After pressing enter on the item "Set and Manage Your Cities...", you will
  find other buttons as follows:

* Test - testing the validity of woeID entry and find the name of city
  assigned or vice versa.

* Add - adds the current city into your list. This button can be activated
  if you select a city from the list, when the city entered passed the test.

* Details - displays information about the current city. This button is
  activated if you select a city from the list, or it has passed the test.

* Define - Allows you to define the area, in order to adapt the sound
  effects. This button can be activated if the audio effects are installed
  and activated, and you select a city from the list.

* Preset - Presets a city as the default, will be used every time you
  restart the plugin. This button is activated if you select a city
  previously inserted in the list and not preset, or it has passed the test.

* Remove - Deletes the current city from your list. This button can be
  activated if you select a city previously inserted in the list.

* Rename - Rename the current city. This button can be activated if you
  select a city previously inserted in the list.

* Import new cities... - This button allows you to import cities from the
  another list of cities with the extension *.zipcodes; you can select the
  city you want to import, by turning on the check box associated with it.

* Export your cities... - It allows you to save the cities in the specified
  file with the extension *.zipcodes. This button is activated if you have
  added and saved at least one city into the list.

* Scale of temperature measurement: Use the radio button to select between
  Celsius (by default), Fahrenheit and Kelvin.

* Degrees shown as: Use the radio button to select between: Celsius `-`
  Fahrenheit `-` Kelvin (by default C `-` F `-` K or unspecified.

* Combo box: Weather Forecasts up to days: 3 You can choose between 1 to 10
  (3 days by default)

* To perform the following actions, toggle the following checkboxes:

* Copy the weather report and weather forecast, including city details to
  clipboard check box not checked (by default)

* Enable audio effects (only for the current weather conditions) This check
  box also allows you to manage the installation of sound effects; If the
  sound effects are installed and the check box is activated, the F5 key and
  the volume setting becomes available.

* There will also be available an additional check box: Use only weather
  effects.

* You can change the overall volume or change the last heard sound effect
  and filter out the others sounds in your environment. Checkbox is not
  checked by default.)

* Use only weather effects - This option is available if sound effects are
  enabled; If is enabled, allows to listen only weather effects such as
  rain, wind, thunder, etc., filtering out all environmental
  ones. (unchecked by default)

* Enable the reading of the hours in 24-hour format. - If this checkbox is
  unchecked, announces the time in 12-hour format for example, 12 AM `-` 12
  PM. check box is checked (by default)

* Enable help buttons in the settings window check box checked (by default)

* Read wind information check box not checked (by default) If this checkbox
  is enabled, you can also activate the following checkboxes:

* Add wind direction; Indicates the provenance of the wind. check box
  checked (by default)

* Add speed of the wind; Indicates the speed in kilometers or miles per
  hour. check box checked (by default)

* Add speed in meters per second of the wind; check box checked (by default)

* Add perceived temperature; check box checked (by default)

* Read atmospherical information check box not checked (by default) If
  enabled, you can also check the following checkboxes:

* Add humidity value; Indicates the humidity in percent. check box checked
  (by default)

* Add visibility value; Indicate in kilometres or miles the distance
  visible. check box checked (by default)

* Add atmospheric pressure value; Indicates the atmospheric pressure in
  millibars or inches of mercury. If it's checked, enable an additional
  check box that allows you to indicate the pressure in millimeters of
  mercury. check box checked (by default)

* Add status of barometric pressure; check box checked (by default)

* Read astronomical information Indicates the time of sunrise and
  sunset. check box not checked (by default)

* Use the comma to separate decimals If enabled, uses the comma as a decimal
  separator, otherwise, use the point. check box not checked (by default)

* Check for upgrade If is activated this alerts when there is an update of
  the addon. check box checked (by default)

* Premere il pulsante OK per confermare l'azione o il pulsante Annulla per
  annullare l'azione.

* If you have modified the cities list, by pressing "Cancel", you will be
  remembered and you can still save it Note: your settings will be save in
  the file named:

* "Weather.ini": impostazioni di avvio di Weather Plus.
* "Weather.volumes": livelli volume audio personalizzati, a prescindere dal
  volume generale.
* "Weather.zipcodes": lista delle città con rispettivi zip code e
  definizioni.
* "Weather_searchkey": chiavi di ricerca salvate.

--------------------------------------------------------------------------------

# Novità: #

# Versione 7.3 #
* Corretto bug imprevisto in caso di pagina non trovata durante la ricerca
  di aggiornamenti.

# Versione 7.2 #
* Fixed bug after adding a city, if it is the first one entered if you press
  ok button and restart the add-on.
* Now the progress dialog show again the time remaining and time elapsed.
* corretta traduzione in italiano dell'aiuto del pulsante Rinomina.

# Versione 7.1 #
* Fixed update bug.

# Versione 7.0 #
* Improved search window, now it is possible to manage all the search key
  inserted, add, delete and save it from context menu.
* Controllo dell'apertura delle finestre migliorato.
* corretti alcuni piccoli bug.

# Versione 6.9 #
* Implementata la ricerca di città ricorrenti tramite il sistema adottato in
  precedenza nella versione Apixu di Weather_Plus.
* Premere f1 nella finestra delle impostazioni per una spiegazione dei
  comandi disponibili.

# Versione 6.8 #
* Updated compatibility for Python 3

# Versione 6.7 #
* Risolto un bug che si manifestava testando una nuova città e usandola in
  modalità temporanea premendo semplicemente "invio" e in un secondo momento
  provando ad aggiungerla tramite il bottone "Aggiungi".
* Added abbreviation for SOUTH GEORGIA AND THE SOUTH SANDWICH ISLANDS to the
  database, but unfortunately at the moment it seems that the cities of this
  state do not work or have incomplete data, we hope it will be solved soon.

# Versione 6.5 #
* Fixed a couple of bugs in sound effects reproduction; a couple of "for"
  cycles with incorrect maximum values caused the call to a non-existent
  sound effect.
* Fixed bug in local time in "details"; 12-hour time conversion gave an
  error.
* Fixed a bug in the Yahoo Weather Forecast report; In some cities the
  forecasts start from the previous day and not from the current one. The
  correction of these cities entails the loss of the last days of forecast
  proportionate to the mismatch of dates (if the forecast days are set to
  10).

# Versione 6.4 #
* Daylight saving time removed in the "Details" function.
* Improved audio effects reproduction; Now they update regularly if the
  weather conditions change.

# Versione 6.3 #
* Fixed encoding issues.

# Versione 6.2 #
* Fixed bug in the "Add city" function.
* Corretto bug che non assegnava la variabile "_volume" all'avvio
  dell'addon.
* Added missing code from version 6.0; Now you can recover the saved cities
  from the version that uses the Apixu API; The "Test" and "Remove" buttons
  and non-compatible cities are available in the format: "Ferrara, iter
  44.83,11.58 0" (city, geographic coordinates, area definition).

# Versione 6.1 #
* Coorretti 2 bug.

# Versione 6.0 #
* Weather Plus torna a utilizzare l'API di Yahoo Weather.
* Praticamente tutte le funzionalità della precedente versione 4.8 sono
  tornate e mantiene il pulsante "Rinomina".
* Compatibility with Python 3.

# Versione 5.0.1 #
* Corretto bug che restituiva una stringa vuota se la velocità del vento in
  mph era 0.
* Corretto bug che causava la riproduzione di effetti sonori non coerenti
  con il fuso orario.
* corretto il numero di giorni di previsione da 9 a 6 in readme.

# Versione 5.0 #
* Weather Plus now uses the APIXU API.

# Changes in the Weather Plus Settings window: #

* Removed old checkbox "State of barometric pressure". Replaced with new
  checkbox "Add cloudiness value";
* It gives you the percentage of cloudiness.
* Added new checkbox "Add precipitation value". It gives you the amount in
  millimeters of precipitation.
* Removed old checkbox "Indicates the wait with a beep while you search for
  the latest bulletin"; Left active by default.
* added the astronomic information;
* Time of moonrise and moonset.
* Added new button "Rename"; To rename cities more conveniently.
* Improved function of the "Test" button; Now accept some commands to
  facilitate the search for cities; These new commands are described in the
  help function that can be called up with F1.

# Versione 4.8 #
# Changes in the Weather Plus Settings window #

* Added new checkbox; "Use only weather effects"; This allows you to filter
  out all other environmental effects.
* Improved random playback and added 71 new sound effects; You will need to
  update them by clicking twice in "enable audio effects" check box.
* The volume type assigned by the user, between the general and current
  audio volume, is now maintained when the configuration is saved.
* Removed useless sound during selection text in edit box by pressing
  control+a.
* Improved readability into help window invokable with F1 function key.
* Added new compatibility flag for NVDA 2019.1, and the current alpha
  versions.

# Versione 4.7.7 #
* Rimossa la superflua notifica di download completato durante
  l'aggiornamento di Weather Plus.
* Added 6 new sound effects; It will be necessary to update them from the
  settings of the plugin.

# Versione 4.7.6 #
* Bugfix release;

# Versione 4.7.5 #
* Bugfix release

# Versione 4.7.3 #
* "Details" function was updated for convenience; The information about the
  altitude are now provided by veloroutes.org. This leads to small
  differences of little relevance.

# Versione 4.7.2 #
* Fixed small encoding bug.

# Versione 4.7.1 #
* Fixed bug when getting the information about the time zone.

# Versione 4.7 #
* Simplified the update section; Now at the start, in case an update is
  available it will be possible to proceed directly through a single dialog
  box.
* removed the file selector in the update section; Now the update file is
  saved to the temporary folder, It open the possibility to install the
  update automatically, good for beginners.

# Versione 4.6.9 #
* Added arabic localization (thanks to Wafik Immaculate).

# Versione 4.6.8 #
* Updated localizations for brazilian portuguese and european portuguese
  localizations (thanks to Alberto Mendonça).

# Versione 4.6.7 #
* Improved the reading of the current time; In some cities, it was not
  correct. Added daylight saving time to the details; Available only for the
  countries that adopt it.

# Versione 4.6.5 #
* Fixed small bug when reading the time.

# Versione 4.6.4 #
* Migliorata la lettura dell'ora locale corrente; le chiavi di ricerca sono
  più accurate.

# Versione 4.6.2 #
* Corretto bug; il menu "Imposta una città temporanea..." dopo un controllo
  per gli aggiornamenti,veniva abilitato anche se non c'era nessun elenco
  delle città disponibili.
* Corretto bug; impossibile configurare WP quando weather.ini non è ancora
  stato creato,.

# Versione 4.6 #
* Added the menu item "Set a temporary city..."; For the sake of
  completeness, now you can open the temporary city's list also from the
  menu.
* Improved management of temperature scale; Now the settings window will
  always return the default value.
* Improved prevention of the multiple opening of the main windows; If one of
  these is already opened, in addition to the sound alert, puts it in
  foreground.
* Improved audio effects; Now are based on the current local time from the
  city in use.

# Changes in details button function in settings window #

* Aggiunta l'ora locale corrente.
* Fixed altitude value; Now return the altitude values when the value is
  less than or equal to zero.

# Versione 4.5.5 #
* Corretta localizzazione e la documentazione in serbo.
* Corretta la localizzazione in tedesco.

# Changes in the Weather Plus Settings window #

* Added new checkbox; You can enable the comma as the decimal separator,
  otherwise the separator will be the point.

# Versione 4.5.3 #
* correct 2 strings in Russian and ukrainian localizations.
* Corrected title of the Check for upgrade window.
* Improved update algorithm;

# Versione 4.5 #
* Added hotkey NVDA+shift+control+alt+w; it Opens the Weather Plus settings
  dialog.
* Correct some English strings.

# Changes in the Weather Plus Settings window #

* Added 8 new check boxes It is now possible to further customize the
  readout:
* wind direction.
* wind speed.
* Perceived temperature.
* Humidity value.
* Visibility value.
* Atmospheric pressure value.
* Indicates the atmospheric pressure in millimeters of mercury (mmHg).
* State of the barometric pressure.

# Versione 4.4.8 #
* Aggiunta la traduzione in polacco (grazie a Zvonimir Staneczyć).
* Compatibility with wx python version 4;

# Versione 4.4.1 #
* Added SSL support;

# Versione 4.4 #
* Corretto bug nella lettura della nuova stringa di versione, durante un
  time-out della connessione.
* Improved the upgrade section; Now the dialog do not interferes with the
  nvda menu.
* Revised and corrected russian Localization.
* Adding Ukrainian translation (thanks to Alex Yeshanu).

# Versione 4.3.4 #
* Riveduta e corretta la localizzazione Tedesca.

# Versione 4.3.3 #
* Aggiunta localizzazzione tedesca (grazie a Karl Eick).

# Versione 4.3.2 #
* Aggiunta localizzazione Rumena (grazie a Florian Ionașcu).

# Versione 4.3.1 #
* Fixed a minor bug in the function "details"; The strings "latitude" and
  "longitude" were reversed compared to the value.

# Versione 4.3 #
* Weather plus moved to the "nvda.it" as it's default hosting provider

# Versione 4.2.4 #
* Fixed a minor bug when the connection was not active.

# Versione 4.2.3 #
* Now Weather Plus is able to run some connection attempts before notifying
  the malfunction of the WoeId in use, it emits a beep at each attempt; This
  beep, if you want, can be disabled by using a check box by Weather Plus
  settings.

# Versione 4.2.2 #
* Fixed bug in the translation strings for the scale measurement. In some
  languages, Kelvin, Celsius and Fahrenheit have not been translated.

# Versione 4.2.1 #
* Fixed update notice of Weather Plus during the Windows start-up; This
  happens when the button was pressed "Use currently saved settings on the
  logon and other secure screens (requires administrator privileges)" from
  the general settings of nvda, which copies the configuration, and all of
  the add-on folder systemConfig, but these are not synchronized with
  subsequent updates of the add-ons. If you have ever used at least once
  this option, you will have to do it again one last time just after to have
  up-to-date Weather Plus.

# Versione 4.2 #
* Added 5 new sound effects; It will be necessary to update them from the
  settings of the plugin.
* Fixed bug in the import function; The list of cities was not sorted
  alphabetically.
* Added import mode in the import function; You may decide to completely
  replace your own list, or simply add new cities to it.
* Updated the reading of the weather forecast, current weather report;
  Adding the perceived temperature (wind chill).
* Aggiunte nuove stringhe alla lista per i rapporti meteo.

# Versione 4.1 #
* Fixed bug in the forecast for up to 10 days; Now if the estimates received
  are in number less than the request of the user, the missing days are
  indicated as unknown.
* Fixed string help entry on the command nvda+shift+w.
* Revised and updated documentation.

# Versione 4.0 #
* Updated some parts of code and replaced all instructions eval().

# Versione 3.9.7 #
* Fixed bug during the reading of weather forecasts; Now the temperatures
  are read correctly.

# Versione 3.9.6 #
* Changed the rounding in the conversion of atmospheric pressure from mbar
  in inches of mercury; * Now the value is calculated in defect, while
  before it was in excess.

# Versione 3.9.5 #
* Aggiunte 2 nuove stringhe alla lista rapporti meteo.
* Coorretti 2 bug.
* Updated running sounds for the effect in conditions of only wind; * Now
  the sound of the wind can vary randomly.

# Versione 3.9.4 #
* documentation, localizations for Croatian and german language were
  removed; Because they are no longer supported by the respective
  translators.
* Fixed bug in Serbian localization.
* Updated Czech localization.
* Updated documentation and localization for Galician.

# Versione 3.9 #
* Changed again API service; Weather Plus now uses the new Yahoo Weather API
  with language Yahoo!Query and JQuery:
* The api key is no longer required.
* Restored The search of the homonymous cities; It will be possible to
  choose exactly the desired city from a list.
* Optimized the output of general sounds; Now they are synchronized with the
  voice synthesis and are faster.
* Improved the cache for data off-line; Is zeroed every 10 minutes or only
  by changing the city.
* barometric pressure measured in mbar, or in inches of mercury (if set to
  Fahrenheit).

# Versione 3.8 #
* data accuracy fixes
* Enabled the automatic setting of the language; Now the API sends the data
  of the weather conditions in the language set by nvda.
* Added the cache for bulletin and weather forecasts; If not changed the
  city, degree scale or the days of forecast set, you will be able to read
  the data for 10 minutes even when connection off-line The cache is reset
  at each change described above. This is because the bulletins do not
  change in this period of time and to reduce the frequent calls to the API,
  maybe playing with sound effects.
* Improved searching for updates; Now once downloaded, It will be activated
  to its installation, or in the case of a portable version of nvda It will
  be opened the folder where you saved the update.
* Updated all sounds. Now the sounds are in the wave format.

# Versione 3.7 #
* Aggiunta possibilità di disattivare la conversione in metri al secondo del
  vento.
* Aggiunta possibilità di utilizzare l'unità di misura in libbre per pollice
  quadrato.
* Coorretti 2 bug.

# Versione 3.6 #
* Changed the API service (application programming interface); Now WP uses
  the service offered by OpenWeatherMap.org instead of Yahoo Weather.com.
* Added Wind classification in the current bulletin.
* Added a cloudiness percentage in the current bulletin.
* Adopted the units of pressure measurement in hectopascal in the current
  bulletin.

# Changes to the Weather Plus Settings window #

* Changed insertion/search from yahoo zipcode/woeId in ID number, Identifier
  of the city; * ID numbers city are similar to woeid, but the woeId will no
  longer work, even the old zipcode. You will be able to rediscover a great
  part of the cities by typing the name or part of it.
* Added insertion/Search for geographical coordinates.
* Added insertion/search by postal code.
* Improved the function "details".
* assigned to F1 key the entry/search help.
* assigned to F4 key the controls to the forecasts from 1 to 16 days set;
  Attention, if you choose to copy to the clipboard a value greater than 10,
  it will not be read!
* Assigned F5 key for audio controls.
* Adding measurement scale degrees Kelvin.
* Added check for updates; You can set the control by settings or check
  manually from menu.
* reassigned the button "Find your city" in "Management of your API Key...";
  Allows you to enter or change the key-API.

# Versione 3.5 #
* Aggiunta localizzazione croata (grazie a Gordan Radić).
* Added control for no longer valid WoeId and Zip Code found in the network;
  There have been reports of codes that have stopped working from one day to
  another, WP now warns if one of these has been inserted from the windows
  of search on the net. If this occurs using the function "Find your
  city...", please report it to me so that I can update the Weather_buffer
  and remove them from the list.
* Fixed encoding bug in the search functionality.
* Updated the window to set one temporary zip code; Added feature "Find" As
  in the other windows of Weather Plus: Control+F3 = Find..., F3 = Find
  next, Shift+F3 = Find previous.

# Versione 3.4 #
* Aggiunta traduzione galiziana (grazie a Iván Novegil).
* Aggiunta traduzione portoghese (grazie a Ângelo Miguel Abrantes).
* Aggiunta traduzione tedesca (incompleta).

# Versione 3.3 #
* Aggiunta misura della velocità del vento in metri al secondo.
* encoding fixes

# Versione 3.2 #
* Updated the reading of the weather forecast, current weather report and
  reading of the date of the current weather report; Yahoo weather forecast,
  from a bit of time and in random amounts, allows it to pass a historic
  from -10 to -5 days of weather forecast to be inserted between the updated
  data that we want to read; It was added a filter that allows you to read
  only the last weather data updated, and a discreet beep alerts when it
  intervenes; This beep, if you want, can be disabled by using a check box
  by Weather Plus settings. Obviously, the filtering of data sometimes
  involves a short delay in reply, but is still acceptable.
* Forecasts of the time extended to 10 days.

# Versione 3.1 #
* Added translation in Serbian (thanks to the kind cooperation of Dejan
  Gasic.
* Fixed command insert+alt+w; It did not check the validity of the zipcode
  in use and did not check if the connection was active as the other
  commands do.
* Updated the playback function of sound effects; Mp3 format is now
  used. Now the files will be much smaller.
* Added 55 new sound effects; It will be necessary to update them from the
  settings of the plugin.

# Changes to the Weather Plus Settings window #

* Fixed display help on the buttons; Now disables / enables real-time
  through the appropriate check box.
* Added 3 shortcut commands to navigate more quickly in the window:
* F1 jumps into list and edit box of zip code.
* F2 returns to the last selection reached with TAB.
* F3 jumps into volume controls (if the sound effects are installed and
  activated).
* Added shortcut commands for all check boxes and buttons; Omitted the two
  radio buttons as they are present in succession and the first is reachable
  with the command control+shift+w.
* Changed, the button "define" is now disabled if the sound effects are not
  installed and activated.
* Added volume controls; You can adjust the overall volume and the last
  heard sound effect; This option is enabled if the sound effects are
  installed and activated.
* Added ability to set the system time in 12-hour format (12:30 AM `-` 12:30
  PM) , or the 24-hour system (12:30 `-` 00:30).

# Versione 3.0 #
* Added the slovak translation (thanks to the kind cooperation of Vitek
  Jirasek).
* Aggiunta traduzione in portoghese-brasiliano e portogallo (grazie aAdair
  Knaesel).
* Aggiunte nuove stringhe alla lista per i rapporti meteo.
* Aggiunti 171 nuovi effetti sonori, ora sono 213 in totale.
* Aggiunto il comando insert + alt + w in gesture, annuncia la data
  dell'ultimo aggiornamento del bollettino meteorologico.
* Aggiunto scriptCategory che sposta nella corretta posizione i tasti rapidi
  di Weather Plus in "gesti e tasti di immissione".

# Changes to the Weather Plus Settings window #

* Added radio button to set how to indicate the temperature scale;
* The choice is between:
* Celsius `-` Fahrenheit
* C `-` F
* No indication
* Added button " Define"; It permits to define the zone of one city between:
* Hinterland
* Maritime area
* Desert zone
* Arctic zone
* Mountain zone
* The choice will consent to Weather Plus to use more appropriate sound
  effects for every single city; * This is the reason for the boost of the
  number of new sound effects in this versione of the addon; * Many of the
  new sound effects I got them from Tapin, whom I thank sincerely.

# Versione 2.9 #
* Aggiunta possibilità durante l'importazione di selezionare il contenuto
  del file importato.
* Aggiunti 4 nuovi effetti sonori.
* Aggiunta traduzione in Russo (grazie a Alex Yeshanu).
* Aggiunta traduzione in ceco (grazie a Jirimu Holzingerovi).

# Versione 2.8 #
* Corretto bug in "dettagli", apriva finestra delle ricorrenze quando non
  trovava la località.
* Fixed regexp to search for the altitude; It did not accept parameters of
  single digits.
* Improved parser of the edit box; It should find more easily the city.
* Connections now handled by urllib2, instead of urllib; * This should allow
  the functioning of the addon even on a computer connected to the corporate
  network protected by proxy.
* Added feature "Find"; Control+F3 = Find..., F3 = Find next, Shift+F3 =
  Find previous.

# Versione 2.7 #
* Fixed wrong name of a string "Motorcycle" in "Motorcycle00"; He asked
  updated sound effects because they could not find the file.
* Added ability to read about wind ; Direction, speed and temperature of the
  wind.
* Added ability to read atmospherical information; Humidity, visibility,
  pressure and state of the barometric pressure.
* Added ability to read the Astronomic information; * Time of sunrise and
  sunset.

# Changes to the Weather Plus Settings window #

* Aggiunte 3 caselle di controllo per gestire le rispettive informazioni
  sopra elencate.
* Added button " Details "; * Provides some information such as the real
  name of the city ( assigned by Yahoo Weather Forecast), the state / region
  and the nation to which it belongs; With geographic coordinates, and
  height above sea level.
* Added recognition of WoeID (location codes, eg. Bologna it corresponds to
  711080).
* Now you can type the name of the city, in this case, if any, the
  occurrences will be listed and you will be able to choose.

# Versione 2.6 #
* The functions of the buttons "Add" and "Remove" were optimized in the zip
  code's list management; Now the operation are a lot more fast!
* The function of the button "Test" was optimized, now it exploits until 13
  research keys; Now if it doesn't find the name of the city it is a real
  bad luck!
* The function of the button "Find your city...", now finds more countries;
  It was added an automatic test that collects the functioning zip codes,
  and it further consents a rapid visualization thanks to the creation of a
  little buffer corresponding to the name of the specific country.
* Three new sounds effects were added; It will be necessary to update them
  from the settings of the plugin.

# Versione 2.5 #
* Aggiunto comando nella gesture per alternare temporaneamente la scala
  della temperatura da Celsius a Fahrenheit, il comando ha effetto anche
  nella finestra delle impostazioni.
* Corretto bug, se l'utente non premeva "Aggiungi" o "Preimpostato" non
  permetteva di vocalizzare il nome della città perché non in lista.
* Aggiunte nuove stringhe alla lista per i rapporti meteo.

# Changes to the Weather Plus Settings window #

* Aggiunto pulsante per aprire una pagina web di ricerca dei Zip Code
  mondiali.
* Aggiunta la possibilità di importare / esportare i codici postali di
  amici.
* Aggiunta possibilità di copiare negli appunti il bollettino o la
  previsione meteo.
* Aggiunta possibilità per ascoltare gli effetti audio metereologici,
  l'opzione permette anche l'installazione/aggiornamento degli effetti
  audio.
* Aggiunta possibilità aiuto sui pulsanti della gestione dei Zip Code.
* Cambiata la modalità di visualizzazione della finestra, ora lascia liberi
  i menu di nvda quando è aperta.

# Versione 2.4.4 #
* Aggiunte 2 nuove stringhe alla lista rapporti meteo.
* Aggiunta traduzione in Francese e Spagnolo (grazie a Rémy Ruiz e Pablo
  Vargas).

# Versione 2.4.3 #
* Aggiunta la previsione meteo fino ai successivi 4 giorni.
* Aggiunta una stringa alla lista rapporti meteo.
* La lista dei zipcode temporanei ora viene ordinata ad ogni nuovo
  inserimento.

# Versione 2.4 #
* Corretto un bug che impediva di salvare e gestire correttamente i nomi
  delle città contenenti vocali accentate.

# Versione 2.3 #
* Eliminata la finestra di dialogo per impostare la scala di misura della
  temperatura, ora è stata aggiunta in una nuova gui che permetta di
  impostare tutto in una sola finestra.
* Ora è possibile testare/aggiungere/eliminare/preimpostare come default i
  Zip Code raccolti man mano in una lista.
* Modificata la finestra di dialogo per l'inserimento digitato di un Zip
  Code, ora permette di impostare in modalità temporanea un Zip Code
  precedentemente aggiunto alla lista dall'apposito menu in Preferenze.
* Ora la documentazione può essere letta in inglese se la lingua impostata
  non è compresa nei documenti.

# Versione 2.2 #
* Corretto un bug che non permetteva la lettura della documentazione per le
  versioni definitive di nvda.

# Versione 2.1 #
* Corretto un bug che non chiudeva correttamente il plugin, questo impediva
  a nvda di aggiornare l'icona nel system tray.

# Versione 2.0 #
* Menu Weather Plus Impostazioni spostato in Preferenze sottomenu.
* correct input on the fly is no longer saved, so it is temporary; To call
  the city set in the preferences, press INSERT + control + f3.

# Versione 1.9 #
* aggiunti aiuto immissione delle funzioni.
* aggiunto una nuova funzione per inserimento rapido dello Zip Code.
* aggiunto lettura/scrittura configurazione in weather.ini, ora non è più
  necessario editare il file sorgente.
* aggiunto Weather menu nel System Tray.
* aggiunto sottomenu impostazione Zip Code...
* aggiunto sottomenu impostazione scala di temperatura (Fahrenheit o
  Celsius).
* aggiunto menu Documentazione.
* Aggiunta localizzazione italiana.

# Initial Version 1.1 #
* updated the NVDA-addon.
* Translation support has been added.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
