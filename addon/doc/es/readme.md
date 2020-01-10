# Weather Plus #

* Autor: Adriano Barbieri
* Compatibilidad con NVDA: de 2017.3 a 2019.3
* Descargar: [versión estable][1]

# ACERCA DE WEATHER PLUS: #

* Este complemento añade la temperatura local y el pronóstico del tiempo
  actual a 24 horas y la predicción hasta 9 días adicionales para NVDA.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Liberado bajo la licencia GNU GPL (General Public License) v2

* Weather Plus funciona a través del uso y la presencia de los siguientes
  servicios:
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
* Pulsar NVDA + shift + control + alt + w para abrir el cuadro de diálogo
  Configuración de Weather Plus.
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

* Pulsa el botón Aceptar para confirmar la acción o el botón Cancelar para
  anular la acción.

* If you have modified the cities list, by pressing "Cancel", you will be
  remembered and you can still save it Note: your settings will be save in
  the file named:

* "Weather.ini": configuración de inicio de Weather Plus.
* "Weather.volumes": niveles de volumen de audio personalizado, cualquiera
  que sea el volumen general.
* "Weather.zipcodes": lista de las ciudades con su código postal y
  definiciones.
* "Weather_searchkey": clave de búsqueda guardada.

--------------------------------------------------------------------------------

# Que Hay de nuevo: #

# Versión 7.3 #
* Se ha corregido un error inesperado cuando no se encontró la página
  durante la búsqueda de actualizaciones.

# Versión 7.2 #
* Fixed bug after adding a city, if it is the first one entered if you press
  ok button and restart the add-on.
* Now the progress dialog show again the time remaining and time elapsed.
* corregida la traducción italiana en la ayuda del botón renombrar.

# Versión 7.1 #
* Fixed update bug.

# Versión 7.0 #
* Improved search window, now it is possible to manage all the search key
  inserted, add, delete and save it from context menu.
* Mejorado el control de apertura de ventana.
* corregidos algunos pequeños fallos.

# Versión 6.9 #
* Se ha implementado la búsqueda recursiva de ciudades con el sistema válido
  usado anteriormente en la versión de Weather Plus para Apixu.
* Pulsa f1 en la ventana de opciones para ver una explicación con las
  órdenes disponibles.

# Versión 6.8 #
* Updated compatibility for Python 3

# Versión 6.7 #
* Corregido un fallo que sucedía al probar una nueva ciudad y usarla en modo
  temporal pulsando simplemente "intro" e intentando añadirla después
  mediante el botón "Añadir".
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
* Se corrigió un error que no asignaba la variable "_volume" al iniciar el
  complemento.
* Added missing code from version 6.0; Now you can recover the saved cities
  from the version that uses the Apixu API; The "Test" and "Remove" buttons
  and non-compatible cities are available in the format: "Ferrara, iter
  44.83,11.58 0" (city, geographic coordinates, area definition).

# Versión 6.1 #
* Se han corregido 2 errores.

# Versión 6.0 #
* Weather Plus vuelve a utilizar la API de Yahoo Weather.
* Prácticamente todas las características de la versión 4.8 anterior están
  de vuelta y mantienen el botón "Renombrar".
* Compatibility with Python 3.

# Versión 5.0.1 #
* Se corrigió un error que devolvía una cadena vacía si la velocidad del
  viento en mph era 0.
* Corrección de errores que causó que los efectos de sonido no fueran
  consistentes con la zona horaria para reproducirse.
* se ajustó el número de días de previsión de 9 a 6 en el archivo readme.

# Versión 5.0 #
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
* Eliminado notificación innecesaria de la descarga completa durante la
  actualización de Weather Plus.
* Added 6 new sound effects; It will be necessary to update them from the
  settings of the plugin.

# Versión 4.7.6 #
* Bugfix release;

# Versión 4.7.5 #
* Bugfix release

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
* Mejorada la lectura de la hora local actual; los criterios de búsqueda son
  más precisos.

# Versión 4.6.2 #
* Error corregido: después de verificar las actualizaciones, el menú
  "Establecer una ciudad temporal..." se habilitó incluso si no había una
  lista disponible de ciudades.
* Error corregido: no se puede configurar WP cuando weather.ini aún no se ha
  creado.

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

* Se ha añadido la hora local actual.
* Fixed altitude value; Now return the altitude values when the value is
  less than or equal to zero.

# Versión 4.5.5 #
* Corregida la localización y la documentación en Serbio.
* Corregida la localización en Alemán.

# Changes in the Weather Plus Settings window #

* Added new checkbox; You can enable the comma as the decimal separator,
  otherwise the separator will be the point.

# Versión 4.5.3 #
* correct 2 strings in Russian and ukrainian localizations.
* Corrected title of the Check for upgrade window.
* Improved update algorithm;

# Versión 4.5 #
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

# Versión 4.4.8 #
* Añadida la traducción en Polaco (gracias a Zvonimir Staneczyć).
* Compatibility with wx python version 4;

# Versión 4.4.1 #
* Added SSL support;

# Versión 4.4 #
* Corregido error en la lectura de la nueva cadena de la versión, durante un
  tiempo de espera de conexión.
* Improved the upgrade section; Now the dialog do not interferes with the
  nvda menu.
* Revised and corrected russian Localization.
* Adding Ukrainian translation (thanks to Alex Yeshanu).

# Versión 4.3.4 #
* Revisada y corregida la localización en Alemán.

# Versión 4.3.3 #
* Añadida la localización en Alemán (gracias a Karl Eick).

# Versión 4.3.2 #
* Añadida la localización en Rumano (gracias a Florian Ionașcu).

# Versión 4.3.1 #
* Fixed a minor bug in the function "details"; The strings "latitude" and
  "longitude" were reversed compared to the value.

# Versión 4.3 #
* Weather plus moved to the "nvda.it" as it's default hosting provider

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
* Añadidas nuevas cadenas a la lista de los informes meteorológicos.

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
  in inches of mercury; * Now the value is calculated in defect, while
  before it was in excess.

# Versión 3.9.5 #
* Añadido 2 nuevas cadenas a la lista de los informes meteorológicos.
* Se han corregido 2 errores.
* Updated running sounds for the effect in conditions of only wind; * Now
  the sound of the wind can vary randomly.

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

# Versión 3.7 #
* Añadida  la posibilidad de desactivar la conversión en metros por segundo
  del viento.
* Añadida la posibilidad de usar las unidades de medida en libras por
  pulgada cuadrada.
* Se han corregido 2 errores.

# Versión 3.6 #
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

# Versión 3.5 #
* Añadida Traducción en Croata (gracias a Gordan Radić).
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
* Añadida Traducción en Gallego (gracias a Iván Novegil).
* Añadida Traducción en  Portugués (gracias a Ângelo Miguel Abrantes).
* Añadida Traducción en Alemán (incompleta).

# Versión 3.3 #
* Se agregó la medida de la velocidad del viento en metros por segundo.
* encoding fixes

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

# Versión 3.0 #
* Added the slovak translation (thanks to the kind cooperation of Vitek
  Jirasek).
* Añadida traducción al Portugués de Brasil y al Portugués de Portugal
  (gracias a la amable colaboración de Adair Knaesel).
* Añadidas nuevas cadenas a la lista de los informes meteorológicos.
* Se añadieron 171 nuevos efectos de audio, ahora el número total es de 213.
* Añadido el comando insert+alt+w en el gesto, anuncia la última
  actualización del boletín meteorológico actual.
* Añadido scriptCategory que se mueve en la buena posición, las teclas
  rápidas de Weather Plus en "Gestos de Entrada..."

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

# Versión 2.9 #
* Añadida la opción al importar para seleccionar el contenido del archivo
  importado.
* Se añadieron cuatro nuevos efectos de audio.
* Añadida traducción al ruso (gracias a Alex Yeshanu).
* Añadida traducción al checo (gracias a Jirimu Holzingerovi).

# Versión 2.8 #
* Corregido bug en "detalles", solía abrir la ventana de las ocurrencias
  cuando no podía encontrar la ciudad.
* Fixed regexp to search for the altitude; It did not accept parameters of
  single digits.
* Improved parser of the edit box; It should find more easily the city.
* Connections now handled by urllib2, instead of urllib; * This should allow
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
* Added ability to read the Astronomic information; * Time of sunrise and
  sunset.

# Changes to the Weather Plus Settings window #

* Añadidas 3 casillas de verificación para manejar la información listada
  anteriormente.
* Added button " Details "; * Provides some information such as the real
  name of the city ( assigned by Yahoo Weather Forecast), the state / region
  and the nation to which it belongs; With geographic coordinates, and
  height above sea level.
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
* Añadido un comando en el gesto para cambiar temporalmente la escala de
  temperatura de Celsius a Fahrenheit, este comando también es efectivo en
  la ventana de configuración.
* Corregido un error, si el usuario no pulsó los botones "Añadir" o
  "Predeterminar", no permitió pronunciar el nombre de la ciudad, ya que no
  estaba incluído en la lista.
* Añadidas nuevas cadenas a la lista de los informes meteorológicos.

# Changes to the Weather Plus Settings window #

* Añadido botón para abrir una página web de búsqueda con el fin de
  comprobar los códigos postales de todo el mundo.
* Añadida la posibilidad de importar/exportar los códigos postales de tus
  amigos.
* Añadida la posibilidad de copiar el reporte del clima o el pronóstico del
  tiempo al portapapeles.
* Añadida la posibilidad de escuchar efectos de audio meteorológicos, la
  opción también permite la instalación/actualización de los efectos de
  audio.
* Añadido botones capacidad de ayuda en la gestión de Código Postal.
* Cambio al modo de visualización de la ventana, los menús de NVDA son
  desenfrenados cuando está abierto.

# Versión 2.4.4 #
* Añadido 2 nuevas cadenas a la lista de los informes meteorológicos.
* Se añadio  localización Español y Francés (gracias a Pablo Vargas y Rémy
  Ruiz).

# Versión 2.4.3 #
* Se añadio la previsión meteorológica para los próximos 4 días.
* Se añadio una cadena a la lista de los informes meteorológicos.
* La lista de código postal temporal está ahora ordenada a cada nueva
  inserción.

# Versión 2.4 #
* Se ha corregido un error que impedía guardar y administrar correctamente
  los nombres de las ciudades que contienen vocales acentuadas.

# Versión 2.3 #
* Cuadro de diálogo para establecer la escala de medición de temperatura
  Eliminado, ahora se ha agregado una nueva interfaz gráfica de usuario que
  le permite configurar todo en una sola ventana.
* También será posible probar / añadir / eliminar / predeterminar el Código
  Postal por defecto establecido en una lista.
* Modificado el cuadro de diálogo para introducir por escrito un código
  postal, ahora en el modo temporal le permite establecer un Código Postal
  previamente añadido a la lista   en el menú Preferencias.
* Ahora la documentación se puede leer en Inglés si la configuración del
  idioma no está incluida en los documentos.

# Versión 2.2 #
* Solucionado un problema que no le permitía abrir la documentación de las
  versiones definitivas de NVDA.

# Versión 2.1 #
* Se ha corregido un error que no cerraba correctamente el plugin, lo que
  impedía la actualización del icono de NVDA en la bandeja del sistema.

# Versión 2.0 #
* El menú de configuración de Weather Plus    se ha movido al submenú
  Preferencias.
* correct input on the fly is no longer saved, so it is temporary; To call
  the city set in the preferences, press INSERT + control + f3.

# Versión 1.9 #
* añadida ayuda para entrar en funciones.
* añadida una nueva función para ingresar rápidamente un Código Postal.
* añadido al weather.ini la configuración de lectura / escritura, ahora ya
  no tendrá que editar el archivo de origen.
* Añadido El menú Weather a la bandeja del sistema.
* añadido el submenú establecer Código postal.
* añadida sub-configuración escala de temperatura (Fahrenheit o Celsius).
* añadido menú Documentación.
* Añadido localización italiano.

# Initial Version 1.1 #
* updated the NVDA-addon.
* Translation support has been added.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
