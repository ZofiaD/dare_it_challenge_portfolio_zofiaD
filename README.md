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


  * Zbyt mała lub duża waga np. - 100 (dodatkowo waga nie jest podana w jednostkach. Czy to kg czy funty?) 


  * Zbyt duży/mały wzrost.


  * Można dodać gracza który miałby teraz ponad 100 lat lub urodzi się dopiero w przyszłości.


  * Można wpisać cyfry zamiast liter i litery zamiast cyfr, a nawet emotikony.


  * Można wprowadzić za dużo znaków w wyniku czego przy przeglądaniu graczy tekst nachodzi na inne kolumny i staje się nieprzejrzysty.

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

# TASK 2

## Subtask 1 - *Pisanie przypadków testowych na podstawie User Story.*

Znajdziesz moje test case'y tutaj  https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing


## Subtask 2 - *Pisanie przypadków testowych na podstawie “własnych doświadczeń"*.

Znajdziesz moje test case'y tutaj  https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing

## Subtask 3 - *Po co piszemy test case’y?*

Moim zdaniem przypadki testowe piszemy, ponieważ pomaga nam to planować testy.
Łatwiej jest z ich pomocą zweryfikować zgodność oprogramowania z wymaganiami. Są pewnego rodzaju instrukcją dla testera, pomocną zwłaszcza dla nowych testerów w projekcie. Umożliwiają również skuteczne i spójne testowanie regresji.

## Subtask 4 *Pisanie przypadków testowych na podstawie “własnych doświadczeń"*. - **Pick Eat Up** - aplikacja mobilna.

Znajdziesz moje test case'y tutaj  https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing




#### ENGLISH VERSION

# TASK 1 
## Subtask 1

9 	:blush:

## Subtask 3

Hi, my name is Zofia Dańko. I decided to participate in **Dare IT challenge** to gain experience and practical skills during web and mobile applications testing.
I expect interesting challenges, fun while learning, professional networking and career development.

## Subtask 4

The web application https://scouts-test.futbolkolektyw.pl/pl is used to create and edit reports about football players and matches they played.

Application functionality:

 * login/logout
 * password recovery
 * language switching (Polish / English)
 * adding a player
 * editing player data
 * integration with social media (FB and YT)
 * displaying all players data
 * searching for a specific player
 * downloading the player's data in a CSV file
 * printing players data
 * columns filtering option
 * table filtering option
 * "add match" functionality 
 * "edit match" functionality 
 * "add match report" functionality 
 * "edit match report" functionality 
 * "start match" functionality
 * "DEV team contact" functionality 
 * Responsive layout

Unfortunately, the application has poor interface and is not very intuitive. The "add" or "edit match" function can only be accessed via player or "activity". It also has many bugs. The report from the exploratory testing session can be found on my Github (XTSessionReport.html file). The session was conducted on the Chrome browser Version 108.0.5359.126. The report includes screenshots of bugs. However, it is the effect of experimenting with the plugin, rather than a professional report 😏. List of errors below.

 * Whle recovering your password, after clicking "SEND" button, the pop-up with "Message sent successfully" appears whether or not you have entered your e-mail address.
 * Once you enter wrong login or password, the return message is always in English (despite having the Polish language chosen).
 * There were a lot of typos after changing the language to Polish.
 * After switching the language, the logo language on the home page does not change.
 * While creating a player or editing his or her data, you can enter invalid values such as:

   * Weight displayed as negative number, e.g. - 100, or ridiculously heavy or no information about weight unit (is it kg or pound?)

   * Too great or too small height.

   * You can add a player who has not been born yet or would be over 100 years old.

   * You can type numbers instead of letters and letters instead of numbers. You can also type emojis.

   * Too many characters or digits can be entered. Beacuse of that, the text can overlap other columns.

  * Despite saving the data, the "clear" button removes the provided data.
  * The "submit" and "clear" buttons are in English despite changing the page settings to Polish.
  * When trying to submit a player data, without providing all the required information, not all required fields are highlighted in red. The return message is in English.  
  * It is impossible to click on the YT/FB link provided during the player data creation step.
  * When creating a match, the game time can be displayed as a negative number.
  * You can create a report of a match that has not yet taken place.
  * It is possible to play more than two halves and minus halves during a game.
  * It is not possible to download the match report.
  * Wrong translation of "Linki pomocnicze" button on home page.
  * Dev team contact hyperlink redirects to slack app only (instead of email etc.).

# TASK 2

## Subtask 1 - *Writing test cases based on User Story.*

Please find my test ceases on https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing

## Subtask 2 - *Writing test cases based on your "own experience"*

Please find my test ceases on https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing

## Subtask 3 - *Why do we write test cases?*

In my opinion we write test cases because it helps us plan tests.
They help verify the compliance of the software with the requirements.
They also contain helpful instructions for a new tester in a project.
Test cases allow for effective and consistent regression testing.

## Subtask 4 *Writing test cases based on your "own experience"* - ***PICK EAT UP*** - mobile application.

Please find my test ceases on https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing
