gitlab
============

Repozytorium zawiera opis laboratorium z podstaw wykorzystania systemu kontroli wersji Git, realizowanego w ramach przedmotu 'Podstawy Inżynierii Oprogramowania' prowadzonego przez Instytut Informatyki Stosowanej dla studentów kierunku Informatyka na wydziale Elektrotechniki, Elektroniki Informatyki i Automatyki Politechniki Łódzkiej.

Pliki:
----------------
Opis zadań laboratoryjnych znajduje się w pliku [git_lab_opis.pdf](https://github.com/radamus/gitlab/blob/master/git_lab_opis.pdf?raw=true).
Zmiany realizowane w poszczególnych zadaniach znajdują się w odrębnych folderach umieszczonych w folderze [context](https://github.com/radamus/gitlab/tree/master/context). Obecnie folder zawiera jeden przykładowy projekt.

Koncepcja
-----------------
Struktura laboratorium oddziela problem kontroli wersji (który jest tematem laboratorium), od projektu podlegającego kontroli wersji (który jest tylko przykładem - kontekstem). Zmiany, które należy wprowadzać w ramach przykładowego projektu, opisane są niezależnie, w osobnych plikach. Możliwa jest, dzięki temu, zmiana kontekstu kontroli wersji. Domyślnie jest to strona WWW, ale można wprowadzić kontekst bardziej programistyczny (np. projekt w Javie) lub temat nie związany z dziedziną wytwarzania oprogramowania (np. opracowywanie dokumentu ustawy). Ograniczeniem jest struktura laboratorium wprowadzająca określony scenariusz zmian.
Taka generyczność wymusza również adekwatny opis laboratorium, w którym np. zamiast określenia: "Otwórz stronę w przeglądarce w celu kontroli poprawności struktury po zmianach" znajduje się treść: "Przetestuj poprawność wprowadzonych zmian". Efektem takiego zabiegu jest powstanie sytuacji, w które student sam musi określić sposób kontroli poprawności, w zależności od rodzaju przykładu.


Scenariusze 
----------------
1. Praca indywidualna

    1. Inicjalizacja i połączenie ze sobą repozytorium lokalnego oraz zdalnego.
  2. Wersja początkowe projektu.
  3. Utworzenie gałęzi dla odrębnych cech.
  4. Rozwój cechy pierwszej.
  5. Wprowadzenie zmiany w gałęzi master i scalenie jej z gałęziami dla cech.
  6. Rozwój cechy drugiej.
  7. Scalenie cech z gałęzią master.
  8. Wysłanie do zdalnego repozytorium rezultatów i utworzenie wydania (release) projektu.

2. Praca zespołowa 

  1. Zdalne "sklonowanie" projektu kolegi/koleżanki na platformie GitHub i utworzenie na jego podstawie repozytorium lokalnego.
  2. Rozwój cechy 3.
  3. Wysłanie zmian do zdalnego repozytorium.
  4. Wysłanie informacji o zmianach (pull request) do właściciela projektu.
  5. Wprowadzenie zmian wykonanych przez kolegę/koleżankę do swojego repozytorium zdalnego i utworzenie kolejnego wydania projektu.

TODO
--------------
1. Inne przykłady (konteksty kontroli wersji)
