# challenge_portfolio_agnieszka
# **SPIS TREŚCI**
* [Zadanie 1](#task-1)
* [Zadanie 2](#task-2)
* [Zadanie 3](#task-3)
* [Zadanie 4](#task-4)
* [Zadanie 5](#task-5)

# **Task 5**
#### 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
* SELECT * FROM ACTORS ORDER BY SURNAME

![](https://raw.githubusercontent.com/AgnieszkaB1/challenge_portfolio_agnieszka/main/Zrzut%20ekranu%202022-11-28%20o%2023.03.31.png)
#### 2. Wyświetl film, który powstał w 2019 roku.
* SELECT * FROM MOVIES WHERE year_of_production =2019

#### 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.
* SELECT * FROM MOVIES WHERE year_of_production BETWEEN 1900 AND 1999
#### 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$ 
* SELECT TITLE, PRICE FROM MOVIES WHERE PRICE < 7

#### 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

#### 6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny. 
* SELECT * FROM CUSTOMERS WHERE CUSTOMER_ID IN (2,4,6) AND NOT CUSTOMER_ID = 5
#### 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
* SELECT * FROM CUSTOMERS WHERE CUSTOMER_ID IN (1, 3, 5)
#### 8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
* SELECT * FROM ACTORS WHERE NAME LIKE 'AN%'
#### 9. Wyświetl dane klienta, który nie ma podanego adresu email.
* SELECT * FROM CUSTOMERS WHERE EMAIL IS NULL
#### 10.  Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
* SELECT * FROM MOVIES WHERE PRICE >9 AND MOVIE_ID BETWEEN 2 AND 8
## Subtask 3

# **Task 4**

## Subtask 2
[Testowanie eksploracyjne aplikacji mobilnych](https://docs.google.com/document/d/1OlbZJxA7RsKmtlFZJ2mkPBR91d6SDaSmXM7XaTUWi4Q/edit?usp=share_link)

## Subtask 3

Do czego służy aplikacja Focusly? 

Aplikacja ta umożliwia nam wprowadzenie i praktykowanie medytacji, rozwoju wewnętrznego czy uważności. Na pewno dużym plusem jest fakt ze jest dostępna w formie mobilnej, można z niej korzystać w każdej chwili (o ile ma się dostęp do intenetu). Odbiorcą może byc każda osoba, która poszukuje wprowadzenia do medytacji, afirmacji albo porad związanych z rozwojem na wielu płaszczyznach. Myślę że skorzystają z niej zarówno osoby starsze jak i młode ponieważ interfejs jest czytelny i bardzo intuicyjny. Pozytywnym zaskoczeniem jest brak wyskakujących reklam nawet w podstawowej- darmowej- wersji. Osobiście brakuje mi funkcji pracy w trybie offline. Spotify czy YouTube pokazały nam że jest możliwość odtwarzania podcastów oraz muzyki bez połącznia internetowego co w przypadku medytacji może być przydatne. Nie będą nas wtedy rozpraszały żadne bodźce zewnętrzne (a można też wyjechać na zadupie bez dobrego połączenia internetowego :wink:)

Na chwilę obecną główną rożnicą jest dla mnie sam poziom trudności (który pewnie wynika z przyzwyczajenia do testowania aplikacji webowych). Trzeba skupić się na trochę innych funkcjonalnościach jak chociażby możliwość pracy w tle, zużycie baterii, czy sam sposób nawigacji po aplikacji. 

# **Task 3**

## Subtask 2 
[Testowanie według planów testów i raportowanie błędów](https://docs.google.com/document/d/1Uo8seh3jUhqUISe2zzOeCuHPcDR4DSjkdFhPAHreebQ/edit?usp=share_link)

## Subtaks 3

[Raport z przeprowadzonych testów](https://docs.google.com/document/d/17UqIgK6j8KvOEX0C2p4qAGlMr1F9hgzq18aijXYJ3fw/edit?usp=share_link)

# **Task 2** 
## Subtask 1

[Pisanie przypadków testowych na podstawie User Story](https://docs.google.com/document/d/1zruE5uYCEHi5lA7CgPvwbE_OFJQusfp7rz6GvhzPcTc/edit?usp=share_link)

## Subtask 2

[Pisanie przypadków testowych na podstawie własnych doświadczeń](https://docs.google.com/document/d/1apr1ixyxF0GCTytJUk68JiXe6GM79t9XkiTRDzp0LjM/edit?usp=share_link)

## Subtask 3

Test case'y systemtyzaują naszą wiedzę na temat danego projektu. Czytelnie napisane bezpośrednio pokazują nam jakie działania wywołują konkretne efekty. Dzięki temu wiemy dokładnie w którym momencie aplikacja nie odpowiada, tak jak życzył sobie tego klient, a jako że wszystkie nasze działania mamy zapisane krok po kroku to jesteśmy w stanie dojść do tego samego momentu po poprawkach i zobaczyć czy bug rzeczywiście został naprawiony (a przy okazji czy naprawa konkretnego elementu nie popsuła nam czegoś po drodze :D)

## Subtask 4

[Dla chętnych](https://docs.google.com/document/d/1mtB0XP-yVeUc0cYBEILwLDf9wCSBebS--EH6JedXCSI/edit?usp=share_link)
# **Task 1** 
## Subtask 1
9/10. Następnym razem bedzie max!
## Subtask 3 
Hej! Nazywam się Agnieszka. Dołączyłam do projektu z zamiarem wejścia do świata branży IT. Z milionem pomysłów w którym kierunku iść i dość długo trwającej eliminacji pozostałych opcji stwierdziłam, że testowanie oprogramowania będzie tym, w czym najlepiej się odnajdę. 
Wybrałam wasz kurs ponieważ wiem że sama teoria niewiele mi da, a nauka przez praktykę jest najlepszym sposobem.

Na dzień dzisiejszy skupiam się na testowaniu manualnym, ale to wie, może w przyszłości skuszę się na rozwój w stronę testera automatycznego?
## Subtask 4 
* Aplikacja ta, jak sama nazwa wskazuje, stworzona jest dla scoutów piłki nożnej. Nie ma jednak przeciwwskazań żeby korzytał z niej każdy, kto chce prowadzić ewidencję graczy i rozegranych przez nich meczów. Aplikacja jest czysta i przejrzysta. Ze względu na jej funkcję nie ma potrzeby dodawania zbędnych obrazków na stronie głównej. Istnieje możliwość stworzenia dokładnego profilu zawodnika oraz każdego rozegranego przez niego meczu. W raportach można odwzorować dokładny przebieg spotkania dla danego zawodnika ze wszystkimi akcjami przeprowadzonymi na boisku w czasie rzeczywistym. Odbywa się to na intuicyjnym planie boiska. W samym raporcie jest też miejsce na dokładniejsze opisanie całej rozgrywki. 

Poprawiłabym opcje dostępne po wejściu w zakładkę "rozpocznij mecz". Dostepne przyciski mogłyby pokazywać do czego służą po najechaniu na nie. Użytkownik który nie zna jeszcze aplikacji działa trochę na ślepo nie wiedząc czego dokladnie może się spodziewać. Dobrym pomysłem byłoby dodanie opcji przewinięcia meczu do tyłu, w razie gdyby scout nie zdążył dodać akcji na czas. Dodatkowo dodałabym też opcję dodania zdjęcia danego zawodnika. Przyspieszyłoby to odnlezienie go na liście. 

* Wykryte błędy

1.DevTools

-Błąd 404 po wklejeniu linka testowanej strony do przeglądarki. Na głównej stronie logowania pokazuje się miesjce żeby wprowadzić login i hasło więc wszystko wygląda prawidłowo. Po przejściu do zakładki sources wyświetla się kod więc nie jestem w stanie na chwilę obecną stwierdzić z czego ten błąd wynika.

-Przy zmianie urzadzenia na surface duo i wyborze trybu podwojnego ekranu część tresci jest nieczytelna. Linia przebiega przez środek. Niemożliwy jest odczyt tekstu (np. imię, które jest wymagane podczas tworzenia nowego użytkownika)

-Na mniejszych urządzeniach mobilnych po rotacji ekranu ucina możliwość przełącznia jezyka i/lub wylogowania się. Jest opcja zjechania w dół tego pola, jednak na pierwszy rzut oka nawet nie widać takiej możliwości. Rozwiązaniem mogłoby być przeniesienie tych dwóch przycisków w inne miejsce (np prawy, górny róg na niesbieskim tle).

2.Działanie aplikacji

-Przy tworzeniu nowego zawodnika po uzupełnionym jedym polu podświetla sie tylko jedno kolejne do wypełnienia. Lepiej by bylo gdyby od razu wszystkie wymagane pola podswietlały się na czerwono. 

-Po wpisaniu wszystkich potrzebnych danych wyskakuje okienko informujące o przeniesieniu na stronę edycji na której cały czas się znajdujemy.

-Po wejściu w zakładkę "gracze” i wpisaniu w wyszukiwarkę "ab" pojawia sie jeden o imieniu <script>alert(‚hello’)</script>. Nie jestem pewna czy ktoś tak nazwał zawodnika,  czy podczas tworzenia wyskoczył jakiś błąd.

-Po wejściu w zawodnika i dodaniu pozostałych, niewymaganych danych nie można zapisać zmian. Wyskakuje okno „ Nie udało sie zaktualizować gracza”. Po wpisaniu i zapisaniu każdego pola osobno widać że problemem był błędnie wpisany email. Warto by było dodać opcję podświetlenia na czerwono źle wypełnionego pola żeby szybko zweryfikować pomyłkę.





