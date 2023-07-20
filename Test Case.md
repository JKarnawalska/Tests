**<h2>Test Case: Sprawdzenie poprawnego działania przycisku "ukryj sekcję wyników"</h2>**


__Opis__

Test sprawdza, czy przycisk "ukryj sekcję wyników" działa poprawnie i ukrywa odpowiednią sekcję na stronie.

__Warunki wstępne__

1. Projekt jest uruchomiony i dostępny na stronie.
2. Sekcja wyników jest widoczna na stronie.


__Kroki testowe__

1. Otwórz stronę projektu.
2. Zlokalizuj sekcję wyników na stronie.
3. Sprawdź, czy sekcja wyników jest widoczna.
4. Zlokalizuj przycisk "ukryj sekcję wyników".
5. Kliknij przycisk "ukryj sekcję wyników".


__Oczekiwany rezultat__

Po kliknięciu przycisku "ukryj sekcję wyników", sekcja wyników powinna zostać ukryta.
Przycisk "ukryj sekcję wyników" powinien zmienić się na "pokaż sekcję wyników".
Sekcja wyników powinna być niewidoczna na stronie.


__Warunki końcowe__

Sekcja wyników jest ukryta na stronie.
Przycisk "ukryj sekcję wyników" jest widoczny jako "pokaż sekcję wyników".


__Notatki__

Test powinien być powtórzony dla różnych scenariuszy, na przykład gdy sekcja wyników jest już ukryta lub gdy użytkownik jest zalogowany.
Test może zostać rozszerzony o dodatkowe weryfikacje, takie jak sprawdzanie stanu przycisku po ponownym kliknięciu.
Ten test case ma na celu sprawdzenie, czy przycisk "ukryj sekcję wyników" działa zgodnie z oczekiwaniami i ukrywa odpowiednią sekcję na stronie.
Możesz go dostosować do swoich potrzeb i dodawać dodatkowe kroki lub weryfikacje, w zależności od specyfiki Twojego projektu.



**<h2>Test Case: Zwinięcie sekcji teorii i rozwinięcie edytora HTML</h2>**


__Opis__

Test sprawdza funkcjonalność zwijania sekcji teorii w edytorze HTML. Sprawdzane jest, czy sekcja zostaje poprawnie zwinęta, a następnie, czy można ją ponownie rozwinąć.



__Warunki wstępne__

Edytor HTML jest otwarty.
Sekcja teorii jest rozwinięta.


__Kroki testowe__

1. Sprawdź, czy sekcja teorii jest rozwinięta.
2. Sprawdź, czy zawartość sekcji teorii jest widoczna.
3. Sprawdź, czy przycisk "Zwiń" obok sekcji teorii jest dostępny.
4. Kliknij na przycisk "Zwiń" obok sekcji teorii.


__Oczekiwany rezultat__

Sekcja teorii zostaje zwinęta, zawartość sekcji teorii jest ukryta.
Przycisk "Zwiń" zmienia się na "Rozwiń".


__Warunki końcowe__

Sekcja teorii jest zwinięta, zawartość sekcji teorii jest niewidoczna.
Przycisk "Rozwiń" jest dostępny obok sekcji teorii.


__Notatki__

Upewnij się, że po zwinieciu sekcji teorii zawartość jest ukryta i nie jest widoczna dla użytkownika.


 **<h2>Test Case "Responsywności menu nawigacji w nagłówku"</h2>**

<h3>Opis</h3> 

Przetestuj responsywność menu nawigacji w nagłówku strony internetowej na różnych rozdzielczościach ekranu oraz sprawdź nawigację strzałkami.


<h3>Warunki wstępne</h3>

Strona internetowa jest załadowana i menu nawigacji w nagłówku jest widoczne.



<h3>Kroki testowe</h3>

1. Zmniejsz rozdzielczość ekranu do szerokości mniejszej niż 768 pikseli.
2. Sprawdź, czy menu nawigacji koliduje ze sobą lub wychodzi poza granice ekranu.
3. Kliknij na przycisk menu (hamburger).
4. Sprawdź, czy menu rozwija się i wyświetla się poprawnie.
5. Kliknij na dowolny element menu.
6. Kliknij w strzałki lewo i prawo
7. Sprawdź, czy zostajesz przeniesiony do odpowiedniej sekcji strony.


<h3>Oczekiwany rezultat</h3>

Menu nawigacji nie koliduje ze sobą ani nie wychodzi poza granice ekranu na małych rozdzielczościach.
Po kliknięciu na przycisk menu, menu rozwija się i wyświetla się poprawnie na małych rozdzielczościach.Strzałki w lewo lub prawo kierują użytkownika 
na kolejne sekcje strony. Po kliknięciu na element menu, użytkownik jest przenoszony do odpowiedniej sekcji strony.


<h3>Warunki końcowe</h3>

Test został wykonany na różnych rozdzielczościach ekranu i menu nawigacji działa poprawnie.Strzałki przekierowały użytkownika na inne sekcje strony.


<h3>Notatki</h3>

Upewnij się, że test jest przeprowadzany na różnych urządzeniach i przeglądarkach, aby upewnić się, że menu nawigacji jest responsywne na każdej platformie. Sprawdź również, czy menu poprawnie reaguje na zmiany rozmiaru ekranu w czasie rzeczywistym.
Sprawdź, czy przycisk "Rozwiń" działa poprawnie po zwinieciu sekcji.
Sprawdź czy strzałki kierują na kolejne sekcje strony.
Można również sprawdzić, czy po zwinięciu sekcji teorii miejsce na ekranie jest odpowiednio zwolnione.




