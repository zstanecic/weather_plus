# Időjárás-előrejelző #

* Készítő: Adriano Barbieri
* NVDA compatibility: 2017.3 to beyond
* [Stabil Verzió][1] letöltése

# Az időjárás-előrejelzőről: #

* This plugin adds local temperature and forecasts to 24 hours up to 2
  additional days and hourlyforecast for NVDA.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* A GNU GPL (Általános nyilvános Licenc) v2 hatálya alá tartozik.
* Az Időjárás-előrejelző az alábbi szolgáltatásokat használja:
* [https://www.weatherapi.com/](https://www.weatherapi.com/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# Billentyűparancsok: #

* NVDA+w: Aktuális hőmérséklet és időjárási viszonyok lekérdezése.
* Press NVDA+shift+W to get 24 hours forecast and forecast up to 2 days.
* Press NVDA+shift+W twice to get hourlyforecast of temperature and
  atmospheric conditions.
* NVDA+Shift+Ctrl+w: ideiglenes város beálítása
* NVDA+shift+ctrl+alt+w: Az időjárás-előrejelző beállításai
* NVDA+Alt+w: megadja, hogy mikor frissültek legutóbb az időjárási adatok.
* Ctrl+Shift+w: Váltás a hőmérsékleti skálák között (Fahrenheit, Celsius és
  Kelvin)

# Az Időjárás-előrejelző beállítása #

* You must set the Weather Plus addon before its first use! Go to the Preferences submenu, Weather Plus Settings submenu and choose one of the following options:
 * Set and Manage Your Cities... - Displays or allows to set the current city from a list.
 * Set a temporary city... - Displays and allows to set one temporary city from a list if available.
 * Documentation - Opens the help file for the current language.
 * Check for Update... - Notifies about the availability of the new version.

Új város hozzáadásához használja a következő menüpontot

* Városok beállítása és kezelése... - Városok megjelenítése, vagy
  importálása egy listából.
* A következő üzenet csak az első alkalommal jelenik meg: Beállítások
  Alapértelmezett nincs megadva F1: Súgó, F2: utolsó kijelölt lapfül, F3:
  Lista és szerkesztőmező, F4: Előrejelzés napok száma, F5: Hangerő.
* In the edit box, enter a City or choose one from the list, if
  available. Note: The F5 key is available if the sound effects are
  activated.
* A párbeszédpanelen az alábbi gombok találhatók:
* Test - Test the validity of the city and find the data of it.
* Hozzáadás - Hozzáadja a jelenlegi várost a listához. A gomb csak akkor
  aktiválható ha a listáról választott várost vagy pedig a beírt város
  szerepel az adatbázisban, azaz megfelelt az ellenőrzésen.
* Részletek - Részleteket jelenít meg a jelenlegi városról. A gomb csak
  akkor működik, ha a megadott várost már elfogadta a rendszer.
* Definiálás - Megadható a régió típusa a hangeffektek hozzárendeléséhez. A
  gomb csak akkor működik, ha a hangeffektek telepítve és aktiválva vannak.
* Alapértelmezett - Beállítja a jelenlegi várost alapértelmezett helyként,
  mindig ez fog megjelenni, amikor a bővítmény elindul. Csak olyan várost
  lehet megadni alapértelmezettként, amit a rendszer már elfogadott.
* Eltávolítás - Eltávolítja a jelenlegi várost a listáról.
* Átnevezés - Átnevezi a jelenlegi várost. Csak olyan várost lehet
  átnevezni, ami már szerepel a saját városok listáján.
* Városok importálása - Új városokat adhat hozzá *.zipcodes kiterjesztésű
  fájlokból. Csak azok a városok kerülnek fel a saját városok listájára,
  amiknél bejelöli a megfelelő jelölőnégyzetet.
* Városok exportálása - Elmenti a városlistát egy megadott *.zipcodes
  kiterjesztésű fájlba. A funkció csak akkor működik, ha legalább egy várost
  már felvett a listájára.
* hourly forecast setting... - This button allows you to choose the contents
  of the hourly forecast report.
* Hőmérsékleti skála - Használja a választógombot a kívánt skála
  beállításához. Celsius az alapértelmezett beállítás, de választhat még
  Fahrenheit és kelvin közül is.
* Mértékegység megjelenítése - Itt lehet beállítani, hogyan jelenjenek meg a
  hőfok értékek egységei a beállítottt skálának megfelelően. Teljes névvel,
  egybetűs jelöléssel, vagy ne jelenjen meg mértékegység az értékek után.
* Combo box: Weather Forecasts up to days: 1; you can choose between 1 to 3
  (1 days by default)
* Combo box: API response language: English, en; you can choose the language
  of the weather conditions text.
* A következő opciók használatához jelölje be a jelölőnégyzeteket:
* Időjárás-előrejelzés másolása a vágólapra, a város részletes adataival
  együtt - alapértelmezés szerint ki van kapcsolva.
* Hangeffektek az időjárási viszonyokhoz - Ezzel a jelölőnégyzettel lehet
  kezelni a hangeffekteket. Amennyiben az effektek telepítve vannak és a
  jelölőnégyzet is be van jelölve, elérhetővé válik a hangerő beállítása is.
* Kapcsolódó opció: Csak időjárási hangok.
* Megváltoztathatja a hangerőt és az utoljára hallott effektet. A
  jelölőnégyzet alapértelmezés szerint ki van kapcsolva.
* Csak időjárási hangok - Ha be van jelölve,akkor a program csak az
  időjárási hangokat játssza le a környékhez kapcsolódó hangokat
  nem. Alapértelmezés szerint ki van kapcsolva.
* 24 órás formátum - Ha a jelölőnégyzet nincs bejelölve, a bővítmény által
  megjelenített helyi idők 12 órás formátumban lesznek hallhatók. Pl. 10 AM,
  13 PM. Alapértelmezés szerint be van kapcsolva.
* Súgószövegek a gombokon - Alapértelmezés szerint be van jelölve.
* Szélviszonyok - A jelölőnégyzet bejelölése után további opciók jelennek
  meg. Itt lehet megadni, hogy milyen információkat szeretnénk az
  előrejelzésben a szélviszonyokról.
* Szélirány
* Szélsebesség
* Szélsebesség méter per szekundumban - ha nincs bejelölve akkor az érték
  kilométer per órában jelenik meg.
* Add wind gust speed of the wind; checkbox checked (by default)
* Hőérzet - a szél befolyása a mért hőmérséklet érzékelésére.
* Légköri viszonyok - Bejelölés után további opciókat lehet elérni:
* Páratartalom - a levegő páratartalma százalékban
* Látótávolság - kilométerben vagy mérföldben.
* Légnyomás - a bejelölés után megadható, hogy milyen mértékegységben
  szeretnénk. Légnyomás higanymilliméterben (mmHg) jelölőnégyzet ha be van
  jelölve, akkor a légnyomás értéke higanymilliméterben, ha nincs bejelölve
  akkor barban jelenik meg.
* Légnyomás tendenciája - Stagnál, emelkedik vagy csökken.
* Add cloudiness value; check box checked (by default)
* Add precipitation value; check box checked (by default)
* Add ultraviolet radiation value; check box checked (by default)
* Read astronomical information; indicates the time of sunrise and sunset
  and the time of moonrise and moonset. Checkbox not checked (by default)
* Tizedesvessző használata pont helyett - ha be van jelölve,akkor a
  tizedesértékeket tizedesvesszővel választja el, ha nincs bejelölve, akkor
  ponttal.
* Frissítések keresése - ha be van jelölve, akkor mindig figyelmeztet, ha a
  bővítményhez frissítés érhető el. A bővítmény saját frissítési rendszerrel
  működik, nem szerepel a Bővítményfrissítőben.
* Az Ok gomb lenyomásával jóváhagyhatja a beállításokat, a mégse gomb
  lenyomásával marad minden a korábbi állapotában.
* Ha módosította a városok listáját és mégis a mégse gombot nyomja meg, a
  program figyelmeztet, és lehetővé teszi a városok listájának mentését a
  többi beállítástól függetlenül.A program beállításai az alábbi fájlokban
  találhatók:
* "Weather.ini": Indítási beállítások
* "Weather.volumes": Egyéni hangerőértékek.
* "Weather.zipcodes": a városok listája WOEID kódjukkal és a részleteikkel.
* "Weather.default": Your default city.
* "Weather_searchkey": mentett keresőszó

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
