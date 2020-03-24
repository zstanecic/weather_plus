# Weather Plus #

* Autor: Adriano Barbieri
* Zgodność z wersjami NVDA: 2017.3 to 2019.3
* Pobierz: [Wersja stabilna][1]

# O Weather Plus: #

* Ten dodatek dodaje lokalną temperaturę i prognozę pogody do 24 godzin i do
  dodatkowych 9 dni dla NVDA
* prawa autorskie (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Wydano pod licencją GNU GPL (General Public License v2)

# Weather Plus działa przy użyciu i obecności następujących serwisów: #
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# Użycie: #
* naciśnij NVDA + w dla aktualnej temperatury i warunków pogodowych.
* Naciśnij NVDA + shift + W dla 24-godzinnej pogody i prognozy do 9 dni.
* naciśnij NVDA + shift + ctrl + w, aby ustawić tymczasowe miasto.
* naciśnij NVDA + shift + control + alt + w, aby otworzyć ustawienia Weather
  plus.
* naciśnij NVDA + alt + w, aby się dowiedzieć, kiedy ostatnio był
  zaktualizowany biuletyn pogodowy.
* Naciśnij control + shift + w aby przełączać się między skałami mierzenia
  temperatury.

# Aby ustawić weather plus: #
Proszę przeczytać rożdział: Weather Plus pierwsze ustawienia.

--------------------------------------------------------------------------------

# Weather plus pierwsze ustawienia #

Powinno się ustawić dodatek przed jego pierwszym użyciem!

idź do:

meni rozwijane ustawienia

Ustawienia weather plus rozwijane

Pokazuje elementy konfiguracji.

# Naciśnij element dla: #

* Ustaw i zarządzaj swoimi miastami...
	* Wyświetla i umożliwia ustawianie aktualnego miasta z listy.
* Dokumentacja
	* Otwiera meni pomocy dla aktualnego języka.
* sprawdź aktualizację...
	* Oznajmia o dostępności nowje wersji.

Naciśnij element:

# Ustaw i zarządzaj swoimi miastami... #

Wyświetla listę miasta, a także umożliwia ustawianie go z niej.

Następujący komunikat pokazywany jest tylko przy pierwszym uruchomieniu!

Predefiniowane ustawienia

Nic

F1: pomóż mi znaleźć miasto, F2: gdzie się znajduję, F3: lista i pole
edycji, F4: czas trwania pogody, F5: kontrola głośności.

Wpisz nazwę miasta, woeID lub wybierz jeden z listy, jeżeli jest dostępny.

Uwaga: kombinacja klawiszy f5 jest dostępna, gdy efekty dźwiękowe są
aktywne.

Po naciśnięciu przycisku ustaw i zarządzaj swoimi miastami następujące
przyciski są dostępne:

# Testuj #

Testuje nazwę miasta lub WoeID i na odwrót.

# Dodaj #

Dodaje aktualne miasto do listy.

Ten przycisk jest dostępny gdy miasto przeszedło test, lub jest ono
dostępne.

# Szczegółu #

Pokazuje informację o aktualnym mieście.

Ten przycisk jest dostępny gdy miasto przeszedło test, lub jest ono
dostępne.

# Zdefiniuj #

Umożliwia zdefiniowanie obszaru, aby dostosować dźwięki pogodowe do
rzeczywistości.

Ten przycisk jest dostępny, gdy dźwiękowe efekty są zainstalowane i
aktywowane, przy czym miasto musi być wybrane.

# Ustaw miasto jako domyślne #

Ustawia miasto jako domyślne, ędzie używane przy każdym ponownym
uruchomieniu.

Ten przycisk jest aktywny, gdy zaznaczone jest miasto i nie jest ono
domyślne, lub ono przeszło test.

# Usuń #

Usuwa aktualne miasto z listy.

Ten przycisk jest aktywowany jeśli jest zaznaczone miasto, które uprzednio
istniało na liście.

# Zmień nazwę #

Zmienia nazwę aktualnego miasta..

Ten przycisk jest aktywowany jeśli jest zaznaczone miasto, które uprzednio
istniało na liście.

# Zaimportuj nowe miasta... #

Pozwala dołączać do listy nowe miasta zaimportowane z innej listy o
rozszerzeniu *.zipcodes; Miasto do zaimportowania można wybrać zaznaczając
odpowiadające mu pole wyboru.

# Eksportuj miasta #

Zapisuje listę miast w określonej lokalizacji.

Przycisk ten jest aktywny, jeśli na liście znajduje się przynajmniej jedno
miasto.

# Skala pomiaru temperatury: #

Użyj przycisku opcji aby wybrać:

* Celsjusz (domyślnie)
* Farenhajt
* Kelwin

# Pokazuj stopnie jako: #

Użyj przycisku opcji aby wybrać:

* Celsjusz `-` Farenhajt `-` Kelwin (domyślnie)
* C `-` F `-` K
* Nieokreślone

Lista rozwijana:

# Prognoza pogody do 3 dni #

Wybierz od 1 do 10 (domyślnie na 3 dni)

Przełącz pole wyboru aby:

# Skopiuj prognozę i biuletyn pogodowy do schowka wraz ze szczegółami miasta. #

Domyślnie odznaczone.

# Włącz efekty dźwiękowe (tylko dla aktualnych warunków pogodowych) #

To pole wyboru pozwala też zarządzać instalowaniem efektów dźwiękowych;

Gdy efekty dźwiękowe są zainstalowane a pole wyboru zaznaczone, uaktywniają
się ustawienia głośności i klawisz F5.

Pojawia się także dodatkowe pole wyboru:

* Używaj tylko efektów pogodowych.

Można zmienić głośność ogólną, lub głośność ostatnio usłyszanego dźwięku, a
także odfiltrować inne dźwięki z otoczenia.

Domyślnie odznaczone.

# Używaj tylko efektów pogodowych. #

Dostępne gdy efekty dźwiękowe są włączone;

Po zaznaczeniu umożliwia słuchanie wyłącznie efektów pogodowych, takich jak
deszcz, wiatr, grzmoty itd. Inne dźwięki otoczenia zostają odfiltrowane.

Domyślnie odznaczone.

# Włącz odczytywanie godzin w formacie 24-godzinnym. #

Gdy odznaczone, czas odczytywany jest w formacie 12-godzinnym, np. 12 AM `-`
12 PM.

Domyślnie zaznaczone.

# Włącz przyciski pomocy w oknie ustawień. #

Domyślnie zaznaczone.

# Odczytuj informacje o wietrze. #

Domyślnie odznaczone.

Gdy włączone, można uaktywnić również:

* Dodaj kierunek wiatru;

Określa skąd wieje wiatr.

Domyślnie zaznaczone.

* Dodaj prędkość wiatru;

Podaje prędkość wiatru w kilometrach, lub milach na godzinę.

Domyślnie zaznaczone.

* Dodaj prędkość wiatru w metrach na sekundę;

Domyślnie zaznaczone.

* Dodaj temperaturę odczuwalną;

Domyślnie zaznaczone.

# Odczytuj informacje atmosferyczne. #

Domyślnie odznaczone.

Gdy włączone, można uaktywnić również:

* Dodaj wskaźnik wilgotności powietrza;

Podaje wilgotność powietrza w procentach.

Domyślnie zaznaczone.

* Dodaj stopień widzialności;

Podaje widoczną odległość w kilometrach, lub milach.

Domyślnie zaznaczone.

* Dodaj wartość ciśnienia atmosferycznego;

Podaje ciśnienie atmosferyczne w milibarach, lub calach słupa rtęci.

Gdy jest włączone, można zaznaczyć dodatkowe pole wyboru, które umożliwia
podawanie ciśnienia w milimetrach słupa rtęci.

Domyślnie zaznaczone.

* Dodaj wartość ciśnienia barometrycznego;

Domyślnie zaznaczone.

# Odczytuj informacje astronomiczne. #

Podaje czas wschodu i zachodu słońca.

Domyślnie odznaczone.

# Użyj przecinka do oddzielania wartości dziesiętnych. #

Gdy jest zaznaczone, wartości dziesiętne oddzielane są przecinkiem, w
przeciwnym razie kropką.

Domyślnie odznaczone

# Sprawdź aktualizacje #

Po uaktywnieniu tej opcji dodatek powiadamia o dostępnych aktualizacjach

Domyślnie zaznaczone.

# Naciśnij przycisk OK aby potwierdzić akcję, lub przycisk Anuluj aby ją anulować. #

Jeśli po zmodyfikowaniu listy miast naciśniesz "Anuluj", dodatek przypomni
Ci o zmianach na liście i umożliwi jej zapisanie.

# Uwaga: Twoje ustawienia zostaną zapisane w pliku o nazwie: #

* "Weather.ini": ustawienia uruchamiania Weather Plus.
* "Weather.volumes": Dostosuj poziom głośności dźwięku niezależnie od
  głośności ogólnej.
* "Weather.zipcodes": Lista miast wraz z kodami pocztowymi i definicjami.
* "Weather_searchkey": Słowo kluczowe zapisane.

--------------------------------------------------------------------------------

# Co nowego: #

# Wersja 7.3 #
* Naprawiono niespodziewany błąd podczas wyszukiwania aktualizacji.

# Wersja 7.2 #
* Naprawiony błąd, który pojawiał się po dodaniu pierwszego miasta,
  wciśnięciu przycisku Ok i restarcie dodatku.
* Na pasku postępu znowu wyświetlany jest czas który upłynął i który
  pozostał.
* Poprawione włoskie tłumaczenie przycisku Zmień Nazwę w pomocy

# Wersja 7.1 #
* Naprawiony błąd w Removeupdate() gdy podczas restartu dodatku plik ma
  atrybut tylko do odczytu.

# Wersja 7.0 #
* Ulepszone okienko wyszukiwania pozwala zarządzać wszystkimi wprowadzonymi
  słowami kluczamu. Z poziomu meni kontekstowego można dodać, usunąć i
  zapisać słowo klucz.
* Ulepszona kontrola otwierania okna
* Kilka drobnych poprawek

# Wersja 6.9 #

* Wprowadzono rekurencyjne wyszukiwanie miast z systemem weryfikacji
  używanym w wersji Weather_Plus Apixu.

	* Naciśnij f1 w oknie ustawień, aby uzyskać pomoc.

* Naprawiony problem z usuwaniem niektórych modułów * .pyc, * .pyo przy
  aktualizacji NVDA.

# Wersja 6.8 #

* Zaktualizowane flagi dla poniższych gałęzi;

	* nvda_snapshot_threshold i nvda_snapshot_threshold_py3_staging.

# Wersja 6.7 #
* Naprawiono błąd, który pojawiał się podczas sprawdzania nowego miasta w
  trybie tymczasowym po naciśnięciu klawisza "enter" i przy próbie dodania
  tego miasta przyciskiem "Dodaj"
* Dodano skrót dla Georgii Południowej i Sandwichu Południowego do bazy
  danych. Niestety na chwilę obecną miasta tego obszaru nie działają, lub
  mają niekompletne dane. Zostanie to wkrótce naprawione.

# Wersja 6.5 #
* Naprawiono kilka błędów w odtwarzaniu dźwięków;
	* kilka "for" cykli o niewłaściwych wartościafh spowodowało próbę odtworzenia nieistniejącego efektu dźwiękowego.
* Naprawiono błąd związany z czasem lokalnym w "szczegółach";
	* czas 12-godzinny spowodował błąd.
* Naprawiono błąd w prognozie Yahoo Weather Forecast;
	* Prognozy dla niektórych miast zaczynają się od poprzedniego, a nie od aktualnego dnia.
	* Naprawienie tych miast wiąże się z utratą ostatnich dni prognozy proporcjonalnie do niezgodności w datach (jeśli prognoza ustawiona jest na 10 dni).

# Wersja 6.4 #
* Czas letni został usunięty z "funkcji" Szczegóły;
	* Usługa używana przez czas letni uległa zmianie. Dlatego został on usunięty.
* Ulepszono odtwarzanie efektów dźwiękowych;
	* Od teraz uaktualniają się one regularnie, wraz ze zmianami warunków pogodowych.

# Wersja 6.3 #
* Poprawiono kodowanie znaków w wynikach wyszukiwania.
* Poprawiono kodowanie także w szczegółowej prognozie.

# Wersja 6.2 #
* Naprawiono błąd w funkcji "Dodaj"
* Naprawiono błąd, który nie przypisywał zmiennej "_volume" podczas
  uruchamiania dodatku.
* Dodano brakujący kod z wersji 6.0;
	* Od teraz można przywrócić zapisane miasta z wersji, która używa Apixu API;
	* Przyciski "Testuj" i "Usuń" a także miasta niezgodne z nową wersją dodatku można znaleźć w format: "Ferrara, iter 44.83,11.58 0" (miasto, współrzędne geograficzne, charakterystyka obszaru).

# Wersja 6.1 #
* Naprawiono 2 błędy.

# Wersja 6.0 #
* Weather Plus znów będzie używać Yahoo Weather API.
* Praktycznie wszystkie funkcje z wersji 4.8 znów są dostępne. Przycisk
  "Zmień nazwę" też został zachowany.
* Teraz także zgodne z Pythonem 3.

# Wersja 5.0.1 #
* Naprawiono błąd, który zwracał pusty ciąg znaków, gdy prędkość wiatru w
  milach na godzinę wynosiła 0.
* Naprawiono błąd, który powodował odtwarzanie efektów dźwiękowych
  niezgodnych ze strefą czasową.
* Poprawiono ilość prognozowanych dni w pliku czytaj to z 9 na 6.

# Wersja 5.0 #
* Od teraz Weather Plus używa APIXU API, które, moim zdaniem, działa lepiej
  niż poprzednie.

`#`Zmiany w oknie ustawień Weather Plus:

* Usunięto stare pole wyboru "Stan ciśnienia barometrycznego".
* Replaced with new checkbox "Add cloudiness value";
	* It gives you the percentage of cloudiness.
* Added new checkbox "Add precipitation value";
	* It gives you the amount in millimeters of precipitation.
* Removed old checkbox "Indicates the wait with a beep while you search for the latest bulletin";
	* Left active by default.
* Added to the Astronomic information;
	* Time of moonrise and moonset.
* Added new button "Rename";
	* To rename cities more conveniently.
* Improved function of the "Test" button;
	* Now accept some commands to facilitate the search for cities;
	* These new commands are described in the help function that can be called up with F1.

# Wersja 4.8 #
`#`Zmiany w oknie ustawień Weather Plus:

* Dodano nowe pole wyboru;
	* "Używaj tylko efektów dźwiękowych dla pogody";
	* Pozwala to odfiltrować pozostałe efekty dźwiękowe związane z danym obszarem.
* Ulepszono odtwarzanie losowe i dodano 71 nowych efektów dźwiękowych;
  	* Należy je zaktualizować zaznaczając pole wyboru "włącz efekty dźwiękowe".
* Rodzaj głośności przypisany przez użytkownika, znajdujący się pomiędzy głośnością główną a aktualną głośnością audio, zostaje zachowany po zapisaniu ustawień.
* Usunięto niepotrzebny dźwięk odtwarzany przy zaznaczaniu tekstu w polu edycyjnym skrótem control+a.
* Ulepszono czytelność okna pomocy wywoływanego klawiszem funkcyjnym F1.
* Dodano nową flagę zgodności dla NVDA 2019.1, oraz dla aktualnych wersji alfa.

# Wersja 4.7.7 #
* Usunięto niepotrzebne powiadomienie o ukończeniu pobierania podczas
  aktualizacji Weather Plus.
* Dodano 6 nowych efektów dźwiękowych;
	* Należy je zaktualizować w ustawieniach dodatku.

# Wersja 4.7.6 #
* Naprawiono niewielki błąd w funkcji GetCoords();
	* Dodatek nie zwracał dwóch wartości przy braku połączenia.

# Wersja 4.7.5 #
* MenuItem.GetLabel() jest przestarzałe i zostało zastąpione przez
  MenuItem.GetItemLabelText().
* Poprawiono niektóre deklaracje zmiennych globalnych.

# Wersja 4.7.3 #
* Dla wygody zaktualizowano funkcję w oknie dialogowym "szczegóły";
	* Informacje o wysokości nad poziomem morza są od tej pory dostarczane przez veloroutes.org.
	* Nieznacznie zmieni to działanie dodatku.

# Wersja 4.7.2 #
* Naprawiono błąd kodowania w funkcji Removeupdate function.

# Wersja 4.7.1 #
* Naprawiono błąd w funkcji GetTimezone;
	* W przypadku pustych danych zwracana była tylko jedna wartość zamiast trzech wymaganych.

# Wersja 4.7 #
* Uproszczono aktualizator;
	* Jeżeli podczas uruchamiania dodatku dostępna jest nowa aktualizacja, wystarczy przejść przez jedno okno dialogowe, aby ją zainstalować.
* Usunięto listę plików w aktualizatorze;
	* Plik aktualizacji jest pobierany do folderu tymczasowego, co ułatwia początkującym użytkownikom korzystanie z dodatku.

# Wersja 4.6.9 #
* Dodano arabskie tłumaczenie (Wafik Immaculate).

# Wersja 4.6.8 #
* Uaktualniono portugalskie i brazylijskie tłumaczenia (Alberto Mendonça).

# Wersja 4.6.7 #
* Ulepszono odczytywanie aktualnego czasu;
	* Dla niektórych miast było ono niepoprawne.
* Dodano czas letni do funkcji szczegóły;
	* Jest to dostępne tylko dla krajów, w których on obowiązuje.

# Wersja 4.6.5 #
* Naprawiono niewielki błąd podczas odczytywania aktualnego czasu;
	* Separator ":" nie był usuwany w trakcie zamiany na liczbę całkowitą.

# Wersja 4.6.4 #
* Ulepszono odczytywanie aktualnego czasu lokalnego; Słowa kluczowe są
  lepiej dopasowane.

# Wersja4.6.2 #
* Naprawiono błąd, który pojawiał się po sprawdzeniu aktualizacji. Meni
  "ustaw miasto tymczasowe..." było włączone, nawet gdy żadna lista miast
  nie była dostępna.
* Naprawiono błąd; nie można skonfigurować WP, jeśli nie ma jeszcze pliku
  weather.ini.

# Wersja 4.6 #
* Dodano element meni "Dodaj miasto tymczasowe...";
	* Dla przejrzystości, listę miast tymczasowych można otwierać również z meni.
* Ulepszono zarządzanie skalą temperatury;
	* Okno ustawień będzie zawsze zwracać wartość domyślną.
* Ulepszono zapobieganie wielokrotnemu otwieraniu okna głównego;
	* Gdy okno główne dodatku jest już otwarte, przy próbie kolejnego otwarcia pojawia się sygnał dźwiękowy, a kursor zostaje przeniesiony do Wcześniej otwartego okna.
* Ulepszono efekty dźwiękowe;
	* Są one oparte na aktualnym czasie lokalnym.

`#`Zmiany w funkcji szczegóły w oknie ustawień:

* Dodano aktualny czas lokalny.
* Naprawiono wartość wysokości nad poziomem morza;
	* Dodatek zwraca wartość wysokości nad poziomem morza, gdy ta wartość jest równa lub mniejsza niż zero.
* Naprawiono funkcję import;
	* Jeśli miasto domyślne zostało usunięte, nie będzie się już pojawiało na pasku tytułu.

# Wersja 4.5.5 #
* Poprawiono serbskie tłumaczenie i dokumentację.
* Poprawiono niemieckie tłumaczenie.

`#`Zmiany w oknie ustawień Weather Plus:

* Dodano pole wyboru;
	* Można włączyć przecinek jako separator dziesiętny. W przeciwnym razie separatorem będzie kropka.

# Wersja 4.5.3 #
* Poprawiono 2 ciągi znaków w rosyjskim i ukraińskim tłumaczeniu.
* Poprawiono nazwę okna Sprawdź aktualizacje.
* Poprawiono algorytm aktualizacji;
	* Link do aktualizacji jest odczytywany bezpośrednio z manifest url.

# Wersja 4.5 #
naciśnij NVDA + shift + control + alt + w, aby otworzyć ustawienia Weather plus.

`#`Zmiany w oknie ustawień Weather Plus:

* Dodano 8 pól wyboru;
	* Można bardziej dostosować wyjście:
* kierunek wiatru.
* prędkość wiatru.
* temperaturę odczuwalną.
* wartość wilgotności.
* wartość widoczności.
* wartość ciśnienia atmosferycznego.
* Pokazuje ciśnienie atmosferyczne w milimetrach słupa rtęci (mmHg).
* stan ciśnienia barometrycznego.

# Wersja4.4.8 #
* Dodano polskie tłumaczenie (Zvonimir Staneczyć).
* Weather Plus będzie zgodny także z przyszłą wersją wx 4;
	* Uwaga: obecnie z wersją wx 4.0.0b1 msw (phoenix) dodatek generuje denerwujący błąd podczas używania strzałek góra dół w wielu polach edycyjnych:

wxAssertionError: C++ assertion "Assert failure" failed at
..\..\src\common\evtloopcmn.cpp(110) in wxEventLoopBase::Yield(): wxYield
called recursively.

# Wersja 4.4.1 #
* Dodano wsparcie SSL;
	* Jest to używane tylko wtedy, gdy pojawia się błąd SSL error certificate verify failed.

# Wersja 4.4 #
* Naprawiono błąd odczytu informacji o nowej wersji, który pojawiał się po
  przekroczeniu czasu połączenia.
* Ulepszono aktualizator;
	* Okno dialogowe aktualizatora nie nakłada się już na meni nvda.
* Sprawdzono i poprawiono rosyjskie tłumaczenie.
* Dodano ukraińskie tłumaczenie (Alex Yeshanu).

# Wersja 4.3.4 #
* Sprawdzono i poprawiono niemieckie tłumaczenie.

# Wersja 4.3.3 #
* Dodano niemieckie tłumaczenie (Karl Eick).

# Wersja 4.3.2 #
* Dodano rumuńskie tłumaczenie (Florian Ionașcu).

# Wersja 4.3.1 #
* Naprawiono niewielki błąd w funkcji "details";
	* Określenia "szerokość geograficzna" i "długość geograficzna" były odwrotnie użyte, skutkiem czego opisywały nieswoje wartości.

# Wersja 4.3 #
* Linki publiczne zostaną zdezaktywowane 15 marca.
	* Z tą datą Folder publiczny stanie się typowym folderem Dropbox, a dodatek nie będzie go już używał.
	* Linki publiczne dodatku i efektów dźwiękowych zostały zaktualizowane. Dlatego WP będzie hostowane wyłącznie przez włoską społeczność NVDA.

# Wersja 4.2.4 #
* Naprawiono niewielki błąd pojawiający się gdy połączenie jest nieaktywne.

# Wersja 4.2.3 #
* Weather Plus spróbuje połączyć się ponownie zanim ogłosi, że WoeId nie działa poprawnie. Każda próba połączenia będzie oznajmiana sygnałem dźwiękowym;
	* Można wyłączyć ten sygnał przełączając pole wyboru w ustawieniach Weather Plus.

# Wersja 4.2.2 #
* Naprawiono błąd w tłumaczeniu skali pomiaru temperatury.
	* Skale Kelwina, Celsjusza i Farenhajta nie były przetłumaczone na niektóre języki.

# Wersja4.2.1 #
* Naprawiono powiadomienie o aktualizacji Weather Plus podczas uruchamiania systemu Windows;
	* Ten problem pojawiał się po naciśnięciu przycisku "Używaj zapisanych ustawień NVDA na ekranie logowania i innych zabezpieczonych ekranach (wymaga uprawnień administratora)" znajdującego się w ustawieniach ogólnych NVDA. Wszystkie ustawienia dodatku zostają skopiowane do konfiguracji systemowej, ale nie są synchronizowane z kolejnymi aktualizacjami dodatków.
	* Jeśli ten przycisk był kiedykolwiek aktywny, należy wcisnąć go jeszcze raz, żeby dodatek Weather Plus był zawsze aktualny.

# Wersja 4.2 #
* Dodano 5 efektów dźwiękowych;
	* Trzeba uaktualnić je w ustawieniach dodatku.
* Naprawiono błąd w funkcji import;
	* Miasta na liście nie były sortowane alfabetycznie.
* Do funkcji import dodano tryb importu;
	* Można zastąpić własną listę inną listą miast, lub dodać nowe miasta do już istniejącej.
* Zaktualizowano odczytywanie prognozy pogody;
	* Dodano temperaturę odczuwalną (efekt chłodzący wiatru).
* Dodano nowe ciągi znaków do listy prognoz.

# Wersja 4.1 #
* Naprawiono błąd w prognozie do 10 dni;
	* Gdy otrzymana liczba szacunkowa jest mniejsza niż żądana przez użytkownika, brakujące dni są wyświetlane jako stan nieznany.
* Poprawiono pomoc dla polecenia nvda+shift+w.
* Dokumentacja dodatku została sprawdzona i uaktualniona.

# wersja 4.0 #
* Uaktualniono część kodu i wymieniono wszystkie instrukcje eval().

# Wersja 3.9.7 #
* Naprawiono błąd w proporcji prognoz;
	* Temperatura jest już odczytywana poprawnie.

# Wersja 3.9.6 #
* Zmieniono zaokrąglanie podczas zamiany ciśnienia atmosferycznego z milibarów na cale słupa rtęci;
	* Wartość jest teraz zaokrąglana w dół, chociaż wcześniej była zaokrąglana w górę.

# Wersja 3.9.5 #
* Dodano 2 nowe ciągi znaków do listy prognoz.
* Naprawiono 2 błędy.
* Zaktualizowano zmienny dźwięk stosowany tylko dla wiatru;
	* Dźwięk wiatru może się teraz zmieniać losowo.

# Wersja 3.9.4 #
* Chorwackie oraz niemieckie tłumaczenia i dokumentacje zostały usunięte;
	* ponieważ nie są już wspierane przez poszczególnych tłumaczy.
* Naprawiono błąd w serbskim tłumaczeniu.
* Uaktualniono czeskie tłumaczenie.
* Naprawiono galicyjską dokumentację i tłumaczenie.

# Wersja 3.9 #
* Ponownie zmieniono serwis API;
	* Weather Plus używa teraz nowego API pogodowego Yahoo z Yahoo!Query i JQuery:
	* [yahoo-weather-api-with-yahooquery](http://codesimplified.blogspot.it/2013/10/yahoo-weather-api-with-yahooquery.html)
* Klucz API nie jest już wymagany.
* Przywrócono wyszukiwanie homonimicznych miast;
	* Będzie można dokładnie wybrać żądane miasto z listy.
* Zoptymalizowano wyjście dla głównych dźwięków;
	* Są one teraz synchronizowane z dźwiękiem syntezatora mowy i działają szybciej.
* Ulepszono haszowanie danych off-line;
	* Haszowanie ulega wyzerowaniu co 10 minut lub tylko przy zmianie miasta.
* Ciśnienie barometryczne mierzone w milibarach, lub w calach słupa rtęci gdy temperatura jest podawana w stopniach Farenhajta.

# Wersja 3.8 #
* Zmieniono pakiet danych API;
	* Po zmianie formatu z xml na JSON dane są bardziej precyzyjne, zwłaszcza strefa czasowa.
* Włączone zostało automatyczne ustawianie języka;
	* API przesyła teraz dane warunków pogodowych w języku aktualnie ustawionym w nvda.
* Dodano pamięć podręczną dla prognoz pogody;
	* Jeśli miasto, skala temperatury, lub ustawione dni prognozy nie zostały zmienione, Można będzie odczytać dane do 10 minut, nawet gdy nie ma połączenia z internetem.
	* Pamięć podręczna jest resetowana po każdej zmianie opisanej powyżej.
	* Wszystkie te zmiany wprowadzono, aby zapewnić dostęp do starszych prognoz pogody, jeśli nie zmieniają się one z upływem czasu. Zmniejszy to także liczbę wywołań API, co powstrzyma bawienie się efektami dźwiękowymi.
* Ulepszono wyszukiwanie aktualizacji;
	* Po pobraniu aktualizacji, zostanie ona zainstalowana. W wersji przenośnej nvda otworzy się folder, w którym aktualizacja została zapisana przez użytkownika.
* Zaktualizowano wszystkie dźwięki;
	* Moduł "tones" nie jest już używany i został zastąpiony małymi plikami w formacie WAV.

# Wersja 3.7 #
* Dodano możliwość wyłączenia zamiany prędkości wiatru na metry na sekundę.
* Dodano możliwość używania jednostek pomiaru takich jak funty na cal
  kwadratowy.
* Naprawiono 2 błędy.

# Wersja 3.6 #
* Zmieniono serwis API (application programming interface);
	* WP korzysta teraz z usług dostarczanych przez OpenWeatherMap.org a nie Yahoo Weather.com.
* Dodano klasyfikację wiatru w aktualnej prognozie.
* Dodano procent zachmurzenia w aktualnej prognozie.
* Przyjęto jednostkę pomiaru ciśnienia w hektopaskalach w aktualnej prognozie.

`#`zmiany dla okna ustawie Wather plus:

* Zmieniono dodawanie/wyszukiwanie z yahoo zipcode/woeId za pomocą identyfikatora miasta;
	* Identyfikatory miasta są podobne do woeid, ale woeId przestaje już działać nawet ze starymi kodami pocztowymi.
	* Można będzie odzyskać większość miast wpisując nazwę danego miasta, lub jej część.
* Dodane zostało dodawanie/wyszukiwanie współrzędnych geograficznych.
* Dodane zostało dodawanie/wyszukiwanie po kodzie pocztowym.
* Ulepszono funkcję "details".
* Klawisz F1 został przypisany do wpisywania pomocy dotyczącej miast.
* Klawisz F4 został przypisany do ustawiania terminu prognoz od 1 do 16 dni;
	* Uwaga! Jeśli skopiujesz do schowka wartość większą niż 10, nie zostanie ona odczytana!
* Klawisz F5 został przypisany do regulowania głośności.
* Dodano skalę pomiaru temperatury w stopniach Kelwina.
* Dodano sprawdzanie aktualizacji;
	* Można zaznaczyć pole wyboru do automatycznego sprawdzania aktualizacji, lub sprawdzić ręcznie w menu.
* Przycisk "Znajdź miasto" w grupie "Zarządzanie kluczem API...";
	* Umożliwia wprowadzenie lub zmianę klucza API.

# Wersja 3.5 #
* Dodano tłumaczenie chorwackie (dziękuję Gordan Radić).
* Added control for no longer valid WoeId and Zip Code found in the network;
	* There have been reports of codes that have stopped working from one day to another, WP now warns if one of these has been inserted from the windows of search on the net.
	* If this occurs using the function "Find your city...", please report it to me so that I can update the Weather_buffer and remove them from the list.
* Fixed a bug in the search function the next and previous; lacked the mbcs encoding and could not recognize accented characters.
* Updated the window to set one temporary zip code;
	* Added feature "Find" As in the other windows of Weather Plus:
	* Control+F3 = Find..., F3 = Find next, Shift+F3 = Find previous.

# Wersja 3.4 #
* Dodano tłumaczenie galicyjskie (dziękuję Iván Novegil).
* Dodano portugalskie tłumaczenie (dziękuję Ângelo Miguel Abrantes).
* Dodano tłumaczenie niemieckie (niekompletne).

# Wersja 3.3 #
* Added the measure of the speed of wind in meters per second.
* Modified the encode in "mbcs";
	* This permits to use also the diacritical marks in the city names.

# Wersja 3.2 #
* Updated the reading of the weather forecast, current weather report and reading of the date of the current weather report;
	* Yahoo weather forecast, from a bit of time and in random amounts, allows it to pass a historic from -10 to -5 days of weather forecast to be inserted between the updated data that we want to read;
	* It was added a filter that allows you to read only the last weather data updated, and a discreet beep alerts when it intervenes;
	* This beep, if you want, can be disabled by using a check box by Weather Plus settings.
	* Obviously, the filtering of data sometimes involves a short delay in reply, but is still acceptable.
* Forecasts of the time extended to 10 days.

# Wersja 3.1 #
* Dodano serbskie tłumaczenie (doceniając współpracę Gašić Dejan `-` Gashich
  Deyan).
* Fixed command insert+alt+w;
	* It did not check the validity of the zipcode in use and did not check if the connection was active as the other commands do.
* Updated the playback function of sound effects;
	* Mp3 are now used, with a considerable saving on the download time and disk space, thanks to the reduced size of compressed files.
* Added 55 new sound effects;
	* It will be necessary to update them from the settings of the plugin.

`#`zmiany dla okna ustawie Wather plus:

* Fixed display help on the buttons;
	* Now disables / enables real-time through the appropriate check box.
* Added 3 shortcut commands to navigate more quickly in the window:
* F1 jumps into list and edit box of zip code.
* F2 returns to the last selection reached with TAB.
* F3 jumps into volume controls (if the sound effects are installed and activated).
* Added shortcut commands for all check boxes and buttons;
	* Omitted the two radio buttons as they are present in succession and the first is reachable with the command control+shift+w.
* Changed, the button "define" is now disabled if the sound effects are not installed and activated.
* Added volume controls;
	* You can adjust the overall volume and the last heard sound effect;
	* This option is enabled if the sound effects are installed and activated.
* Added ability to set the system time in 12-hour format (12:30 AM `-` 12:30 PM) , or the 24-hour system (12:30 `-` 00:30).

# Wersja 3.0 #
* Added translation in Slovak (thanks to the kind cooperation of Vitek
  Jirasek).
* Added translation in Portuguese-Brazilian and Portuguese-Portugal (thanks
  to the kind cooperation of Adair Knaesel).
* Added new strings to the list weather reports.
* Added 171 new sound effects, now the total amount is 213.
* Added command insert+alt+w in the gesture to announce last update of
  current bulletin.
* Added scriptCategory which shifts in the correct position the rapid keys
  of Weather Plus in "Input gestures..."

`#`zmiany dla okna ustawie Wather plus:

* Added radio button to set how to indicate the temperature scale;
	* The choice is between:
* Celsius `-` Fahrenheit
* C `-` F
* No indication
* Added button " Define";
	* It permits to define the zone of one city between:
* Hinterland
* Maritime area
* Desert zone
* Arctic zone
* Mountain zone
	* The choice will consent to Weather Plus to use more appropriate sound effects for every single city;
	* This is the reason for the boost of the number of new sound effects in this versione of the addon;
	* Many of the new sound effects I got them from Tapin, whom I thank sincerely.

# Wersja 2.9 #
* Added option when importing to select the contents of the imported file.
* Four new sounds effects were added.
* Dodano tłumaczenie rosyjskie i ukraińskie (dziękuję Alex Yeshanu).
* Dodano czeskie tłumaczenie (dziękuję Jiri Holzinger).

# Wersja 2.8 #
* Fixed bug in "details", it used to open the window of the occurrences when
  he could not find the city.
* Fixed regexp to search for the altitude;
	* It did not accept parameters of single digits.
* Improved parser of the edit box;
	* It should find more easily the city.
* Connections now handled by urllib2, instead of urllib;
	* This should allow the functioning of the addon even on a computer connected to the corporate network protected by proxy.
* Added feature "Find";
	* Control+F3 = Find..., F3 = Find next, Shift+F3 = Find previous.

# Wersja 2.7 #
* Fixed wrong name of a string "Motorcycle" in "Motorcycle00";
	* He asked updated sound effects because they could not find the file.
* Added ability to read about wind ;
	* Direction, speed and temperature of the wind.
* Added ability to read atmospherical information;
	* Humidity, visibility, pressure and state of the barometric pressure.
* Added ability to read the Astronomic information;
	* Time of sunrise and sunset.

`#`zmiany dla okna ustawie Wather plus:

* Added 3 check boxes to manage their information listed above.
* Added button " Details ";
	* Provides some information such as the real name of the city ( assigned by Yahoo Weather Forecast), the state / region and the nation to which it belongs;
	* With geographic coordinates, and height above sea level.
* Added recognition of WoeID (location codes, eg. Bologna it corresponds to 711080).
* Now you can type the name of the city, in this case, if any, the occurrences will be listed and you will be able to choose.

# Wersja 2.6 #
* The functions of the buttons "Add" and "Remove" were optimized in the zip code's list management;
	* Now the operation are a lot more fast!
* The function of the button "Test" was optimized, now it exploits until 13 research keys;
	* Now if it doesn't find the name of the city it is a real bad luck!
* The function of the button "Find your city...", now finds more countries;
	* It was added an automatic test that collects the functioning zip codes, and it further consents a rapid visualization thanks to the creation of a little buffer corresponding to the name of the specific country.
* Three new sounds effects were added;
	* It will be necessary to update them from the settings of the plugin.

# Wersja 2.5 #
* Added command in the gesture to switch temporarily the temperature scale
  from Celsius to Fahrenheit, the command is also effective in the settings
  window.
* Fixed bug, if the user did not press the "Add" or "Preset" buttons, it did
  not allow to vocalize the name of the city since it was not included in
  the list.
* Added new strings to the list weather reports.

`#`zmiany dla okna ustawie Wather plus:

* Added button to open a research web page in order to check for the
  world-wide Zip Codes.
* Added the possibility to import / export the Zip Codes from friends.
* Added possibility to copy the weather report or the weather forecast to
  the clipboard.
* Added possibility to listen to the meteorological audio effects, the
  option also allows the installation / upgrade of the audio effects.
* Added ability help buttons on the management of Zip Code.
* Change to the display mode of the window, the menus of nvda are
  unrestrained when it is open.

# Wersja 2.4.4 #
* Dodano 2 nowe ciągi znaków do listy prognoz.
* Dodano hiszpańskie i włoskie tłumaczenie (dziękuję Pablo Vargas i Rémy
  Ruiz).

# Wersja 2.4.3 #
* Adding up the weather forecast for the next 4 days.
* Adding a string to the list weather report.
* The list of temporary zipcode is now ordered to each new insertion.

# Wersja 2.4 #
* Fixed a bug that prevented to save and manage properly the city names
  containing accented vowels.

# wersja 2.3 #
* Eliminated dialog box to set the scale of temperature measurement, has now
  been added a new gui that allows you to set all in one window.
* You will then also possible to test / add / delete / preset as the default
  Zip Code collected as a list.
* Modified the dialog box for entering typed a Zip Code, now in temporary
  mode allows you to set a Zip Code previously added to the list in
  Preferences from the menu.
* Now the documentation can be read in English if the language setting is
  not included in the documents.

# Wersja 2.2 #
* Fixed bug that did not allow you to open the documentation for the
  definitive versions of NVDA.

# Wersja 2.1 #
* Fixed a bug that did not close properly the plugin, this prevented the
  NVDAupdate the icon in the system tray.

# Wersja 2.0 #
* Weather Plus Settings menu in Preferences submenu moved.
* correct input on the fly is no longer saved, so it is temporary;
	* To call the city set in the preferences, press INSERT + control + f3.

# Wersja 1.9 #
* added help entering functions.
* added a new function for quick entry of Zip Code.
* added read / write configuration weather.ini, now no longer need to edit
  the source file.
* Weather menu added in the System Tray.
* added setting submenu Zip Code .
* added sub-setting temperature scale (Fahrenheit or Celsius).
* Dodano meni rozwijane pomoc.
* Dodano tłumaczenie włoskie.

# Wersja poprzednia 1.1 #
* Zaktualizowano dodatek.
* Pierwotne tłumaczenie w kodzie źrudłowym.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
