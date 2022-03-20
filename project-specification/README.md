# Specyfikacja projektowa i techniczna

## Inicjowanie projektu

### Nazwa projektu

Nazwa jaką wybraliśmy dla naszego projektu to FindMe z angielskiego „find me” co oznacza znajdź mnie. Nazwa w języku angielskim jest według nas bardziej chwytliwa i łatwiejsza do zapamiętania. Zdecydowanie lepiej prezentuje się pod względem wizerunkowym i znacząco prościej się wymawia w porównaniu do polskiego odpowiednika.

### Analiza i ocena ryzyka

- Wypowiedzenie/rezygnacja członka zespołu (2 / 4 = wysokie)
- Brak wystarczającej ilości czasu, aby zdobyć wiedzę, która ma sprostać oczekiwaniom projektu (3 / 5 = krytyczne)
- Powstanie podobnej aplikacji na rynku (np. na Facebooku) (1 / 5 = wysokie)
- Brak akceptacji pracy przez promotora (1 / 5 = wysokie)
- Utrata pracy (niewystarczające fundusze na realizację projektu) (1 / 3 = średnie)
- Brak czasu na projekt/ losowe wypadki uniemożliwiające zmieszczenie się w przeznaczonym czasie na wykonanie projektu (np. praca) (1 / 4 = wysokie)

### Ocena nakładów i korzyści

#### Nakłady

- 1.5 roku pracy trójosobowego zespołu programistów, co przekłada się na 1680 godzin pracy nad projektem.
- Rozeznanie się w temacie zaginionych zwierząt
- Stworzenie wielu makiet szablonu graficznego aplikacji
- Stworzenie aplikacji  na systemy mobilne (zarówno Android jak i iOS)
- Stworzenie aplikacji serwerowej do obsługi aplikacji
- Stworzenie struktury obiektowej bazy danych służącej do zapisu danych
- Stworzenie regulaminu korzystania z usługi

#### Korzyści

- Satysfakcja z odnalezionych zwierząt dzięki naszej aplikacji
- Kontakty wywiązujące się ze współpracy ze schroniskami
- Możliwość wdrożenia nowej aplikacji open-source oraz non-profit

### Plan bazowy

- Stworzenie dokumentacji wstępnej
- Utworzenie wymagań projektowych
- Zapisanie wymagań w postaci historyjek oraz epik w programie Jira
- Przygotowanie makiet wyglądu aplikacji
- Wybór oraz zapoznanie się z technologiami, które najlepiej wpasują się w wymagania
- Wybranie silnika bazy danych
- Rozpisanie wzorców schematów obiektów w bazie danych
- Rozpoczęcie pracy nad aplikacją
- Testy prototypu aplikacji
- Zakończenie pracy nad aplikacją 
- Testy beta aplikacji
- Wdrożenie aplikacji do sklepu play oraz app store
- Utrzymanie aplikacji

### Opis norm

#### Komunikacja
- Stand-up'y co 3 dni o godzinie 21:30
- Review co 2 tygodnie w niedzielę
- Spotkania z wykładowcą podczas zajęć na uczelni
- Spotkania kwartalne

#### Narzędzia

- Github – prowadzenie projektu, śledzenie zmian
- Jira – planowanie projektu, przydzielanie tasków, monitorowanie przebiegu projektu
- Discord – komunikacja

#### Techniczne

- React Native – aplikacja mobilna
- Figma – projektowanie szablonu graficznego aplikacji
- NestJS – backend
- MongoDB – baza danych
- SonarCloud - statyczna analiza kodu
- CircleCI - pipeline CI
- Codecov - analiza code coverage

### Punkty kontrolne

- Inicjowanie
- Projektowanie
- Kodowanie
- Testy zamknięte (alpha)
- Testy otwarte (beta)
- Deployment
- Maintenance

### Opis zakładanej jakości

- Prosta w obsłudze - z aplikacji może bez problemu korzystać osoba w każdym wieku
- Przyjemny dla oka oraz prosty interfejs użytkownika - duże łatwe w kliknięciu przyciski, szybkość działania, minimalistyczny wygląd, tylko najpotrzebniejsze informacje oraz funkcje
- Możliwość dodania ogłoszenia w każdym momencie - możemy otworzyć aplikację oraz dodać ogłoszenie w 2 minuty
- Możliwość dodania komentarza do ogłoszenia w każdym momencie - możemy otworzyć aplikację oraz bezproblemowo dodać komentarz do ogłoszenia w mniej niż minutę
- Aplikacja wysyła powiadomienia do użytkownika
- Możliwość wyłączenia oraz włączenia uprawnień przez użytkownika aplikacji w prosty sposób - ustawienia aplikacji
- Prosta opcja odinstalowywania aplikacji - brak śmieci po odinstalowaniu aplikacji 
- Możliwość dodania zdjęć prosto z interfejsu aplikacji - użytkownik może dodać zdjęcia przez przycisk w aplikacji i nie musi uruchamiać - osobno aplikacji aparatu
- Możliwość szybkiego zlokalizowania się w aplikacji - użytkownik nie musi wpisywać lokalizacji, lecz ma szybką opcję “zlokalizuj mnie”

### Zakres funkcjonalności

- Możliwość stworzenia konta użytkownika
- Możliwość zalogowania się na konto użytkownika
- Możliwość przypomnienia hasła na wypadek jego zapomnienia
- Obsługa autoryzacji oraz zapamiętywanie danych logowania użytkownika na jego urządzeniu
- Możliwość zapomnienia zapamiętanych danych na urządzeniu
- Możliwość sprawdzenia historii dostępu (logowania) na konto użytkownika
- Możliwość edycji danych konta
- Możliwość dodania oraz usunięcia zdjęcia profilowego do konta
- Aplikacja wysyła do użytkownika natywne systemowe powiadomienia
- Możliwość dostosowania powiadomień wysyłanych przez aplikację
- Użytkownik ma możliwość kompletnego usunięcia konta z aplikacji
- Możliwość dodania ogłoszenia 
- Możliwość dodania zdjęć do ogłoszenia
- Możliwość wyszukiwania ogłoszeń
- Możliwość przeglądania wszystkich ogłoszeń 
- Możliwość edycji swoich ogłoszeń
- Możliwość rozwiązywania swoich ogłoszeń
- Możliwość archiwizacji ogłoszenia
- Możliwość dodania ogłoszenia do obserwowanych
- Możliwość przeglądania ogłoszeń ostatnio oglądanych
- Możliwość przeglądania szczegółów ogłoszeń
- Możliwość zobaczenia numeru telefonu dodającego ogłoszenie po wcześniejszym zaakceptowaniu regulaminu aplikacji
- Możliwość dodawania komentarzy do ogłoszenia
- Możliwość dodania zdjęcia w komentarzu do ogłoszenia
- Możliwość dodania znacznika lokalizacji do komentarza ogłoszenia
- Możliwość edytowania swoich komentarzy
- Możliwość archiwizowania swoich komentarzy
- Możliwość edycji uprawnień aplikacji (lokalizacja, powiadomienia)
- Możliwość czatowania z innymi użytkownikami aplikacji
- Możliwość otrzymywania wiadomości czatu w czasie rzeczywistym
- Możliwość przesyłania zdjęć przez czat
- Możliwość przesyłania lokalizacji przez czat
- Możliwość zmiany motywu (dark mode / light mode)

## Szczegóły projektu

### Opis projektu

FindMe to narzędzie, które ma zapewnić dodatkową pomoc w odnalezieniu zagubionego zwierzęcia.  Jest to aplikacja mobilna z przyjaznym, intuicyjnym interfacem. Użytkownicy aplikacji mogą dzięki niej wymieniać się informacjami na temat zagubionych lub znalezionych zwierząt przez ogłoszenia, komentarze oraz prowadzenia konwersacji na chacie.

### Geneza

Pomysł na aplikacje wziął się z przykrych zaistniałych sytuacji życiowych. Poszukując zwierzaka/właściciela zaginionego zwierzaka wyczerpaliśmy możliwości poszukiwawcze, a kontakt ze schroniskiem był niemożliwy, bądź utrudniony.

### Cel projektu

Celem aplikacji ma być usprawnienie procesu poszukiwania zaginionego zwierzęcia, odciążenie schronisk, zwiększenie zasięgu poszukiwań i zmniejszenie sytuacji nielegalnego pozbywania się zwierząt. Istotą projektu jest wzrost szans dla właściciela i jego ukochanego pupila na ponowne spotkanie oraz zmniejszenie czasu oczekiwania i środków, jakie należy  poświęcić, aby poszukiwania zakończyły się sukcesem.

### Wartości

Dzięki naszej aplikacji pomoc poszukującym osobom jak i zagubionym zwierzętom będzie zdecydowanie ułatwiona. Przez brak schronisk bądź ich przepełnienie ludzie chętnie skorzystają z alternatywy jaką jest nasza aplikacja.

Gdy zauważymy na ulicy zwierzę, którego nie będziemy mogli złapać, wystarczy że zrobimy jego zdjęcie i udostępnimy lokalizację, w której było ostatni raz widziane. Dodatkowo dzięki systemowi komunikacji - chat/komentarze - w łatwy i szybki sposób można porozumiewać się z innymi użytkownikami i być na bieżąco.  Zyskamy nowy, innowacyjny sposób na zrobienie czegoś dobrego bez dużego wysiłku. Niejednokrotnie można stać się “bohaterem” i zapobiec rozerwaniu więzi między właścicielem a jego pupilem w czasie rozłąki, a tym samym dać kolejną szansę na ich spotkanie. W przypadku zagubienia zwierząt przy ruchliwych ulicach możemy też zaradzić wypadkowi i uratować życie zarówno zwierzaka, jak i człowieka. Z pewnością jest to dobry krok, aby zniwelować starty i smutek w rodzinach, które zbudowały mocną więź ze zwierzęciem. Dzięki temu kryzys związany z jego chwilową nieobecnością spowodowany zaginięciem zostanie w szybki i tani sposób zażegnany.

### Milestones

- Przygotowanie planu projektowego
- Analiza rynku oraz research tematu
- Wybór metodologii prowadzenia projektu 
- Wybór technologii oraz frameworków technicznych
- Wykonanie projektów interfejsów dla aplikacji mobilnej
- Zebranie zespołu projektowego - programistycznego
- Przygotowane pierwsze makiety wszystkich ekranów aplikacji
- Przygotowanie pierwszego prototypu szkieletu aplikacji
- Aplikacja, w której możemy dodać ogłoszenie
- Aplikacja, w której możemy dodawać komentarze do ogłoszeń
- Aplikacja, w której możemy czatować z innymi użytkownikami
- Aplikacja, która na podstawie lokalizacji dostosowywuje wyniki wyszukiwania
- Pierwsza alpha aplikacji
- Pierwsza beta aplikacji 
- Zakończenie prac nad aplikacją
- Publikowanie aplikacji w Google Play
- Publikowanie aplikacji w Apple App Store

### Sukces projektu

Projekt odniesie sukces gdy pierwszy zaginiony zwierzak znajdzie swój dom.

### Ryzyko projektu

Ryzykiem dla naszego projektu jest np. powstanie podobnego narzędzia mocniej przemawiającego do użytkownika lub wykreowany przez bardziej znane/ą osoby/ę, które może sprawić, że nasz nie odniesie sukcesu i ludzie stracą zainteresowanie naszą aplikacją, co znacząco wpłynie na redukcję liczby jej pobierania. Kolejnym, dość istotnym ryzykiem jest brak kompetencji zespołu projektowego, brak funduszy na rozwój, słaba organizacja i komunikacja, które mogą zablokować nasz projekt lub opóźnić jego wykonanie. Należy również wziąć pod uwagę wszelkie losowe wypadki, jakie mogą wydarzyć się podczas pracy nad projektem, co w efekcie końcowym może znacznie wydłużyć czas oczekiwania na wdrożenie aplikacji do życia. Istotnym elementem są testy końcowe, które mogą uwydatnić błędy, których nie udało się wcześniej wykryć. Tym samym zespół projektowy musi dołożyć wszelkich starań, aby doprowadzić aplikację do ładu, co niesie ze sobą dodatkowe, być może nie do końca przewidziane dni lub nawet tygodnie dalszej pracy.

### Dane aplikacji (baza danych, przetwarzane dane przez aplikacje)

Ogłoszenia w aplikacji dostarczane są przez jej użytkowników, dostarczą one wszystkie niezbędne informacje o zaginionym lub znalezionym pupilu. Zarówno informacje tekstowe, daty, lokalizacje jak i zdjęcia będą przetrzymywane w bazie danych.

Wszystkie dane w bazie danych będą zaszyfrowane.

#### Użytkownik

- Imię
- Nazwisko
- Adres email
- Hasło dostępu
- Numer telefonu
- Lokalizacja
- Zdjęcie profilowe
- Dodane ogłoszenia
- Obserwowane ogłoszenia
- Ostatnio oglądane ogłoszenia (historia przeglądania ogłoszeń)
- Ostatnio szukane ogłoszenia (historia wyszukiwania ogłoszeń)
- Czaty z innymi użytkownikami
- Wiadomości czatu wysłane do innych użytkowników
- Komentarze zamieszczone pod ogłoszeniami
- Data dołączenia do aplikacji
- Data usunięcia konta (jeżeli istnieje)

#### Ogłoszenie

- Tytuł
- Data publikacji
- Opis
- Zdjęcia
- Lokalizacja 
- Umaszczenie
- Płeć
- Kategoria
- Dane o użytkowniku zamieszczającym ogłoszenie
- Komentarze do ogłoszenia

#### Komentarz

- Wiadomość
- Data publikacji
- Dane o użytkowniku zamieszczającym komentarz

#### Wiadomość czatu

- Wiadomość 
- Data publikacji
- Dane o użytkowniku wysyłającym wiadomość

#### Powiadomienia

- Tytuł
- Data publikacji
- Wiadomość
