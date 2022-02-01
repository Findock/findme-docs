# Struktura projektu oraz plan pracy

## Określenie struktury projektu

### Sprecyzowanie celów projektu

Celem projektu jest stworzenie działającej aplikacji, pozwalającej jej użytkownikom na dodawanie ogłoszeń, komentowanie ogłoszeń oraz wymianę wiadomości w czasie rzeczywistym pomiędzy użytkownikami. Głównym celem aplikacji jest umożliwienie użytkownikom prostego i szybkiego dodawania ogłoszeń zaginionych zwierząt oraz śledzenia postępu ogłoszenia przez komentarze dodawane przez innych użytkowników. Użytkownicy mogą dodawać zdjęcia do ogłoszeń oraz do komentarzy. Duży nacisk będzie kładziony na funkcjonalność wykorzystania lokalizacji urządzeń użytkowników aplikacji - do ogłoszeń będzie dodawana pinezka lokalizacji, przez co aplikacja będzie mogła wysłać powiadomienia do innych urządzeń w pobliżu o nowym ogłoszeniu, aby dało to możliwość natychmiastowego zareagowania. Użytkownicy będą mogli też wyświetlać dane kontaktowe twórcy ogłoszenia, dzięki czemu aplikacja umożliwi prosty kontakt nie tylko przez “czat” w aplikacji, ale także przez tradycyjne metody komunikacji - telefon, sms lub email.

### Zebranie dodatkowych informacji dotyczących projektu

Przeprowadziliśmy research odnośnie podobnych aplikacji / forum internetowych. W tym momencie brakuje aplikacji, które skupiają się tylko na tej funkcjonalności oraz dawały użytkownikowi tak spersonalizowane narzędzia do rozwiązania tego problemu. Żaden gigant technologiczny nie prowadzi aktualnie rozwoju swoich aplikacji w tym kierunku, a ludzie zmuszeni są szukać zaginionych zwierząt pośrednio przez funkcje innych aplikacji np. grupy na portalu Facebook lub po wielu rozproszonych forach użytkowników.

### Ustalenie kryteriów podziału projektu

Wynikiem projektu będzie jedna aplikacja na urządzenia mobilne, komunikująca się z jedną aplikacją serwerową połączoną z jedną bazą danych do przechowywania informacji.

Prace nad aplikacjami są podzielone na wiele etapów oraz każdemu z nich możemy ustalić kryteria podziału.

Podział projektu:

#### Szablony oraz makiety ekranów aplikacji

Wszystkie makiety oraz prace graficzne przygotowane do zwizualizowania oraz oszacowania ilości pracy potrzebnej do stworzenia aplikacji, wizualizacji scenariuszów użytkowników oraz bazy projektowej dla programistów aplikacji mobilnej.

#### Aplikacja mobilna (frontend)

Całość aplikacji zainstalowanej na urządzeniu użytkownika, z testami oprogramowania prowadzonymi przez dewelopera aplikacji mobilnej, cały kod źródłowy aplikacji mobilnej oraz wszystkie biblioteki używane w projekcie, pliki instalacyjne i konfiguracyjne aplikacji, konfiguracja środowiska deweloperskiego.

#### Aplikacja serwerowa (backend)

Całość aplikacji uruchomionej na serwerze z dostępem do bazy danych aplikacji, z testami oprogramowania prowadzonymi przez dewelopera aplikacji serwerowej, cały kod źródłowy aplikacji mobilnej oraz wszystkie biblioteki używane w projekcie, pliki instalacyjne i konfiguracyjne aplikacji, konfiguracja środowiska deweloperskiego.

#### Baza danych

Szablony używane w bazie danych, stworzenie środowiska bazy danych, tabel, schematów oraz populacja bazy danych wymaganymi danymi, biblioteki połączenia bazy danych do aplikacji serwerowe.

### Określenie struktury hierarchicznej projektu

Nasz projekt będzie skupiał się na rozwoju jednej aplikacji, która za cel ma dostarczyć jedną funkcjonalność według jednoznacznego celu.

Projekt będzie prowadzony według kolektywnej struktury zespołu, aby zmniejszyć wpływ indywidualnych charakterów członków zespołu na finalny efekt projektu. Główną cechą takiej struktury jest brak rozpoznawalnego przywódcy. Decyzje podejmuje się poprzez powszechną zgodę. Wymagane jest zaangażowanie każdego członka zespołu w poszczególne zadania projektu. Wykorzystanie takiej struktury pozwoli zachować aktywną komunikację i działanie między członkami zespołu. Według definicji struktura ta przydaje się, gdy pracownicy o wyrazistych osobowościach nie chcą podporządkować się jednemu liderowi, co idealnie reprezentuje nasz zespół.

Każdy członek naszego projektu będzie równo zaangażowany w ~30% całej funkcjonalności końcowej projektu.

## Planowanie przebiegu projektu

### Określenie czasu realizacji czynności projektu

Projekt wstępnie jest oszacowany na 42 dni planowania oraz 207 dni pracy programistów, 10 dni testów alpha, 20 dni testów beta, 20 dni wdrożenia aplikacji, składa się na to:

- Wdrożenie środowiska deweloperskiego
- Stworzenie projektów programistycznych
- Stworzenie oraz skonfigurowanie repozytorium kodu
- Stworzenie dokumentacji projektowej 
- Stworzenie ram projektu przez scenariusze użytkownika
- Stworzenie szablonów graficznych aplikacji
- Stworzenie makiet wyglądu ekranów aplikacji
- Prowadzenie dokumentacji postępu nad pracami projektowymi
- Projekt bazy danych
- Wdrożenie bazy danych
- Pracę nad aplikacją mobilną 
- Pracę nad aplikacją serwerową
- Testy wewnętrzne
- Testy alpha
- Testy beta
- Wdrożenie aplikacji do sklepów aplikacji mobilnych
- Wsparcie aplikacji w czasie życia aplikacji

### Planowanie terminów realizacji projektu

| Milestone | Termin |
|-|-|
| Określenie planów projektu | 30 stycznia 2022 r. |
| Rozpoczęcie pracy deweloperów | 1 lutego 2022 r. |
| Pierwszy pełny prototyp aplikacji | 1 października 2022 r. | 
| Rozpoczęcie testów alpha aplikacji | 2 października 2022 r. |
| Zakończone testy alpha aplikacji | 15 października 2022 r. |
| Rozpoczęcie testów beta aplikacji | 20 października 2022 r. | 
| Zakończenie testów beta aplikacji | 20 listopada 2022 r. |
| Wdrożenie aplikacji do sklepów aplikacji mobilnych | 20 grudnia 2022 r. |
| Pierwsze pobrania aplikacji ze sklepów | 1 stycznia 2023 r. |

### Obliczenie rezerw czasu

Czas pracy deweloperów nad projektem szacowany jest na 207 dni pracy, dodajemy do tego 33 dni rezerwy.

Czas testów alpha jest szacowany na 10 dni dodajemy do tego 3 dni rezerwy

Czas testów beta jest szacowany na 20 dni dodajemy do tego 10 dni rezerwy

Czas wdrożenia szacowany jest na 20 dni dodajemy do tego 10 dni rezerwy

### Określenie krytycznych elementów projektu

- Zabezpieczenia protokołu wymiany danych aplikacji mobilnej oraz serwera
- Zabezpieczenia bazy danych oraz jej fizyczna lokalizacja
- Moduł czatu w czasie rzeczywistym w aplikacji mobilnej
- Moduł lokalizacji w aplikacji mobilnej
- Szybkość wymiany danych pomiędzy aplikacją mobilną oraz aplikacją serwera
- Wdrożenie aplikacji do sklepów z aplikacjami mobilnymi

### Weryfikację przebiegu projektu

Projekt będziemy weryfikować przez stworzone wcześniej tickety w narzędziu Jira, pozwoli nam ona zaplanować pracę nad całym projektem w czasie ponad półtorej roku. Pracę będziemy weryfikować po każdym pełnym przebiegu iteracji projektowej, czas iteracji ustalamy na czas 3 tygodni w fazie tworzenia rozwiązania oraz czas 1 tygodnia w czasie testowania prototypu / aplikacji oraz 2 tygodni podczas wdrażania aplikacji.

## Plan projektu jest prowadzony przez narzędzie Jira

Harmonogram projektu  
[mvtthew.atlassian.net/jira/roadmap](https://mvtthew.atlassian.net/jira/software/projects/FM/boards/1/roadmap)

Backlog projektu  
[mvtthew.atlassian.net/jira/backlog](https://mvtthew.atlassian.net/jira/software/projects/FM/boards/1/backlog)

## Charakterystyka używanych narzędzi / technikaliów:

- Google Docs - przygotowanie dokumentacji projektowej
- Google Gmail - wymiana korespondencji projektowej
- Figma - przygotowanie szablonów graficznych oraz makiet aplikacji
- Facebook Messenger - komunikacja zespołu 
- Discord - komunikacja zespołu
- Visual Studio Code - edytor kodu
- Jetbrains Webstorm - edytor kodu
- Git - system kontroli wersji
- Github - platforma z repozytoriami naszego kodu, pozwoli nam na szybką oraz wydajną pracę nad zmianami w kodzie
- React Native - framework frontendu aplikacji, pozwoli nam tworzyć aplikację na oba wiodące systemu mobilne (iOS oraz Android) na raz
- Nodejs - środowisko uruchomienia kodu serwerowego
- NestJS - framework backendu aplikacji, pozwoli zachować skalowalność oraz możlwiość rozwoju aplikacji w przyszłości oraz stabilność
- SonarCloud - statyczna analiza kodu
- CircleCI - pipeline CI
- Codecov - analiza code coverage
- MongoDB - baza danych, da nam szybkość oraz elastyczność, która idealnie wpasuje się w projektu
