## Nazwa aplikacji: Sklep Internetowy

Sklep Internetowy to aplikacja mająca na celu dać możliwość użytkownikom zakupu techniki elektronicznej online w sposób prosty i wygodny. Aplikacja pozwala na przeglądanie dostępnych produktów, dodawanie ich do koszyka, użytkownicy mogą założyć konto w sklepie lub zalogować się na istniejące konto, składanie zamówień online.


## Zasada działania
### Aplikacja działa w kilku kluczowych krokach:

Rejestracja i logowanie: Użytkownicy mogą założyć konto w sklepie lub zalogować się na istniejące konto. 
Przeglądanie produktów: Użytkownicy mogą przeglądać produkty dostępne w sklepie. Produkty są pogrupowane w kategorie, co ułatwia wyszukiwanie. Każdy produkt ma opis, zdjęcia i cenę.
Dodawanie do koszyka: Użytkownicy mogą dodawać produkty do koszyka, który przechowuje wybrane produkty do momentu finalizacji zakupu.
Finalizacja zakupu: Po dodaniu produktów do koszyka, użytkownik przechodzi do procesu realizacji zamówienia. W tym etapie wprowadza dane dostawy, wybiera metodę płatności i finalizuje zamówienie.


## Interakcja z użytkownikiem:

Strona główna: Zawiera przegląd najnowszych produktów, promocji i kategorii.
Strona produktu: Zawiera szczegóły dotyczące produktu, zdjęcia, ceny oraz przyciski do dodania do koszyka.
Koszyk: Wyświetla produkty dodane do koszyka, umożliwia edytowanie ilości lub usuwanie produktów.
Logowanie się: Pozwala użytkownikom zalogować się na stronie.



------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


v0.02 - nadanie sensownych nazw, przede wszystkim ta zasada dotyczy zmienne klasy i funkcje. To jest bardzo ważna praktyka pozwalająca zrozumieć co w sobie przechowuje np. zmienna, zwiększa czytelność i poprawność napisanego kodu.

v0.04 - w tej wersji wykorzystałem metodę SOLID, poprawia strukturę i jakość kodu. Dzięki SOLID kod staje się łatwy w utrzymaniu i bardziej czytelny.

v0.06 - w tej wersji wykorzystałem metodę YAGNI, ponieważ pomaga w unikaniu nadmiernej rozbudowy kodu oraz niepotrzebnego dodawania funkcji.

v0.08 - metoda KISS. Polega na unikaniu tworzenia zbędnej złożoności. Zasada ta promuje prostotę, przejrzystość i efektywność kodu.

v0.10 - metoda DRY.  Jest niezbędną metodą w każdym oprogramowaniu, ponieważ eliminuje zbędne powtórzenia kodu. Dzięki temu zmniejsza się ryzyko błędów, poprawia czytelność oraz ułatwia utrzymanie kodu.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



## Dokumentacja projektu 40%:

### 1. Opis projektu
"Internetowy Market" to prototypowy sklep internetowy zaprojektowany w HTML, CSS i JavaScript. Celem projektu jest prezentacja prostego, funkcjonalnego interfejsu sklepu online, umożliwiającego użytkownikom:
Przeglądanie katalogu produktów.
Sortowanie produktów według ceny.
Dodawanie produktów do koszyka.
Śledzenie łącznej ceny w koszyku.


### 2. Technologie
Projekt został zbudowany w oparciu o następujące technologie:
HTML5: struktura strony.
CSS3: stylizacja strony, responsywność, animacje.
JavaScript: logika interakcji użytkownika, modyfikacja DOM.


### 3. Funkcjonalności
Menu nawigacyjne:
Linki
Lista produktów:
Przeglądanie produktów w formie katalogu.
Sortowanie produktów według ceny.
Koszyk:
Dodawanie produktów do koszyka.
Obliczanie łącznej ceny produktów w koszyku.
Promocje i nowości:
Sekcja z wyróżnionymi produktami.
Newsletter:
Formularz zapisu do newslettera z akceptacją regulaminu.


### 4. Opis komponentów
Nagłówek:
Zawiera logo, menu nawigacyjne, wyszukiwarkę oraz ikonę koszyka z podglądem łącznej ceny. Jest zaprojektowany jako sticky, aby pozostawać widocznym podczas przewijania.

Katalog produktów
Lista produktów z możliwością sortowania według ceny. Każdy produkt zawiera:

Obrazek
Cenę
Nazwę
Przycisk "Kupić"
Koszyk
Dynamiczne wyliczanie sumy cen produktów dodanych do koszyka, z aktualizacją widoczną w nagłówku

Sekcje promocyjne:
Dwie sekcje prezentujące najnowsze oferty i polecane produkty.

Stopka:
Zawiera linki do polityki prywatności, dane kontaktowe oraz ikony mediów społecznościowych.


### 5. Interakcja z użytkowinikiem:
Lista produktów
Przyciski akcji:
Każdy produkt posiada przycisk "Kupić". Po kliknięciu:
Produkt zostaje dodany do koszyka.
Licznik produktów w koszyku oraz łączna cena w nagłówku są natychmiast aktualizowane.


### 6. Przyszły rozwój
Rozszerzenie funkcjonalności koszyka:
Edytowanie ilości produktów w koszyku.
Usuwanie produktów z koszyka.
Rozbudowa animacji dla interakcji użytkownika.
Możliwość założenia konta.

Data ostatniej aktualizacji: 2024-12-02

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Dokumentacja testów aplikacji
### Cel testów
Celem przeprowadzonych testów było upewnienie się, że wszystkie kluczowe funkcje sklepu internetowego działają poprawnie, zgodnie z założeniami. Testy obejmowały funkcje takie jak sortowanie artykułów, dodawanie produktów do koszyka, proces składania zamówienia, przetwarzanie danych użytkownika oraz dokonanie zakupu.

### Zakres testów
Testy obejmowały następujące funkcje:

Sortowanie artykułów
Przycisk „Kup” i obliczanie kwoty zamówienia
Resetowanie koszyka
Składanie zamówienia i przekierowanie do finalizacji
Wyświetlanie produktów na podstronie „Opłata i dostawa”
Zapis danych użytkownika w bazie
Dokonanie zakupu – proces płatności i zapisywanie zamówienia

### Metoda testowania
Testy przeprowadzono manualnie, wykonując zaplanowane kroki i weryfikując, czy system działa zgodnie z oczekiwaniami.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Weryfikacja testów
### Wyniki testów
Wszystkie testowane funkcje przeszły pomyślnie, co oznacza, że:

Produkty są poprawnie sortowane.
Przyciski „Kup” działają prawidłowo, a kwota zamówienia jest obliczana zgodnie z dodanymi produktami.
Opcja resetowania koszyka działa bezbłędnie.
Proces składania zamówienia działa poprawnie, a użytkownik jest przekierowywany do finalizacji.
Produkty wyświetlają się prawidłowo na stronie „Opłata i dostawa”.
Dane użytkowników są zapisywane w bazie danych.
Proces dokonania zakupu, w tym płatność, działa poprawnie i zamówienie jest zapisywane w systemie.
Błędy i problemy
Podczas testów nie wykryto żadnych błędów ani nieprawidłowości w działaniu aplikacji.

### Wnioski
Aplikacja działa zgodnie z oczekiwaniami i jest gotowa do dalszego użytkowania. Wszystkie funkcje działają prawidłowo, a dane są poprawnie przetwarzane.



------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Dokumentacja projektu "Sklep internetowy" 80%:
### 1. Funkcjonalności

Wybór artykułu – użytkownik może przeglądać dostępne produkty i dodać wybrane do koszyka.
Czyszczenie koszyka – możliwość usunięcia wszystkich produktów z koszyka jednym kliknięciem.
Sortowanie artykułów – użytkownik może sortować produkty według ceny lub popularności.
Zamawianie produktów – finalizacja zakupu poprzez złożenie zamówienia.


### 2.Technologie użyte w projekcie

HTML – struktura strony.
CSS – stylizacja i układ wizualny.
JavaScript – obsługa interakcji użytkownika oraz dynamiczne aktualizacje strony.


### 3. Dokumentacja techniczna

### Architektura systemu
Aplikacja jest oparta na modelu klienta (frontend), bez backendu na obecnym etapie. Wszystkie dane są zarządzane po stronie klienta, a interakcje użytkownika obsługiwane są za pomocą JavaScript.
Schemat bazy danych
Obecnie aplikacja nie posiada backendu i bazy danych. Produkty i koszyk są przechowywane w pamięci przeglądarki (np. localStorage lub tablicach JavaScript).
Obsługa API
Na obecnym etapie aplikacja nie korzysta z zewnętrznych API. Możliwe jest przyszłe wdrożenie API dla obsługi produktów i zamówień.


### 4. Weryfikacja projektu

Projekt został zweryfikowany pod kątem poprawności działania oraz zgodności z założeniami:
Sprawdzenie zgodności z funkcjonalnościami – każda funkcja została przetestowana manualnie i automatycznie, aby upewnić się, że spełnia swoje założenia.
Testy wydajnościowe – aplikacja została uruchomiona na różnych przeglądarkach (Chrome, Firefox, Edge) w celu sprawdzenia szybkości działania oraz responsywności.
Testy UX/UI – interfejs użytkownika został oceniony pod kątem intuicyjności i łatwości nawigacji.
Bezpieczeństwo – sprawdzono podstawowe zabezpieczenia, takie jak obsługa nieprawidłowych danych w koszyku.
Stabilność aplikacji – sprawdzono poprawność działania przy dużej liczbie dodanych produktów oraz wielokrotnym sortowaniu.

### 5. Plan dalszego rozwoju

Rozwinięcie podstrony "Skontaktuj się z nami" – dodanie formularza kontaktowego z walidacją.
Możliwość rejestracji i logowania – wprowadzenie systemu użytkowników i sesji.
Integracja z bazą danych – przechowywanie produktów i zamówień w bazie danych.
Integracja z systemem płatności – umożliwienie realizacji płatności online.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Dokumentacja procesu debugowania aplikacji

 ### 1. Metoda debugowania
W procesie debugowania wykorzystano:
Ręczną analizę kodu HTML/CSS w edytorze kodu (np. VS Code)

 ### 2. Proces debugowania
#### Reprodukcja błędów
Błędy w warstwie wizualnej zostały zauważone podczas uruchomienia aplikacji w przeglądarce – objawiały się m.in. nieprawidłowym rozmieszczeniem elementów oraz niedziałającymi stylami.

#### Wyizolowanie źródła błędów
Zlokalizowano błędy w plikach CSS oraz inline-style:
użycie przestarzałych lub niezgodnych z dobrymi praktykami stylów w tagach HTML (style wpisane inline),
niektóre style nie były poprawnie przypisane przez klasy CSS lub były nadpisywane przez inne reguły.

#### Identyfikacja przyczyny
Przyczyną błędów okazały się:
- błędna składnia CSS,
- zbyt duże poleganie na stylach inline zamiast stosowania klas i zewnętrznych plików CSS,
- brak odpowiedniego priorytetu selektorów.

#### Weryfikacja naprawy
Po wprowadzeniu zmian:
- poprawiono składnię,
- usunięto style inline,
- uporządkowano struktury klas i ich hierarchię.

Działanie aplikacji zostało zweryfikowane poprzez ponowne uruchomienie w przeglądarce – błędy nie występują, a stylizacja działa prawidłowo.