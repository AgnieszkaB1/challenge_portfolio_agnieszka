# challenge_portfolio_agnieszka
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





Dodatkowo, już poza zadniami, chciałam zwrócic uwagę na badanie stron przy użyciu DevToolsów. Pracuje na macu i moją główną przeglądarką internetową jest safari gdzie wygląda to trochę inaczej. Zanim odkryłam na czym polega mój błąd i przerzuciłam się na chrome miałam problem z niktórymi opcjami (niektórych do teraz nie znalazłam :d). Moja ocena subtasku 4 na peoblmatyczny wynika więc raczej z tego powodu, po zmianie przęglądarki wszystko się zgadzało i było bardzo dobrze wytłumaczone.
