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

# USO: #

* Premere NVDA+w per ottenere le informazioni sulla temperatura attuale e
  condizione meteo.
* Premere NVDA+shift+W per ottenere la previsione a 24 ore e previsione fino
  a 9 giorni successivi.
* Premere NVDA+shift+control+w per impostare una città temporanea.
* Premere NVDA+shift+control+alt+w per aprire la finestra impostazioni di
  Weather Plus.
* Premere NVDA+alt+w per ottenere la data e l'ora dell'ultimo aggiornamento
  del bollettino meteo.
* Premere shift+control+w per alternare la scala di misura tra Fahrenheit,
  Centigradi o Kelvin.

# Impostare Weather Plus: #

* È necessario impostare l'addon Weather Plus prima del primo utilizzo! Vai al sottomenu Preferenze, sottomenu Impostazioni Weather Plus e scegliere una delle seguenti opzioni:
 * Impostazioni e Gestione delle tue città... - Visualizza o consente di impostare una città da un elenco.
 * Documentazione - Apre la documentazione per la lingua corrente.
 * Controllo presenza aggiornamenti... - Notifica se è disponibile una versione aggiornata.

Per aggiungere una nuova città: premere il seguente elemento:

* Impostazioni e Gestione delle tue città... - Visualizza o consente di
  impostare una città da un elenco.
* Solo per la prima volta, viene visualizzato il messaggio seguente!
  Impostazioni Preimpostato Nessuno F1: aiuto immissione, F2: ultima
  selezione con TAB, F3: elenco e casella di editazione, f4: controllo
  durata previsioni meteo, F5: controlli volume.
* Nella casella di modifica, immettere una città, woeId o sceglierne uno
  dall'elenco, se disponibile. Nota: Il tasto F5 è disponibile se gli
  effetti sonori sono attivati.
* Dopo aver premuto Invio sulla voce "Impostazioni e Gestione delle tue
  città...", si trova altri pulsanti come segue:
* Testa - Testa la validità del woeID immesso e trova il nome della città
  assegnatogli, o viceversa.
* Aggiungi - Aggiunge la città corrente al tuo elenco. Questo pulsante viene
  attivato se si seleziona una città dall'elenco, o ha superato il test.
* Dettagli - Visualizza informazioni sulla città corrente. Questo pulsante
  viene attivato se si seleziona una città dall'elenco, o ha superato il
  test.
* Definisci - Permette di definire l'area, al fine di adeguare gli effetti
  sonori. Questo pulsante viene attivato se gli effetti sonori sono
  installati e attivati, e si seleziona una città dall'elenco.
* Preimpostato - Predispone la città come predefinita, verrà utilizzata ogni
  volta che si riavvia il plugin. Questo pulsante viene attivato se si
  seleziona una città precedentemente inserita nell'elenco e non
  preimpostata o ha superato il test.
* Rimuovi - Elimina la città corrente dall'elenco. Questo pulsante viene
  attivato se si seleziona una città precedentemente inserita nell'elenco.
* Rinomina - Rinomina la città corrente. Questo pulsante viene attivato se
  si seleziona una città precedentemente inserita nell'elenco.
* Importa nuove città... - Questo pulsante permette di importare città da un
  altro elenco delle città con estensione *.zipcodes; puoi selezionare la
  città che vuoi importare, attivando la casella di controllo associata.
* Esporta le tue città... - Esso consente di salvare le città nel file
  specificato con estensione *.zipcodes. Questo pulsante viene attivato se
  avete aggiunto e salvato almeno una città nell'elenco.
* Scala di misura della temperatura: Utilizzare il Pulsante radio per
  selezionare tra Centigradi (predefinito), Fahrenheit e Kelvin.
* Indica i gradi come: Utilizzare il Pulsante radio per selezionare tra:
  Centigradi `-` Fahrenheit `-` Kelvin (predefinito) C `-` F `-` K o Non
  specificato.
* Casella combinata: Previsioni del tempo fino a giorni: 3; selezionare tra
  1 a 10 (3 giorni predefinito)
* Per eseguire le seguenti azioni, attivare o disattivare le seguenti
  caselle di controllo:
* Copia il bollettino meteo e previsioni del tempo, compresi i dettagli
  della città negli appunti; casella di controllo non attivata (per
  impostazione predefinita)
* Abilita effetti audio (solo per le condizioni meteo attuali); questa
  casella di controllo permette anche di gestire l'installazione di effetti
  sonori; se sono installati gli effetti sonori e la casella di controllo è
  attivata, il tasto F5 e l'impostazione del volume diventano disponibili.
* Sarà inoltre disponibile una casella di controllo aggiuntiva: "Usa solo
  effetti atmosferici".
* È possibile modificare il volume generale o modificare l'ultimo effetto
  sonoro sentito e filtrare gli altri suoni ambientali. Questa casella di
  controllo è non attivata per impostazione predefinita.
* Usa solo effetti atmosferici - Questa opzione è disponibile se gli effetti
  sonori sono abilitati; se attivata permette di ascoltare solo effetti
  atmosferici come pioggia, vento, tuoni, ecc., filtrando tutti quelli
  ambientali. (non attivata per impostazione predefinita)
* Abilitare la lettura delle ore in formato 24-ore. - Se questa casella di
  controllo è disattivata, annuncia l'ora in 12-ore formato, esempio: 12 AM
  - 12 PM. Questa casella di controllo è attivata (per impostazione
  predefinita)
* Abilita aiuto pulsanti nella finestra delle impostazioni; casella di
  controllo attivata (per impostazione predefinita)
* Leggi le informazioni del vento; casella di controllo non attivata (per
  impostazione predefinita). Se attivata è anche possibile abilitare le
  seguenti caselle di controllo:
* Aggiungi la direzione del vento; indica la provvenienza del vento. Casella
  di controllo attivata (per impostazione predefinita)
* Aggiungi la velocità del vento; indica la velocità in chilometri o miglia
  orarie. Casella di controllo attivata (per impostazione predefinita)
* Aggiungi la velocità del vento in metri al secondo; casella di controllo
  attivata (per impostazione predefinita)
* Aggiungi la temperatura percepita; casella di controllo attivata (per
  impostazione predefinita)
* Leggi informazioni atmosferiche; casella di controllo non attivata (per
  impostazione predefinita). Se attivata è anche possibile abilitare le
  seguenti caselle di controllo:
* Aggiungi valore dell'umidità; indica l'umidità in percentuale. Casella di
  controllo attivata (per impostazione predefinita)
* Aggiungi valore della visibilità; indica in chilometri o miglia la
  distanza visibile. Casella di controllo attivata (per impostazione
  predefinita)
* Aggiungi valore della pressione atmosferica; indica la pressione in
  millibar o pollici di mercurio. Se è attivata, abilita una ulteriore
  casella di controllo che permette di indicare la pressione in millimetri
  di mercurio. Casella di controllo attivata (per impostazione predefinita)
* Aggiungi lo stato della pressione barometrica; casella di controllo
  attivata (per impostazione predefinita)
* Leggi le informazioni astronomiche; indica l'ora del alba e
  tramonto. Casella di controllo non attivata (per impostazione predefinita)
* Usa la virgola per separare i decimali; se attivata usa la virgola come
  separatore decimale, in caso contrario, utilizza il punto. Casella di
  controllo non attivata (per impostazione predefinita)
* Controllo presenza aggiornamenti; se è attivata avvisa quando c'è un
  aggiornamento del componente aggiuntivo. Casella di controllo attivata
  (per impostazione predefinita)
* Premere il pulsante OK per confermare l'azione o il pulsante Annulla per
  annullare l'azione.
* Se avete modificato la lista delle città, premendo "Annulla", vi sarà
  ricordato e potrete ancora salvarla. Nota: le impostazioni verranno
  salvate nei file denominati:
* "Weather.ini": impostazioni di avvio di Weather Plus.
* "Weather.volumes": livelli volume audio personalizzati, a prescindere dal
  volume generale.
* "Weather.zipcodes": lista delle città con rispettivi zip code e
  definizioni.
* "Weather_searchkey": chiavi di ricerca salvate.

--------------------------------------------------------------------------------

# Novità: #

# Versione 7.4 #

* Corretto un bug in una funzione di ricerca della città.

# Versione 7.3 #

* Corretto bug imprevisto in caso di pagina non trovata durante la ricerca
  di aggiornamenti.

# Versione 7.2 #

* Risolto bug dopo l'aggiunta della prima città, quando si preme il pulsante
  ok e si riavvia il componente aggiuntivo.
* Ora la finestra progressiva di dialogo mostra nuovamente il tempo
  rimanente e il tempo trascorso.
* Corretta traduzione in Italiano dell'aiuto del pulsante Rinomina.

# Versione 7.1 #

* Corretto bug di aggiornamento.

# Versione 7.0 #

* Finestra di ricerca migliorata, ora è possibile gestire le chiavi di
  ricerca inserire, aggiungere, eliminare e salvarle dal menu contestuale.
* Controllo dell'apertura delle finestre migliorato.
* Corretti alcuni piccoli bug.

# Versione 6.9 #

* Implementata la ricerca di città ricorrenti tramite il sistema adottato in
  precedenza nella versione Apixu di Weather_Plus.
* Premere f1 nella finestra delle impostazioni per una spiegazione dei
  comandi disponibili.

# Versione 6.8 #

* Aggiornata compatibilità per Python 3.

# Versione 6.7 #

* Risolto un bug che si manifestava testando una nuova città e usandola in
  modalità temporanea premendo semplicemente "invio" e in un secondo momento
  provando ad aggiungerla tramite il bottone "Aggiungi".
* Aggiunto abbreviazione per SOUTH GEORGIA AND THE SOUTH SANDWICH ISLANDS al
  database, ma purtroppo al momento sembra che le città di questo stato non
  funzionino o hanno dati incompleti, speriamo che sarà risolto presto.

# Versione 6.5 #

* Corretti un paio di bug nella riproduzione degli effetti sonori; un paio
  di cicli "for" con valore massimo errato causavano la chiamata ad un
  effetto sonoro inesistente.
* Corretto bug nell'ora locale in "dettagli"; La conversione del tempo in 12
  ore dava un errore.
* Corretto un bug nelreport di Yahoo Weather Forecast; in alcune città le
  previsioni partono dal giorno precedente e non da quello attuale. La
  correzione di queste città comporta la perdita degli ultimi giorni di
  previsione proporzionale alla mancata corrispondenza delle date (se i
  giorni di previsione sono impostati su 10).

# Versione 6.4 #

* Rimossa l'ora legale nella funzione "Dettagli".
* Migliorata la riproduzione degli effetti audio; ora si aggiornano
  regolarmente se cambiano le condizioni meteorologiche.

# Versione 6.3 #

* Risolto problemi di codifica.

# Versione 6.2 #

* Corretto bug nella funzione "Aggiungi città".
* Corretto bug che non assegnava la variabile "_volume" all'avvio
  dell'addon.
* Aggiunto codice mancante dalla versione 6.0; ora è possibile recuperare le
  città salvate dalla versione che utilizza l'API di Apixu; vengono resi
  disponibili i pulsanti "Testa" e "Rimuovi" e le città non compatibili nel
  formato :"Ferrara, iter 44.83,11.58 0" (città, coordinategeografiche,
  definizione area).

# Versione 6.1 #

* Coorretti 2 bug.

# Versione 6.0 #

* Weather Plus torna a utilizzare l'API di Yahoo Weather.
* Praticamente tutte le funzionalità della precedente versione 4.8 sono
  tornate e mantiene il pulsante "Rinomina".
* Compatibilità con Python 3.

# Versione 5.0.1 #

* Corretto bug che restituiva una stringa vuota se la velocità del vento in
  mph era 0.
* Corretto bug che causava la riproduzione di effetti sonori non coerenti
  con il fuso orario.
* Corretto il numero di giorni di previsione da 9 a 6 in readme.

# Versione 5.0 #

* Weather Plus ora utilizza l'API APIXU.

# Modifiche nella finestra Impostazioni di Weather Plus #

* Rimossa la vecchia casella di controllo "Stato della pressione
  barometrica". Sostituito con la nuova casella di controllo "Aggiungi
  valore della nuvolosità";
* Dà la percentuale di nuvolosità atmosferica.
* Aggiunta nuova casella di controllo "Aggiungi valore di
  precipitazione". Dà la quantità in millimetri di precipitazione
  atmosferica.
* Rimossa la casella di controllo "Indica l'attesa con un segnale acustico
  durante la ricerca dell'ultimo bollettino"; ora è attiva per impostazione
  predefinita.
* Aggiunto le informazioni astronomiche;
* Orario del sorgere e tramonto della luna.
* Aggiunto nuovo pulsante "Rinomina"; per rinominare le città più
  convenientemente.
* Funzione migliorata del pulsante "Test"; ora accetta alcuni comandi per
  facilitare la ricerca delle città; questi nuovi comandi sono descritti
  nella funzione di aiuto che può essere richiamata con F1.

# Versione 4.8 #

# Modifiche nella finestra Impostazioni di Weather Plus #

* Aggiunta nuova casella di controllo; "Usa solo effetti atmosferici";
  questo permette di filtrare tutti gli altri effetti ambientali.
* Migliorata la riproduzione casuale e sono stati aggiunti 71 nuovi effetti
  sonori; sarà necessario aggiornarli dalle impostazioni del plugin
  cliccando due volte la casella di controllo "Abilita effetti audio".
* Il tipo di volume assegnato dall'utente, tra generale e corrente, ora è
  mantenuto quando la configurazione viene salvata.
* Rimosso l'inutile suono durante la selezione di testo nella casella di
  editazione premendo ctrl+a.
* Migliorata la leggibilità nella finestra di aiuto richiamabile con il
  tasto funzione F1.
* Aggiunti nuovi flag di compatibilità per NVDA 2019.1, e le attuali
  versioni alpha.

# Versione 4.7.7 #

* Rimossa la superflua notifica di download completato durante
  l'aggiornamento di Weather Plus.
* Aggiunti 6 nuovi effetti sonori; sarà necessario aggiornarli dalle
  impostazioni del plugin.

# Versione 4.7.6 #

* Versione correzione di un bug.

# Versione 4.7.5 #

* Versione correzione di un bug.

# Versione 4.7.3 #

* Per convenienza è stata aggiornata la funzione "dettagli"; le informazioni
  sull'altitudine sono ora fornite da veloroutes.org. Questo porta a piccole
  differenze di poca rilevanza.

# Versione 4.7.2 #

* Corretto piccolo bug di codifica.

# Versione 4.7.1 #

* Risolto un bug quando ottiene le informazioni sul fuso orario.

# Versione 4.7 #

* Semplificata la sezione di aggiornamento; ora all'avvio, in caso di
  aggiornamento disponibile sarà possibile procedere direttamente tramite
  un'unica finestra di dialogo.
* Rimosso il file selettore nella sezione di aggiornamento; ora il file di
  aggiornamento viene salvato nella cartella temporanea, si apre la
  possibilità di installare l'aggiornamento automatico, buono per i
  principianti.

# Versione 4.6.9 #

* Aggiunta localizzazzione in Arabo (grazie a Wafik Immaculate).

# Versione 4.6.8 #

* Aggiornata localizzazione Portoghese Brasiliano e Portoghese Europee
  (grazie ad Alberto Mendonça).

# Versione 4.6.7 #

* Migliorata ulteriormente la lettura dell'ora corrente; in alcune città non
  era corretta. Aggiunta l'ora legale ai dettagli; disponibile solo per i
  paesi che la adottano.

# Versione 4.6.5 #

* Corretto bug durante lettura dell'ora.

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

* Aggiunta la voce di menu "Imposta una città temporanea..."; per
  completezza, ora si può aprire una città temporanea anche dal menu.
* Migliorata la gestione della scala di temperatura; ora la finestra
  impostazioni restituisce sempre il valore di default.
* Miglioramento nella prevenzione di multiple aperture delle finestre
  principali; se una di queste è già aperta, oltre al suono di avviso, la
  pone in primo piano.
* Miglioramento negli effetti audio; ora sono basati sull'ora locale
  corrente della città in uso.

# Modifiche nella funzione del pulsante dettagli nella finestra impostazioni #

* Aggiunta l'ora locale corrente.
* Corretto il valore di altitudine; ora riporta i valori di altitudine anche
  quando il valore è minore o uguale a zero.

# Versione 4.5.5 #

* Corretta la localizzazione e la documentazione in serbo.
* Corretta la localizzazione in tedesco.

# Modifiche nella finestra Impostazioni di Weather Plus #

* Aggiunto una nuova casella di controllo; è possibile attivare la virgola
  come separatore decimale, altrimenti il separatore sarà il punto.

# Versione 4.5.3 #

* Corrette 2 stringhe in localizzazione Russa e Ucraina.
* Corretto il titolo della finestra Controllo presenza aggiornamenti.
* Migliorato l'algoritmo di aggiornamento.

# Versione 4.5 #

* Aggiunto il tasto di scelta rapida NVDA+shift+control+alt+w; Si apre la
  finestra di dialogo impostazioni di Weather Plus.
* Corrette alcune stringhe inglesi.

# Modifiche nella finestra Impostazioni di Weather Plus #

* Aggiunte 8 nuove caselle di controllo; sarà ora possibile personalizzare
  ulteriormente l'output su:
* Direzione del vento.
* Velocità del vento.
* Temperatura percepita.
* Valore dell'umidità.
* Valore della visibilità.
* Valore della pressione atmosferica.
* Indicare la pressione in millimetri di mercurio (mmHg).
* Stato della pressione barometrica.

# Versione 4.4.8 #

* Aggiunta la traduzione in polacco (grazie a Zvonimir Staneczyć).
* Compatibilità con wx python versione 4.

# Versione 4.4.1 #

* Aggiunto il supporto SSL.

# Versione 4.4 #

* Corretto bug nella lettura della nuova stringa di versione, durante un
  time-out della connessione.
* Migliorata la sezione aggiornamento; ora la finestra di dialogo non
  interferisce con il menu di nvda.
* Riveduta e corretta localizzazione Russa.
* Aggiunta la traduzione in ucraino (grazie ad Alex Yeshanu).

# Versione 4.3.4 #

* Riveduta e corretta la localizzazione Tedesca.

# Versione 4.3.3 #

* Aggiunta localizzazzione tedesca (grazie a Karl Eick).

# Versione 4.3.2 #

* Aggiunta localizzazione Rumena (grazie a Florian Ionașcu).

# Versione 4.3.1 #

* Corretto un bug minore nella funzione "dettagli"; le stringhe "latitudine"
  e "longitudine" erano invertite rispetto al valore.

# Versione 4.3 #

* Weather Plus è passato a "nvda.it" come provider di hosting predefinito.

# Versione 4.2.4 #

* Corretto un bug minore quando la connessione non era attiva.

# Versione 4.2.3 #

* Ora, Weather Plus esegue alcuni tentativi di connessione prima di
  notificare il malfunzionamento del WoeId in uso, con l'emissione di un
  beep ad ogni tentativo; questo segnale acustico, se si desidera, può
  essere disattivato tramite una casella di controllo dalle impostazioni di
  Weather Plus.

# Versione 4.2.2 #

* Corretto un bug nella traduzione della scala di misura; In alcune lingue,
  Kelvin, Celsius e Fahrenheit non sono stati tradotti.

# Versione 4.2.1 #

* Risolto avviso di aggiornamento di Weather Plus durante l'avvio di
  Windows; questo accade quando è stato premuto il pulsante "Utilizza le
  impostazioni di configurazione salvate nella finestra di logon (richiede
  privilegi di amministratore)" dalle impostazioni generali di nvda, che
  copia la configurazione e tutti gli add-on nella cartella systemConfig, ma
  questi non vengono sincronizzati con i successivi aggiornamenti dei
  componenti aggiuntivi. Se avete usato almeno una volta questa opzione,
  dovrete farlo di nuovo per l'ultima volta, solo dopo aver aggiornato
  Weather Plus.

# Versione 4.2 #

* Aggiunti 5 nuovi effetti sonori; sarà necessario aggiornarli dalle
  impostazioni del plugin.
* Corretto un bug nella funzione di importazione; l'elenco delle città non
  veniva ordinato alfabeticamente.
* Aggiunta modalità di importazione nella funzione di importazione; si può
  decidere se sostituire completamente la propria lista, o semplicemente
  aggiungere nuove città ad essa.
* Aggiornata la lettura del bollettino corrente; aggiunta la temperatura
  percepita (wind chill).
* Aggiunte nuove stringhe alla lista per i rapporti meteo.

# Versione 4.1 #

* Corretto bug nelle previsioni fino a 10 giorni; ora se le previsioni
  ricevute sono in numero inferiore alla richiesta dell'utente, i giorni
  mancanti vengono indicati come sconosciuto.
* Corretta stringa di aiuto immissione sul comando nvda+shift+w.
* Documentazione rivista e aggiornata.

# Versione 4.0 #

* Aggiornate alcune parti di codice e sostituito tutte le istruzioni eval().

# Versione 3.9.7 #

* Corretto bug durante la lettura nelle previsioni del tempo; ora le
  temperature vengono lette correttamente.

# Versione 3.9.6 #

* Cambiato l'arrotondamento nella conversione della pressione atmosferica da
  millibars in pollici di mercurio; ora il valore è calcolato in difetto,
  mentre prima era in eccesso.

# Versione 3.9.5 #

* Aggiunte 2 nuove stringhe alla lista rapporti meteo.
* Coorretti 2 bug.
* Aggiornata l'esecuzione suoni per l'effetto in condizioni di solo vento;
  ora il suono del vento può variare in modo casuale.

# Versione 3.9.4 #

* Documentazioni, localizzazioni per lingue Croata e Tedesca erano rimossi;
  perché non sono più supportate dai rispettivi traduttori.
* Corretto un bug nella localizzazione serba.
* Aggiornata la localizzazione ceca.
* Aggiornata la documentazione e localizzazione Gallega.

# Versione 3.9 #

* Cambiato nuovamente servizio API; Weather Plus ora usa le nuove Yahoo
  Weather API con linguaggio Yahoo!Query e JQuery:
* La chiave-API non è più richiesta.
* Ripristinata la ricerca delle città omonime; sarà possibile scegliere
  esattamente la città desiderata da un elenco.
* Ottimizzato l'output dei suoni generali; ora sono sincronizzati con la
  sintesi vocale e sono più veloci.
* Migliorata la cache per i dati off-line; viene azzerata ogni 10 minuti o
  solo cambiando la città.
* Pressione barometrica misurata in millibars, o in pollici di mercurio (se
  impostato su Fahrenheit).

# Versione 3.8 #

* Correzioni di accuratezza dei dati.
* Abilitata l'impostazione automatica della lingua; ora l'API invia i dati
  delle condizioni meteo nella lingua impostata da nvda.
* Aggiunta una cache per bollettino e previsioni del tempo; se non viene
  cambiata la città, la scala dei gradi o i giorni di previsione impostato,
  si sarà in grado di leggere i dati per 10 minuti anche quando la
  connessione off-line. La cache si reinizializza ad ogni cambiamento
  descritto sopra. Questo perché i bollettini non cambiano in questo lasso
  di tempo e per ridurre le frequenti chiamate all'API, magari giocando con
  gli effetti sonori.
* Migliorata la ricerca degli aggiornamenti; ora una volta scaricato, viene
  attivata la sua installazione, o nel caso di una versione portable di nvda
  viene aperta la cartella dove è stato salvato l'aggiornamento.
* Aggiornati tutti i suoni; ora i suoni sono in formato wav.

# Versione 3.7 #

* Aggiunta possibilità di disattivare la conversione in metri al secondo del
  vento.
* Aggiunta possibilità di utilizzare l'unità di misura in libbre per pollice
  quadrato.
* Coorretti 2 bug.

# Versione 3.6 #

* Cambiato servizio API (Application programming interface); ora WP usa il
  servizio offerto da OpenWeatherMap.org al posto di Yahoo Weather.com.
* Aggiunta classificazione vento nel bollettino corrente.
* Aggiunta percentuale di nuvolosità nelbollettino corrente.
* Adottata unità di misura unica della pressione in ettopascal nelbollettino
  corrente.

# Modifiche nella finestra Impostazioni Weather Plus #

* Cambiato inserimento/ricerca da yahoo zipcode/woeId in numero Id,
  identiificativo della città; i numeri di ID città sono simile al woeid, ma
  i woeId non funzioneranno più, neanche i vecchi zipcode. Si potrà
  ritrovare gran parte delle città digitandone il nome o parte di esso.
* Aggiunto inserimento/ricerca per coordinate geografiche.
* Aggiunto inserimento/ricerca per codice postale.
* Migliorata la funzione "dettagli".
* Assegnato al tasto F1 l'aiuto immissione/ricerca.
* Assegnato al tasto F4 i controlli per impostare le previsioni da 1 a 16
  giorni. Attenzione, un valore superiore a 10, se si sceglie di copiare
  negli appunti, questi non verranno letti!
* Assegnato il tasto F5 per i controlli audio.
* Aggiunta scala di misura in gradi Kelvin.
* Aggiunto controllo presenza aggiornamenti; si può settare dalle
  impostazioni o controllare manualmente da menu.
* Riassegnato il pulsante "trova la tua città" in "Gestione della tua chiave
  API..."; permette di inserire o modificare la chiave-API.

# Versione 3.5 #

* Aggiunta traduzione croata (grazie a Gordan Radić).
* Aggiunto controllo per WoeId e zip code non più validi trovati in rete; vi
  sono state segnalazioni di codici che da un giorno all'altro hanno smesso
  di funzionare, WP ora avvisa se uno di questi è stato inserito dalle
  finestre di ricerca sulla rete. Se questo si verifica utilizzando la
  funzione "Trova la tua città...", si prega di segnalarlo in modo che io
  possa aggiornare il Weather_buffer e rimuoverli dall'elenco.
* Corretto un bug di codifica nella funzione di ricerca.
* Aggiornata la finestra per impostare un zip code temporaneo; aggiunta
  funzione di ricerca come nelle altre fiinestre di Weather Plus: Control+F3
  = Trova..., F3 = Trova successivo, Shift+F3 = Trova precedente.

# Versione 3.4 #

* Aggiunta traduzione galiziana (grazie a Iván Novegil).
* Aggiunta traduzione portoghese (grazie a Ângelo Miguel Abrantes).
* Aggiunta traduzione tedesca (incompleta).

# Versione 3.3 #

* Aggiunta misura della velocità del vento in metri al secondo.
* Correzioni di codifica.

# Versione 3.2 #

* Aggiornata la lettura delle previsioni meteo, bollettino corrente e
  lettura data dell'attuale bollettino meteo; Yahoo weather forecast da un
  po' di tempo e in quantità casuale fa passare uno storico a -10 - -5
  giorni delle previsioni meteo che si vanno a inserire tra i dati
  aggiornati che vogliamo leggere; e' stato aggiunto un filtro che permette
  di leggere solo gli ultimi dati meteo aggiornati, e un discreto segnale
  acustico avvisa quando interviene; questo segnale acustico, volendo è
  possibile disattivarlo tramite una casella di controllo dalle impostazioni
  di Weather Plus. Ovviamente il filtraggio dei dati qualche volta comporta
  un breve ritardo nella risposta, comunque accettabile.
* Previsioni del tempo estese a 10 giorni.

# Versione 3.1 #

* Aggiunta traduzione in serbo (grazie alla gentile collaborazione di Dejan
  Gasic).
* Corretto il comando insert+alt+w; non verificava la validità del zipcode
  in uso, ne se la connessione era attiva come già fanno gli altri comandi.
* Aggiornata la funzione di riproduzione degli effetti sonori; il formato
  mp3 è ora utilizzato. Ora i file sono molto più piccoli.
* Aggiunti 55 nuovi effetti sonori; sarà necessario aggiornarli dalle
  impostazioni del plugin.

# Modifiche nella finestra Impostazioni Weather Plus #

* Corretta visualizzazione aiuto sui bottoni; ora si disabilita/abilita in
  tempo reale tramite l'apposita casella di controllo.
* Aggiunti 3 comandi di scelta rapida per navigare più velocemente nella
  finestra:
* F1 salta all'elenco e casella di modifica dei zip code.
* F2 ritorna all'ultima selezione raggiunta con TAB.
* F3 salta ai controlli del volume (se gli effetti sonori sono installati e
  attivati).
* Aggiunti comandi di scelta rapida per tutte le caselle di controllo e i
  bottoni; omessi i due pulsanti radio in quanto sono presenti in
  successione e il primo è raggiungibile con il comando control + shift + w.
* Modificato, il bottone "definisci" ora viene disabilitato se gli effetti
  sonori non sono installati e attivati.
* Aggiunto controlli del volume; si può regolare il volume generale e
  dell'ultimo effetto sonoro ascoltato; l'opzione è abilitata se gli effetti
  sonori sono installati e attivati.
* Aggiunta possibilità di impostare il sistema orario nel formato a 12 ore
  (12:30 AM - 12:30 PM) , o il sistema a 24 ore (12:30 - 00:30).

# Versione 3.0 #

* Aggiunta traduzione in Slovacco (grazie alla gentile collaborazione di
  Vitek Jirasek).
* Aggiunta traduzione in portoghese-brasiliano e portogallo (grazie alla
  gentile collaborazione di Adair Knaesel).
* Aggiunte nuove stringhe alla lista per i rapporti meteo.
* Aggiunti 171 nuovi effetti sonori, ora sono 213 in totale.
* Aggiunto il comando insert + alt + w in gesture, annuncia la data
  dell'ultimo aggiornamento del bollettino meteorologico.
* Aggiunto scriptCategory che sposta nella corretta posizione i tasti rapidi
  di Weather Plus in "gesti e tasti di immissione".

# Modifiche nella finestra Impostazioni Weather Plus #

* Aggiunto un pulsante radio per impostare come indicare la scala di
  temperatura;
* La scelta è tra:
* Centigradi `-` Fahrenheit
* C `-` F
* Nessuna indicazione
* Aggiunto pulsante "Define"; permette di definire la zona di una città tra:
* Entroterra
* Zona marittima
* Zona del deserto
* Zona artica
* Zona montana
* La scelta permetterà a Weather Plus di usare gli effetti sonori più
  appropriati per ogni singolacittà; ecco il motivo dell'incremento del
  numero di nuovi effetti sonori in questa versione dell'addon; molti dei
  nuovi effetti sonori me li ha forniti Tapin, che ringrazio sinceramente.

# Versione 2.9 #

* Aggiunta possibilità durante l'importazione di selezionare il contenuto
  del file importato.
* Aggiunti 4 nuovi effetti sonori.
* Aggiunta traduzione in Russo (grazie ad Alex Yeshanu).
* Aggiunta traduzione in ceco (grazie a Jirimu Holzingerovi).

# Versione 2.8 #

* Corretto bug in "dettagli", apriva finestra delle ricorrenze quando non
  trovava la località.
* Corretto regexp per ricerca altitudine; non accettava parametri a una sola
  cifra.
* Migliorato il parser della casella di editazione; dovrebbe trovare più
  facilmente le città.
* Connessioni ora gestite da urllib2, anziché urllib; questo dovrebbe
  permettere il funzionamento dell'addon anche su un computer collegato a
  rete aziendale protetta da proxy.
* Aggiunta funzione "Trova"; Control+F3 = Trova..., F3 = Trova successivo,
  Shift+F3 = Trova precedente.

# Versione 2.7 #

* Corretto nome errato di una stringa "Motorcycle" in "Motorcycle00";
  chiedeva aggiornamento degli effetti sonori perché non trovava il file.
* Aggiunta possibilità lettura informazioni vento; direzione, velocità e
  temperatura del vento.
* Aggiunta possibilità lettura informazioni atmosferiche; umidità,
  visibilità, pressione e stato della pressione barometrica.
* Aggiunta possibilità lettura dati astronomici; orario del sorgere e
  tramonto del sole.

# Modifiche nella finestra Impostazioni Weather Plus #

* Aggiunte 3 caselle di controllo per gestire le rispettive informazioni
  sopra elencate.
* Aggiunto pulsante "Dettagli"; fornisce alcune informazioni come il nome
  reale della città (assegnato da Yahoo Weather Forecast), lo stato/regione
  e la nazione di appartenenza; con coordinate geografiche, e altezza sul
  livello del mare.
* Aggiunto riconoscimento dei WoeID (codici di luogo, es. Bologna it
  corrisponde a 711080).
* Ora è possibile digitare il nome della città, in questo caso se presenti,
  saranno elencate le ricorrenze e si potrà scegliere.

# Versione 2.6 #

* Ottimizzate funzioni dei pulsanti "Aggiungi" e "Rimuovi" nella gestione
  lista dei zip code; ora le operazioni sono molto più veloci!
* Ottimizzata la funzione del pulsante "Test", ora sfrutta fino a 13 chiavi
  di ricerca; Ora se non trova il nome della città è una vera sfiga!
* La funzione del pulsante "Trova la tua città...", ora trova più paesi; è
  stato aggiunto un test automatico che raccoglie gli zip code al momento
  funzionanti, e consente la successiva rapida visualizzazione grazie alla
  creazione di un piccolo buffer corrispondente al nome del paese specifico.
* Sono stati aggiunti tre nuovi effetti sonori; sarà necessario aggiornarli
  dalle impostazioni del plugin.

# Versione 2.5 #

* Aggiunto comando nella gesture per alternare temporaneamente la scala
  della temperatura da Celsius a Fahrenheit, il comando ha effetto anche
  nella finestra delle impostazioni.
* Corretto bug, se l'utente non premeva "Aggiungi" o "Preimpostato" non
  permetteva di vocalizzare il nome della città perché non in lista.
* Aggiunte nuove stringhe alla lista per i rapporti meteo.

# Modifiche nella finestra Impostazioni Weather Plus #

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
* Corretto immissione al volo, non viene più salvata, è quindi temporanea;
  Per richiamare la città impostata nelle preferenze premere
  NVDA+control+f3.

# Versione 1.9 #

* Aggiunti aiuto immissione delle funzioni.
* Aggiunto una nuova funzione per inserimento rapido dello Zip Code.
* Aggiunto lettura/scrittura configurazione in weather.ini, ora non è più
  necessario editare il file sorgente.
* aggiunto Weather menu nel System Tray.
* Aggiunto sottomenu impostazione Zip Code...
* Aggiunto sottomenu impostazione scala di temperatura (Fahrenheit o
  Celsius).
* Aggiunto menu Documentazione.
* aggiunta localizzazione italiana.

# Versione iniziale 1.1 #

* Aggiornato il nvda-addon.
* Il supporto alla traduzione è stato aggiunto.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
