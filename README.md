![zp2](https://user-images.githubusercontent.com/102677799/212494378-871c1a22-b5c6-45dd-806f-c89817d53530.jpg)

[ENGLISH VERSION](#english-version)


# TASK 1 
## Subtask 1

9 	:blush:

## Subtask 3
Cześć! Nazywam się Zofia Dańko i postanowiłam wziąć udział w **Dare IT challenge** aby z pomocą mentorek zdobyć doświadczenie oraz praktyczne umiejętnośći przy testowaniu aplikacji webowych i mobilnych. Potajemnie liczę też na dobrą zabawę w trakcie nauki, ciekawe wyzwania oraz sieć nowych kontaków :sweat_smile: 

## Subtask 4

Aplikacja https://scouts-test.futbolkolektyw.pl/pl służy do tworzenia i edytowania  raportów na temat zawodników piłki nożnej i rozegranych przez nich meczy.


Jej funkcjonalności to:


* logowanie/wylogowanie
* odzyskiwanie hasła
* możliwość wyboru języka aplikacji (polski/angielski)
* możliwość stworzenia gracza
* możliwość edycji danych gracza
* integracja z social media (FB i YT)
* możliwość przejrzenia danych wszystkich graczy
* możliwość wyszukania konkretnego gracza
* możliwość ściągniecia danych gracza w pliku csv
* wydrukowanie danych gracza
* możliwość filtrowania kolumn
* możliwość filtrowania tabeli
* funkcjonalność "dodaj mecz"
* funkcjonalność "edytuj mecz"
* dodawanie raportu z meczu i jego edycja
* funkcjonalność rozpocznij mecz
* funkcjonalność - DEV team contact
* Responsywny Layout


Niestety aplikacja posiada słaby interfejs i  jest mało intuicyjna. Do funkcji "dodaj" lub "edytuj mecz" można się dostać tylko poprzez gracza lub "aktywność". Posiada też wiele błędów. Raport z sesji przeprowadzonej na przeglądarce Chrome Wersja 108.0.5359.126, w którym znajdują się m.in. błędy i screenshoty umieściłam na githubie (plik XTSessionReport.html). Jest to jednak bardziej efekt mojej zabawy wtyczką niż profesjonalny raport :smirk: Lista błędów poniżej.


* Podczas odzyskiwania hasła nie trzeba wpisać maila aby dostać wiadomość "Wysłano wiadomość na podany adres e-mail".
* Przy wpisaniu złego loginu lub hasła wiadomość zwrotna jest w języku angielskim (pomimo ustawienia języka na polski).
* Po zmianie języka na polski wystąpiło dużo literówek.
* Przy zmianie języka logo na stronie głównej nie zmienia się.
* Przy tworzeniu gracza i edycji jego danych można wpisać niepoprawne wartości takie jak:


1. Zbyt mała lub duża waga np. - 100 (dodatkowo waga nie jest podana w jednostkach. Czy to kg czy funty?) 


2. Zbyt duży/mały wzrost.


3. Można dodać gracza który urodzi się dopiero w przyszłości lub miałby ponad 100 lat.


5. Można wpisać cyfry zamiast liter i litery zamiast cyfr, a nawet emotikony.


6. Można wprowadzić za dużo znaków w wyniku czego przy przeglądaniu graczy tekst nachodzi na inne kolumny i staje się nieprzejrzysty.

*  Pomimo zapisania danych przycisk "clear" przywraca pierwotne dane.
*  Przycisk "submit" i "clear" są w języku angielskim pomimo zmiany ustawień strony na polski.
* Przy próbie stworzenia gracza bez podania wszystkich wymaganych danych nie wszystkie wymagane pola podświetlają się na czerwono. Informacja zwrotna jest w języku angielskim. Pojawia się tylko jeden dymek z tekstem "wypełnij to pole".
* Nie ma możliwości kliknąć linku YT/FB podanego w danych gracza. 
* Przy tworzenie meczu czas gry może być minusowy.
* Data meczu może być w przyszłości.
* Istnieje możliwość rozegrania więcej niż dwóch połówek oraz minusowych połówek podczas meczu. 
* Nie ma możliwości ściągięcia raportu z meczu.
* Złe tłumaczenie na stronie głównej "linki pomocnicze".
* Dev team contact odnosi nas tylko do aplikacji slack zamiast do maila itp.




#### ENGLISH VERSION

# TASK 1 
## Subtask 1

9 	:blush:

## Subtask 3

HI, ma name is Zofia Dańko. I decided to take **Dare IT challenge** to gain experience and practical skills during web and mobile applications testing.
I count for interesting challenges, fun while learning, professional networking and career development.

## Subtask 4

The web application https://scouts-test.futbolkolektyw.pl/pl is used to create and edit reports about football players and matches played by them.

Application functionality:

     * login/logout
     * password recovery
     * ability to choose the language of the application (Polish / English)
     * ability to add a player
     * ability to edit player data
     * integration with social media (FB and YT)
     * possibility to view the data of all players
     * possibility to search for a specific player
     * possibility to download the player's data in a csv file
     * print player data
     * view columns
     * filter the table
     * "add match" functionality 
     * "edit match" functionality 
     * "add match report" functionality 
     * "edit match report" functionality 
     * "start match" functionality
     * "DEV team contact" functionality 
     * Responsive layout

Unfortunately, the application has a poor interface and is not very intuitive. The "add" or "edit match" function can only be accessed via player or "activity". It also has many bugs. You can find report from the session on my github (XTSessionReport.html file). Session was conducted on the Chrome browser Version 108.0.5359.126 and includes bugs and screenshots. However, this is more the effect of my playing with the plugin than a professional report 😏 List of errors below.

     * Whle recovering your password, you don't need to enter your e-mail to get the message "A message has been sent to the given e-mail address".
     * If you enter the wrong login or password, the return message is in English (despite setting the language to Polish).
     * There were a lot of typos after changing the language to Polish.
     * When changing the language, the logo on the home page does not change.
     * While you creating a player and editing his data, you can enter invalid values such as:

     1. Too little or too much weight, e.g. - 100 (No information about weight unit. Is it kg or pound?)

     2. Too big/small height.

     3. You can add a player who not born yet or would be over 100 years old.

     4. You can type numbers instead of letters and letters instead of numbers. You can also type emojis.

     5. Too many characters or digits can be entered. Beacuse of that text overlap other columns.

      * Despite saving the data, the "clear" button restores the original data.
      * The "submit" and "clear" buttons are in English despite changing the page settings to Polish.
      * When trying to create a player without providing all the required information, not all required fields are highlighted in red. The return message is in English.  
      * It is not possible to click on the YT/FB link provided in the player data.
      * When creating a match, the game time can be negative.
      * Match date may be in the future.
      * It is possible to play more than two halves and minus halves during match.
      * It is not possible to download the match report.
      * Wrong translation on home page "Linki pomocnicze".
      * Dev team contact only refers us to slack app instead of email etc.
