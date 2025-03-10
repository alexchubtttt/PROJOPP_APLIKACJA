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

