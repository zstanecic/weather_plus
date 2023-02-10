# Weather Plus #

* Tekijä: Adriano Barbieri
* Yhteensopivuus: NVDA 2017.3 ja uudemmat
* Lataa [vakaa versio][1]

# Tietoa Weather Plus:sta: #

* Tämä lisäosa lisää NVDA:han paikalliset lämpötila- ja sääennusteet 24
  tunnin ajalta aina 2 päivään saakka, ja lisäksi tuntiennusteen.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Julkaistu GNU GPL (General Public License) v2 -lisenssin alaisuudessa
* Weather Plus käyttää seuraavia palveluita:
* [https://www.weatherapi.com/](https://www.weatherapi.com/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# Käyttö: #

* Saat selville nykyisen lämpö- ja säätilan painamalla NVDA+W.
* Saat ennusteen 24 tunnin ajalle aina 2 päivään saakka painamalla
  NVDA+Vaihto+W.
* Saat selville tuntiennusteen lämpötilasta ja ilmakehän olosuhteista
  painamalla kahdesti NVDA+Vaihto+W.
* Määritä väliaikainen kaupunki painamalla NVDA+Vaihto+Ctrl+W.
* Avaa Weather Plus:n asetusvalintaikkuna painamalla NVDA+Vaihto+Ctrl+Alt+W.
* Saat selville sääennusteen päivitysajankohdan painamalla NVDA+Alt+W.
* Vaihda Fahrenheit-, celsius- tai Kelvin-asteikon välillä painamalla
  Ctrl+Vaihto+W.

# Weather Plus:n asetusten määritys: #

* Weather Plus:n asetukset on määritettävä ennen sen ensimmäistä käyttökertaa. Valitse NVDA-valikosta Asetukset -> Weather Plus ja valitse sitten jokin seuraavista vaihtoehdoista:
 * Määritä ja hallinnoi kaupunkeja...: Näyttää nykyisen kaupungin tai mahdollistaa sen valitsemisen luettelosta.
 * Määritä väliaikainen kaupunki...: Näyttää nykyisen väliaikaisen kaupungin tai mahdollistaa sen valitsemisen luettelosta.
 * Dokumentaatio: Avaa ohjetiedoston nykyisellä kielellä.
 * Tarkista päivitys...: Ilmoittaa, jos uusi versio on saatavilla.

Lisää uusi kaupunki painamalla seuraavaa painiketta:

* Määritä ja hallinnoi kaupunkeja...: Näyttää nykyisen kaupungin tai
  mahdollistaa sen valitsemisen luettelosta.
* Seuraava ilmoitus näytetään vain ensimmäisellä
  käyttökerralla. Oletuskaupunki Ei mitään F1: ohje, F2: viimeisimmän
  välilehden valitseminen, F3: luettelo- ja muokkausruutu, F4: muuta
  sääennusteen kestoa, F5: äänenvoimakkuuden säätimet.
* Kirjoita tähän muokkauskenttään kaupunki tai valitse se luettelosta. Huom:
  F5-näppäin on käytettävissä, mikäli äänitehosteet on otettu käyttöön.
* Kun olet valinnut "Määritä ja hallinnoi kaupunkeja..." -kohdan,
  käytettävissä ovat seuraavat painikkeet:
* Testaa: Testaa kaupungin kelvollisuus ja hae sen tiedot.
* Lisää: Lisää nykyisen kaupungin luetteloon. Tämä painike on käytettävissä,
  jos valitset luettelosta kaupungin tai mikäli se on läpäissyt testin.
* Tiedot: Näyttää nykyisen kaupungin tiedot. Tämä painike on käytettävissä,
  jos valitset luettelosta kaupungin tai mikäli se on läpäissyt testin.
* Määritä: Voit määrittää alueen äänitehosteiden mukauttamiseksi. Tämä
  painike on käytettävissä, mikäli äänitehosteet on asennettu ja ne ovat
  käytettävissä, ja valitset luettelosta kaupungin.
* Aseta oletukseksi: Määrittää kaupungin oletukseksi, jolloin sitä käytetään
  aina, kun käynnistät lisäosan uudelleen. Tämä painike on käytettävissä,
  mikäli valitset luetteloon aiemmin lisätyn kaupungin, jota ei ole asetettu
  oletukseksi, tai joka on läpäissyt testin.
* Poista: Poistaa nykyisen kaupungin luettelosta. Tämä painike on
  käytettävissä, mikäli valitset luetteloon aiemmin lisätyn kaupungin, jota
  ei ole asetettu oletukseksi, tai joka on läpäissyt testin.
* Nimeä uudelleen: Nimeä nykyinen kaupunki uudelleen. Tämä painike on
  käytettävissä, mikäli valitset luetteloon aiemmin lisätyn kaupungin, jota
  ei ole asetettu oletukseksi, tai joka on läpäissyt testin.
* Tuo uusia kaupunkeja...: Tällä painikkeella voit tuoda kaupunkeja
  tiedostosta, jonka pääte on .zipcodes. Valitse tuotava kaupunki
  valitsemalla sitä vastaava valintaruutu.
* Vie kaupunkeja...: Tällä painikkeella voit tallentaa kaupunkeja
  tiedostoon, jonka pääte on .zipcodes. Toiminto aktivoidaan, jos olet
  lisännyt ja tallentanut luettelooon vähintään yhden kaupungin.
* Tuntiennusteen asetukset...: Tällä painikkeella voit valita
  tuntiennusteraportin sisällön.
* Lämpötilamittauksen asteikko: Käytä tätä valintapainiketta valitaksesi
  asteikoksi Celsius (oletuksena), Fahrenheit tai Kelvin.
* Asteet näytetään muodossa: Käytä tätä valintapainiketta valitaksesi
  seuraavien vaihtoehtojen väliltä: Celsius `-` Fahrenheit `-` Kelvin
  (oletuksena), C `-` F `-` K tai Ei määritetty.
* Sääennuste näin monelle päivälle: Tästä yhdistelmäruudusta voit valita
  sääennusteen 1-3 päivälle (oletusarvoisesti yksi päivä)
* Ohjelmointirajapinnan vastauksen kieli: Tästä yhdistelmäruudusta voit
  valita säätilan tekstin kielen (oletusarvoisesti englanti).
* Valitse seuraavat valintaruudut suorittaaksesi niiden toiminnot:
* Kopioi sääraportti ja -ennuste leikepöydälle (kaupungin tiedot mukaan
  lukien): Tätä valintaruutua ei ole oletusarvoisesti valittu.
* Ota käyttöön äänitehosteet (vain nykyiselle säätilalle): Tällä
  valintaruudulla voit myös hallita äänitehosteiden asennusta. Mikäli
  äänitehosteet on asennettu ja valintaruutu valitaan, F5-näppäin ja
  äänenvoimakkuusasetus ovat käytettävissä.
* Käytettävissä on myös ylimääräinen valintaruutu: "Käytä vain
  säätehosteita".
* Voit muuttaa yleistä äänenvoimakkuutta tai muuttaa viimeksi kuultua
  äänitehostetta ja suodattaa pois muut äänet ympäristöstäsi. Tätä
  valintaruutua ei ole valittu oletuksena.
* Käytä vain säätehosteita: Tämä vaihtoehto on käytettävissä, jos
  äänitehosteet ovat käytössä. Mikäli tämä asetus on käytössä, vain
  säätehosteet, kuten sade, tuuli, ukkonen jne. sallitaan suodattaen pois
  kaikki ympäristötehosteet (ei ole oletusarvoisesti valittuna).
* Ilmoita aika 24 tunnin muodossa: Jos tätä valintaruutua ei ole valittu,
  kellonaika ilmoitetaan 12 tunnin muodossa, esim. 12 AM `-` 12
  PM. Valintaruutu on oletusarvoisesti valittuna.
* Ota käyttöön asetusikkunan ohjepainikkeet: Tämä valintaruutu on
  oletusarvoisesti valittuna.
* Lue tuulitiedot: Tämä valintaruutu ei ole oletusarvoisesti
  valittuna. Mikäli se on valittuna, voit valita myös seuraavat
  valintaruudut:
* Lisää tuulen suunta: Ilmaisee suunnan, josta tuuli puhaltaa. Tämä
  Valintaruutu on oletusarvoisesti valittuna.
* Lisää tuulen nopeus: Ilmaisee tuulen nopeuden kilometreinä tai maileina
  tunnissa. Tämä valintaruutu on oletusarvoisesti valittuna.
* Lisää tuulen nopeus metreinä sekunnissa: Tämä valintaruutu on
  oletusarvoisesti valittuna.
* Lisää tuulen nopeus puuskissa: Tämä valintaruutu on oletusarvoisesti
  valittuna.
* Lisää havaittu lämpötila: Tämä valintaruutu on oletusarvoisesti valittuna.
* Lue ilmakehän tiedot: Tätä valintaruutua ei ole oletusarvoisesti
  valittu. Jos se on valittuna, voit valita myös seuraavat valintaruudut:
* Lisää kosteusarvo: Ilmaisee kosteuden prosentteina. Tämä valintaruutu on
  oletusarvoisesti valittuna.
* Lisää näkyvyysarvo: Ilmaisee näkyvyyden kilometreinä tai maileina. Tämä
  valintaruutu on oletusarvoisesti valittuna.
* Lisää ilmakehän painearvo: Ilmaisee ilmakehän paineen millibaareina tai
  elohopeatuumina. Mikäli tämä  valintaruutu on valittuna, ota käyttöön myös
  ylimääräinen valintaruutu, joka ilmoittaa paineen
  elohopeamillimetreinä. Tämä valintaruutu on oletusarvoisesti valittuna.
* Lisää ilmanpaineen tila: Tämä valintaruutu on oletusarvoisesti valittuna.
* Lisää pilvisyysarvo: Tämä valintaruutu on oletusarvoisesti valittuna.
* Lisää sademäärä: Tämä valintaruutu on oletusarvoisesti valittuna.
* Lisää ultraviolettisäteilyn arvo: Tämä valintaruutu on oletusarvoisesti
  valittuna.
* Lue tähtitieteelliset tiedot: Ilmaisee auringonnousun ja -laskun sekä kuun
  nousun ja laskun kellonajan. Tätä valintaruutua ei ole oletusarvoisesti
  valittu.
* Käytä pilkkua desimaalierottimena: Jos tämä on käytössä, pilkkua käytetään
  desimaalierottimena. Muutoin käytetään pistettä. Tätä valintaruutua ei ole
  oletusarvoisesti valittu.
* Tarkista päivitykset: Jos tämä on käytössä, lisäosa näyttää ilmoituksen,
  kun päivitys on saatavilla. Tämä valintaruutu on oletusarvoisesti
  valittuna.
* Vahvista toiminto painamalla OK-painiketta tai peruuta painamalla
  Peruuta-painiketta.
* Mikäli olet muokannut kaupunkien luetteloa, sinua muistutetaan siitä
  painaessasi Peruuta-painiketta, ja voit edelleen tallentaa tekemäsi
  muutokset. Huom: Asetukset tallennetaan tiedostoon:
* "Weathe r.ini": Weather Plus:n asetukset.
* "Weather.volumes": mukautetut äänenvoimakkuuden tasot, jotka eivät ole
  riippuvaisia yleisestä äänenvoimakkuudesta .
* "Weather.zipcodes": Luettelo kaupungeista sekä niiden postinumeroista ja
  muista määrityksistä.
* "Weather.default": Oletuskaupunki.
* "Weather_searchkey": Tallennettu hakusana.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
