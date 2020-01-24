# Weather Plus #

* Autor: Adriano Barbieri
* Compatibilidade con NVDA: da 2017.3 á 2019.3
* Descargar [versión estable][1]

# ACERCA DE WEATHER PLUS: #

* Este complemento engade a temperatura local e o pronóstico do tempo actual
  a 24 horas e a predición ata 9 días adicionais para NVDA.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Liberado baixo a licenza GNU GPL (General Public License) v2

* Weather Plus funciona a través da presenza e funcionamento dos seguintes
  servizos:
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# USAGE: #
* Press NVDA+w to get the information about current temperature and weather
  conditions.
* Press NVDA+shift+W to get 24 hours forecast and forecast up to 9 days.
* Press NVDA+shift+control+w to set a temporary city.
* Press NVDA+shift+control+alt+w to open the Weather Plus settings dialog.
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

* Set and Manage Your Cities... - Displays or allows to set the current city
  from a list.

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
  Fahrenheit `-` Kelvin (by default) C `-` F `-` K or Unspecified.

* Combo box: Weather Forecasts up to days: 3; You can choose between 1 to 10
  (3 days by default)

* To perform the following actions, toggle the following checkboxes:

* Copy the weather report and weather forecast, including city details to
  clipboard; check box not checked (by default)

* Enable audio effects (only for the current weather conditions); This check
  box also allows you to manage the installation of sound effects; If the
  sound effects are installed and the check box is activated, the F5 key and
  the volume setting becomes available.

* There will also be available an additional check box: Use only weather
  effects.

* You can change the overall volume or change the last heard sound effect
  and filter out the others sounds in your environment. Checkbox is not
  checked by default.

* Use only weather effects - This option is available if sound effects are
  enabled; If is enabled, allows to listen only weather effects such as
  rain, wind, thunder, etc., filtering out all environmental
  ones. (unchecked by default)

* Enable the reading of the hours in 24-hour format. - If this checkbox is
  unchecked, announces the time in 12-hour format for example, 12 AM `-` 12
  PM. check box is checked (by default)

* Enable help buttons in the settings window; check box checked (by default)

* Read wind information; check box not checked (by default). If this
  checkbox is enabled, you can also activate the following checkboxes:

* Add wind direction; Indicates the provenance of the wind. check box
  checked (by default)

* Add speed of the wind; Indicates the speed in kilometers or miles per
  hour. check box checked (by default)

* Add speed in meters per second of the wind; check box checked (by default)

* Add perceived temperature; check box checked (by default)

* Read atmospherical information; check box not checked (by default). If
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

* Read astronomical information; Indicates the time of sunrise and
  sunset. check box not checked (by default)

* Use the comma to separate decimals; If enabled, uses the comma as a
  decimal separator, otherwise, use the point. check box not checked (by
  default)

* Check for upgrade; If is activated this alerts when there is an update of
  the addon. check box checked (by default)

* Prema o botón de Aceptar para confirmar a acción, Cancelar para cancelala.

* If you have modified the cities list, by pressing "Cancel", you will be
  remembered and you can still save it. Note: your settings will be save in
  the file named:

* "Weather.ini": configuración de inicio do Weather Plus.
* "Weather.volumes": niveis de volume de audio personalizado, calqueira que
  sexa o volume xeral do sistema.
* "Weather.zipcodes": lista de cidades cos seus códigos postais e
  definicións.
* "Weather_searchkey": tecla de busca gardada.

--------------------------------------------------------------------------------

# Que Hai de novo: #

# Version 7.4 #
* Fixed a bug in a city search function.

# Versión 7.3 #
* Arranxado erro inesperado en caso de que non se atope a páxina ao procurar
  actualizacións.

# Versión 7.2 #
* Fixed bug after adding a city, if it is the first one entered if you press
  ok button and restart the add-on.
* Now the progress dialog show again the time remaining and time elapsed.
* tradución italiana correcta na axuda do botón renomear.

# Versión 7.1 #
* Fixed update bug.

# Versión 7.0 #
* Improved search window, now it is possible to manage all the search key
  inserted, add, delete and save it from context menu.
* Mellorado o control de apertura de xanelas.
* arranxados algúns pequenos erros.

# Versión 6.9 #
* Implementada a busca recursiva de cidades co sistema válido utilizado
  anteriormente na versión Apixu de Weather_Plus.
* Prema f1 na xanela de opcións para unha explicación dos comandos
  dispoñibles.

# Versión 6.8 #
* Updated compatibility for Python 3

# Versión 6.7 #
* Arranxado un erro ao se proba unha nova cidade e usándoa en modo temporal
  premendo simplemente "intro" e nun momento posterior tratando de engadila
  mediante o botón "Engadir".
* Added abbreviation for SOUTH GEORGIA AND THE SOUTH SANDWICH ISLANDS to the
  database, but unfortunately at the moment it seems that the cities of this
  state do not work or have incomplete data, we hope it will be solved soon.

# Versión 6.5 #
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

# Versión 6.4 #
* Daylight saving time removed in the "Details" function.
* Improved audio effects reproduction; Now they update regularly if the
  weather conditions change.

# Versión 6.3 #
* Fixed encoding issues.

# Versión 6.2 #
* Fixed bug in the "Add city" function.
* Correxido un erro que non asignou a variable "_volume" ao iniciar o addon.
* Added missing code from version 6.0; Now you can recover the saved cities
  from the version that uses the Apixu API; The "Test" and "Remove" buttons
  and non-compatible cities are available in the format: "Ferrara, iter
  44.83,11.58 0" (city, geographic coordinates, area definition).

# Versión 6.1 #
* Arranxados dous erros.

# Versión 6.0 #
* Weather Plus volve empregar o Yahoo Weather API.
* Prácticamente todas as características da versión anterior 4.8 están de
  volta e mantén o botón "Renomear".
* Compatibility with Python 3.

# Versión 5.0.1 #
* Arranxado erro polo que se devolvía unha cadea vacía se a velocidade do
  vento en mph era 0.
* Corrixido erro que causaba inconsistencia entre os efectos de son da zona
  horaria e os reproducidos.
* axustado o número de días de previsión de 9 a 6 no readme.

# Versión 5.0 #
* Weather Plus now uses the APIXU API.

# Changes in the Weather Plus Settings window #

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

# Versión 4.8 #
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

# Versión 4.7.7 #
* Eliminada a notificación innecesaria de descarga completada ao actualizar
  WeatherPlus.
* Added 6 new sound effects; It will be necessary to update them from the
  settings of the plugin.

# Versión 4.7.6 #
* Bugfix release.

# Versión 4.7.5 #
* Bugfix release.

# Versión 4.7.3 #
* "Details" function was updated for convenience; The information about the
  altitude are now provided by veloroutes.org. This leads to small
  differences of little relevance.

# Versión 4.7.2 #
* Fixed small encoding bug.

# Versión 4.7.1 #
* Fixed bug when getting the information about the time zone.

# Versión 4.7 #
* Simplified the update section; Now at the start, in case an update is
  available it will be possible to proceed directly through a single dialog
  box.
* removed the file selector in the update section; Now the update file is
  saved to the temporary folder, It open the possibility to install the
  update automatically, good for beginners.

# Versión 4.6.9 #
* Added arabic localization (thanks to Wafik Immaculate).

# Versión 4.6.8 #
* Updated localizations for brazilian portuguese and european portuguese
  localizations (thanks to Alberto Mendonça).

# Versión 4.6.7 #
* Improved the reading of the current time; In some cities, it was not
  correct. Added daylight saving time to the details; Available only for the
  countries that adopt it.

# Versión 4.6.5 #
* Fixed small bug when reading the time.

# Versión 4.6.4 #
* Mellorada a lectura da hora local actual; a procura é agora máis exacta.

# Versión 4.6.2 #
* Arranxado erro: Despois de “Verificar actualizacións”, o menú “Establecer
  unha cidade temporal…” foi habilitado aínda que non estea dispoñible
  ningunha lista de cidades.
* Arranxado erro; imposible configurar WP se weather.ini non estaba
  creadoaínda.

# Versión 4.6 #
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

* Engadida hora local actual.
* Fixed altitude value; Now return the altitude values when the value is
  less than or equal to zero.

# Versión 4.5.5 #
* Correct localization and documentation in Serbian.
* Corrixida a tradución alemá.

# Changes in the Weather Plus Settings window #

* Added new checkbox; You can enable the comma as the decimal separator,
  otherwise the separator will be the point.

# Versión 4.5.3 #
* correct 2 strings in Russian and ukrainian localizations.
* Corrected title of the Check for upgrade window.
* Improved update algorithm.

# Versión 4.5 #
* Added hotkey NVDA+shift+control+alt+w; it Opens the Weather Plus settings
  dialog.
* Correct some English strings.

# Changes in the Weather Plus Settings window #

* Added 8 new check boxes; It is now possible to further customize the
  readout:
* wind direction.
* wind speed.
* Perceived temperature.
* Humidity value.
* Visibility value.
* Atmospheric pressure value.
* Indicates the atmospheric pressure in millimeters of mercury (mmHg).
* State of the barometric pressure.

# Versión 4.4.8 #
* Engadida tradución polaca (grazas a Zvonimir Staneczyć).
* Compatibility with wx python version 4.

# Versión 4.4.1 #
* Added SSL support.

# Versión 4.4 #
* Arranxado un erro na lectura da cadea da nova versión durante unha
  conexión expirada.
* Improved the upgrade section; Now the dialog do not interferes with the
  nvda menu.
* Revised and corrected russian localization.
* Adding Ukrainian translation (thanks to Alex Yeshanu).

# Versión 4.3.4 #
* Revisada e corrixida a tradución alemá.

# Versión 4.3.3 #
* Engadida tradución ao alemán (grazas a Karl Eick).

# Versión 4.3.2 #
* Engadida tradución ao rumano (grazas a Florian Ionașcu).

# Versión 4.3.1 #
* Fixed a minor bug in the function "details"; The strings "latitude" and
  "longitude" were reversed compared to the value.

# Versión 4.3 #
* Weather plus moved to the "nvda.it" as it's default hosting provider.

# Versión 4.2.4 #
* Fixed a minor bug when the connection was not active.

# Versión 4.2.3 #
* Now Weather Plus is able to run some connection attempts before notifying
  the malfunction of the WoeId in use, it emits a beep at each attempt; This
  beep, if you want, can be disabled by using a check box by Weather Plus
  settings.

# Versión 4.2.2 #
* Fixed bug in the translation strings for the scale measurement. In some
  languages, Kelvin, Celsius and Fahrenheit have not been translated.

# Versión 4.2.1 #
* Fixed update notice of Weather Plus during the Windows start-up; This
  happens when the button was pressed "Use currently saved settings on the
  logon and other secure screens (requires administrator privileges)" from
  the general settings of nvda, which copies the configuration, and all of
  the add-on folder systemConfig, but these are not synchronized with
  subsequent updates of the add-ons. If you have ever used at least once
  this option, you will have to do it again one last time just after to have
  up-to-date Weather Plus.

# Versión 4.2 #
* Added 5 new sound effects; It will be necessary to update them from the
  settings of the plugin.
* Fixed bug in the import function; The list of cities was not sorted
  alphabetically.
* Added import mode in the import function; You may decide to completely
  replace your own list, or simply add new cities to it.
* Updated the reading of the weather forecast, current weather report;
  Adding the perceived temperature (wind chill).
* Engadíronse novas cadeas aos informes meteorolóxicos da lista.

# Versión 4.1 #
* Fixed bug in the forecast for up to 10 days; Now if the estimates received
  are in number less than the request of the user, the missing days are
  indicated as unknown.
* Fixed string help entry on the command nvda+shift+w.
* Revised and updated documentation.

# Versión 4.0 #
* Updated some parts of code and replaced all instructions eval().

# Versión 3.9.7 #
* Fixed bug during the reading of weather forecasts; Now the temperatures
  are read correctly.

# Versión 3.9.6 #
* Changed the rounding in the conversion of atmospheric pressure from mbar
  in inches of mercury; Now the value is calculated in defect, while before
  it was in excess.

# Versión 3.9.5 #
* Engadidas dúas novas cadeas á lista reportes do tempo.
* Arranxados dous erros.
* Updated running sounds for the effect in conditions of only wind; Now the
  sound of the wind can vary randomly.

# Versión 3.9.4 #
* documentation, localizations for Croatian and german language were
  removed; Because they are no longer supported by the respective
  translators.
* Fixed bug in Serbian localization.
* Updated Czech localization.
* Updated documentation and localization for Galician.

# Versión 3.9 #
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

# Versión 3.8 #
* data accuracy fixes.
* Enabled the automatic setting of the language; Now the API sends the data
  of the weather conditions in the language set by nvda.
* Added the cache for bulletin and weather forecasts; If not changed the
  city, degree scale or the days of forecast set, you will be able to read
  the data for 10 minutes even when connection off-line. The cache is reset
  at each change described above. This is because the bulletins do not
  change in this period of time and to reduce the frequent calls to the API,
  maybe playing with sound effects.
* Improved searching for updates; Now once downloaded, It will be activated
  to its installation, or in the case of a portable version of nvda It will
  be opened the folder where you saved the update.
* Updated all sounds. Now the sounds are in the wav format.

# Versión 3.7 #
* Engadida a posibilidade de deshabilitar a conversión a metros por segundo
  da velocidade do vento.
* Engadida a posibilidade de usar libras por polgada cadrada coma unidade de
  presión.
* Arranxados dous erros.

# Versión 3.6 #
* Changed the API service (application programming interface); Now WP uses
  the service offered by OpenWeatherMap.org instead of Yahoo Weather.com.
* Added Wind classification in the current bulletin.
* Added a cloudiness percentage in the current bulletin.
* Adopted the units of pressure measurement in hectopascal in the current
  bulletin.

# Changes to the Weather Plus Settings window #

* Changed insertion/search from yahoo zipcode/woeId in ID number, Identifier
  of the city; ID numbers city are similar to woeid, but the woeId will no
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

# Versión 3.5 #
* Engadida tradución ao croata (grazas a Gordan Radić).
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

# Versión 3.4 #
* Engadida tradución ao galego (grazas a Iván Novegil).
* Engadida tradución ao portugués (grazas a Ângelo Miguel Abrantes).
* Engadida tradución ao alemán (incompleta).

# Versión 3.3 #
* Agregouse a medida da velocidade do vento en metros por segundo.
* encoding fixes.

# Versión 3.2 #
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

# Versión 3.1 #
* Added translation in Serbian (thanks to the kind cooperation of Dejan
  Gasic).
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

# Versión 3.0 #
* Added the slovak translation (thanks to the kind cooperation of Vitek
  Jirasek).
* Engadiu tradución en portugués-brasileiro e portugués-portugués (grazas á
  amable colaboración de Adair Knaesel).
* Engadíronse novas cadeas aos informes meteorolóxicos da lista.
* Engadíronse 171 novos efectos de son, agora o importe total é de 213.
* Engadido o comando insert + alt + w no xesto para anunciar a última
  actualización do boletín actual.
* Engadida a categoría de script que cambia a posición correcta das teclas
  rápidas de Weather Plus en "Xestos de entrada..."

# Changes to the Weather Plus Settings window #

* Added radio button to set how to indicate the temperature scale;
* The choice is between:
* Celsius `-` Fahrenheit
* C `-` F
* No indication
* Added button "Define"; It permits to define the zone of one city between:
* Hinterland
* Maritime area
* Desert zone
* Arctic zone
* Mountain zone
* The choice will consent to Weather Plus to use more appropriate sound
  effects for every single city; This is the reason for the boost of the
  number of new sound effects in this version of the addon; Many of the new
  sound effects I got them from Tapin, whom I thank sincerely.

# Versión 2.9 #
* Engadido a opción ao importar para seleccionar o contido do ficheiro
  importado.
* Engadíronse catro novos efectos de son.
* Engadindo tradución ao ruso (grazas a Alex Yeshanu).
* Engadindo tradución ao checo (grazas a Jirimu Holzingerovi).

# Versión 2.8 #
* Arranxouse un erro en "detalles", que usaba para abrir a xanela dos
  sucesos cando non atopaba a cidade.
* Fixed regexp to search for the altitude; It did not accept parameters of
  single digits.
* Improved parser of the edit box; It should find more easily the city.
* Connections now handled by urllib2, instead of urllib; This should allow
  the functioning of the addon even on a computer connected to the corporate
  network protected by proxy.
* Added feature "Find"; Control+F3 = Find..., F3 = Find next, Shift+F3 =
  Find previous.

# Versión 2.7 #
* Fixed wrong name of a string "Motorcycle" in "Motorcycle00"; He asked
  updated sound effects because they could not find the file.
* Added ability to read about wind ; Direction, speed and temperature of the
  wind.
* Added ability to read atmospherical information; Humidity, visibility,
  pressure and state of the barometric pressure.
* Added ability to read the Astronomic information; Time of sunrise and
  sunset.

# Changes to the Weather Plus Settings window #

* Engadíronse 3 caixas de verificación para xestionar a súa información
  anterior.
* Added button "Details"; Provides some information such as the real name of
  the city ( assigned by Yahoo Weather Forecast), the state / region and the
  nation to which it belongs; With geographic coordinates, and height above
  sea level.
* Added recognition of WoeID (location codes, eg. Bologna it corresponds to
  711080).
* Now you can type the name of the city, in this case, if any, the
  occurrences will be listed and you will be able to choose.

# Versión 2.6 #
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

# Versión 2.5 #
* Engadido un comando no xesto para cambiar temporalmente a escala de
  temperatura de Celsius a Fahrenheit, o comando tamén é efectivo na ventá
  de configuración.
* Corrixido un erro, se o usuario non preme os botóns "Engadir" ou
  "Preselección", non permitiu vocalizar o nome da cidade xa que non se
  incluíu na lista.
* Engadíronse novas cadeas aos informes meteorolóxicos da lista.

# Changes to the Weather Plus Settings window #

* Botón engadido para abrir unha páxina web de investigación para comprobar
  se hai códigos postais mundiais.
* Engadiu a posibilidade de importar / exportar os códigos de código postal
  de amigos.
* Engadido a posibilidade de copiar o informe do tempo ou a previsión do
  tempo no portapapeis.
* Engadida a posibilidade de escoitar os efectos de son meteorolóxicos, a
  opción tamén permite a instalación / actualización dos efectos de son.
* Engadido botóns de axuda na xestión do código postal.
* Cambia ao modo de visualización da xanela, os menús de nvda non están
  restrinxidos cando está aberto.

# Versión 2.4.4 #
* Engadidas dúas novas cadeas á lista reportes do tempo.
* Engadindo tradución ao español e ao francés (grazas a Pablo Vargas e Rémy
  Ruiz).

# Versión 2.4.3 #
* Engadindo a previsión meteorolóxica para os próximos 4 días.
* Engadindo unha cadea ao informe meteorolóxico da lista.
* A lista de código postal temporal está agora ordenada para cada nova
  inserción.

# Versión 2.4 #
* Resolveu un erro que impedía gardar e xestionar correctamente os nomes das
  cidades que conteñen vogais acentuados.

# Versión 2.3 #
* O cadro de diálogo eliminado para definir a escala da medición da
  temperatura, agora engadiuse un novo gui que lle permite configurar todo
  nunha soa xanela.
* Entón tamén poderá Probar / Engadir / Eliminar / Preselección como o
  código postal predeterminado recollido como lista.
* Modificado o cadro de diálogo para introducir un código postal escrito,
  agora en modo temporal permítelle configurar un código postal previamente
  engadido á lista en Preferencias no menú.
* Agora a documentación pódese ler en inglés se a configuración de idioma
  non está incluída nos documentos.

# Versión 2.2 #
* Arranxouse un erro que non lle permitiu abrir a documentación das versións
  definitivas de NVDA.

# Versión 2.1 #
* Arranxado un erro que non pechaba correctamente o complemento, isto
  impediu que NVDAupdate a icona na bandexa do sistema.

# Versión 2.0 #
* Movido o menú Configuración do Weather Plus en o submenú Preferencias.
* correct input on the fly is no longer saved, so it is temporary; To call
  the city set in the preferences, press INSERT + control + f3.

# Versión 1.9 #
* engadiu axuda para entrar ás funcións.
* engadiu unha nova función para a entrada rápida do código postal.
* engadiu configuración de lectura / escritura weather.ini, xa non ten que
  editar o ficheiro de orixe.
* Menú do Weather engadido na bandexa do sistema.
* engadiu a opción submenú Código postal.
* engadiu unha escala de temperatura de sub-axuste (Fahrenheit ou Celsius).
* engadido menú Documentación.
* Engadido a localización italiana.

# Initial Version 1.1 #
* updated the NVDA-addon.
* Translation support has been added.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
