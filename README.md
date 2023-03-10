![zp2](https://user-images.githubusercontent.com/102677799/212494378-871c1a22-b5c6-45dd-806f-c89817d53530.jpg)

[ENGLISH VERSION](#english-version)


# TASK 1 
## Subtask 1

9 	:blush:

## Subtask 3
Cześć! Nazywam się Zofia Dańko i postanowiłam wziąć udział w **Dare IT challenge** aby z pomocą mentorek zdobyć doświadczenie oraz praktyczne umiejętnośći przy testowaniu aplikacji webowych i mobilnych. Potajemnie liczę też na dobrą zabawę w trakcie nauki, ciekawe wyzwania oraz sieć nowych kontaków :sweat_smile: 

## Subtask 4

Aplikacja [Futbol Kolektyw](https://scouts-test.futbolkolektyw.pl/pl) służy do tworzenia i edytowania  raportów na temat zawodników piłki nożnej i rozegranych przez nich meczy.


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

---


# TASK 2

## Subtask 1 - *Pisanie przypadków testowych na podstawie User Story.*

Znajdziesz moje test case'y tutaj  [Test Cases](https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing)


## Subtask 2 - *Pisanie przypadków testowych na podstawie “własnych doświadczeń"*.

Znajdziesz moje test case'y tutaj  [Test Cases](https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing)

## Subtask 3 - *Po co piszemy test case’y?*

Moim zdaniem przypadki testowe piszemy, ponieważ pomaga nam to planować testy.
Łatwiej jest z ich pomocą zweryfikować zgodność oprogramowania z wymaganiami. Są pewnego rodzaju instrukcją dla testera, pomocną zwłaszcza dla nowych testerów w projekcie. Umożliwiają również skuteczne i spójne testowanie regresji.

## Subtask 4 *Pisanie przypadków testowych na podstawie “własnych doświadczeń"*. - **Pick Eat Up** - aplikacja mobilna.

Znajdziesz moje test case'y tutaj  [Test Cases](https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing)

---

# TASK 3

## Subtask 2 - *Testowanie według planów testów i raportowanie błędów.*

:point_right: [Bug Reports](https://drive.google.com/drive/folders/1ZBefbKlAniqDTgZPBl3wGLYppKZZWG9B?usp=sharing)


## Subtask 3 - *Raport z wykonanych testów.*

:point_right: [Test Report](https://drive.google.com/drive/folders/1ZBefbKlAniqDTgZPBl3wGLYppKZZWG9B?usp=sharing)

---


# TASK 4

## Subtask 2 - *Testowanie eksploracyjne i raportowanie błędów - aplikacja mobilna OLX*

:point_right: [Bug Reports](https://drive.google.com/drive/folders/1i8yyyPkfFo5nn885NUhzRrJreoPbNUPf?usp=sharing)

## Subtask 3

Aplikacja OLX służy do dodawania oraz szukania ogłoszeń na interesujący nas temat. Ogłoszenia te dotyczą m.in. usług, pracy, kupna, sprzedaży i wynajmu.  Osobiście uważam, że aplikacja ta jest bardzo przyjazna i intuicyjna dla użytkowników końcowych którymi są zwykli ludzie. Jest też niezawodna i nie wzbudza w użytkownikach poczucia frustracji.
Gdybym mogła dodałabym do niej przycisk "Wyczyść wszystkie filtry" oraz opcję zmiany języka interfejsu na angielski i ukraiński. 

Z mojego punktu widzenia główną różnicą pomiędzy testowaniem aplikacji mobilnej i webowej jest możliwość wystąpienia różnych błędów na różnych urządzeniach. Należy pamiętać, że telefony komórkowe, a w związku z tym aplikacje wystawione są na działania wielu czynników takich jak ładowanie, słaby zasięg internetu, tryb oszczędzania baterii czy połączenia wychodzące i przychodzące.  W każdej z tych sytuacji aplikacja mobilna może zachować się inaczej.

## Subtask 4 - *Zgłaszanie błędów w programie Jira - aplikacja SwipeTo*

![obraz](https://user-images.githubusercontent.com/102677799/217333186-0003e4aa-fd8c-4685-9309-f14841116f3a.png)



![DPP-3](https://user-images.githubusercontent.com/102677799/217334414-1e87ee74-b2f3-4cad-b948-f16edb2f44f6.png)


![DPP-4](https://user-images.githubusercontent.com/102677799/217334470-722b151a-0c8a-46fe-b53d-e707fd6fba49.png)




![DPP-5](https://user-images.githubusercontent.com/102677799/217335873-b9efcadf-ef1e-4f5b-bc88-a36bc5e5f18b.png)

---

# TASK 5


## Subtask 3


1. Wyświetl tabelę "actors" w kolejności alfabetycznej sortując po kolumnie surname.


**SELECT * FROM actors ORDER BY surname;**


![1](https://user-images.githubusercontent.com/102677799/218267967-e87bb1cf-8cbc-4404-849d-c4f035349fa1.png)

2. Wyświetl film, który powstał w 2019 roku.

**SELECT * FROM movies WHERE year_of_production= 2019;**

![2](https://user-images.githubusercontent.com/102677799/218268185-0c965922-56b3-4745-9d6a-42ffbf5c11d5.png)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

**SELECT * FROM movies WHERE year_of_production BETWEEN 1900 and 1999;**


![between](https://user-images.githubusercontent.com/102677799/218268295-bd11087b-b22d-4afb-8dcc-d8c5a12a375f.png)

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.

**SELECT title, price FROM movies WHERE price < 7;**


![4](https://user-images.githubusercontent.com/102677799/218268408-62e49918-59cb-47ac-a958-3782299cf512.png)

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

**SELECT * FROM actors WHERE actor_id>= 4 and actor_id<= 7;**

![4-7](https://user-images.githubusercontent.com/102677799/218268529-35984004-9a20-4a76-82f7-746acb8dd434.png)

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

**SELECT * FROM `customers` WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6;**


![6](https://user-images.githubusercontent.com/102677799/218268619-3e32e52e-d8ca-4b89-8b79-a172aa49d388.png)

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

**SELECT * FROM customers WHERE customer_id IN (1,2,5);**


![7](https://user-images.githubusercontent.com/102677799/218268708-806f50cb-f852-4a4b-864d-a16585547466.png)

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.


**SELECT * FROM actors WHERE name Like 'An%';**


![8](https://user-images.githubusercontent.com/102677799/218268978-8153e1ab-8e76-434b-b76b-b119985bbc51.png)

9. Wyświetl dane klienta, który nie ma podanego adresu email.

**SELECT * FROM customers WHERE email IS null;**

![9](https://user-images.githubusercontent.com/102677799/218269030-56880640-24c3-49e5-acae-0243e542e908.png)

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.


**SELECT * FROM movies WHERE price > 9 and movie_id Between 2 and 8;**


![10](https://user-images.githubusercontent.com/102677799/218269108-8ed27fe5-b153-487b-aa8e-c7ca452ef573.png)

---

# TASK 6


## Subtask 1

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈
![11(0)](https://user-images.githubusercontent.com/102677799/220428469-274b6c42-8f87-467c-ba0e-ccd635f3626a.png)

![11v2](https://user-images.githubusercontent.com/102677799/220431225-dbed72c9-bd52-4f39-bdbc-a87bc3a57742.png)



12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.


![12ost](https://user-images.githubusercontent.com/102677799/220609401-93a9be82-1585-4761-8987-e31af4f9baac.png)

![12 1](https://user-images.githubusercontent.com/102677799/220609422-e78492d4-0f2e-4283-8063-d4edc5161e0c.png)


13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com


![13](https://user-images.githubusercontent.com/102677799/220428876-ac679e5f-3915-4b1d-8cca-337cbf9fbf1e.png)


![13(2)](https://user-images.githubusercontent.com/102677799/220431761-1ea33c82-d943-4db5-b4a1-cb4230f6060c.png)

14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).


![14](https://user-images.githubusercontent.com/102677799/220428950-d82258ed-d0c4-4672-b41e-c02b533fd1ed.png)

![14(2)](https://user-images.githubusercontent.com/102677799/220428975-27a67859-0fae-48db-916e-4705849f3f84.png)

15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag


 **ALTER TABLE customers ADD pseudonym varchar(3)**
 
![15](https://user-images.githubusercontent.com/102677799/220430151-5c9f519a-e581-47eb-885b-eb3f97c89969.png)

![15(2)](https://user-images.githubusercontent.com/102677799/220624002-e3edfe7e-a102-4855-9c3b-8dc0fe76597b.png)


16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.


![16](https://user-images.githubusercontent.com/102677799/220430256-0aae29c8-69a9-4ddb-8abe-17ad2a923b6e.png)

![16(2)](https://user-images.githubusercontent.com/102677799/220430282-969a770b-1f2e-4fb5-b924-0f6e4c93d9fa.png)

17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)


![17](https://user-images.githubusercontent.com/102677799/220430361-f99272de-32a0-4fdf-ad05-a045fa1d8a6e.png)

![17(2)](https://user-images.githubusercontent.com/102677799/220430392-963ba839-b867-41ea-9def-21d6423dff94.png)

18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).



![18](https://user-images.githubusercontent.com/102677799/220430452-a42163d5-3133-4623-b59c-24e2d6cd109e.png)

19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał


![19(2)](https://user-images.githubusercontent.com/102677799/220430497-d1fadedb-fe65-4c60-b1ee-9457e7370412.png)

![19](https://user-images.githubusercontent.com/102677799/220430477-7ee58b17-6ff2-4429-afc7-f41ab94af04c.png)

20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa


![20](https://user-images.githubusercontent.com/102677799/220430526-3725566e-ee8c-4ccd-b57f-3c419f8f1be0.png)


![20(2)](https://user-images.githubusercontent.com/102677799/220430552-23c9f722-8e7f-4bd6-92ae-f7d42ecb9b68.png)

## Subtask 2

![subtask2](https://user-images.githubusercontent.com/102677799/220448859-98136365-b7d2-439c-943e-fbd0a4dca000.png)


## Subtask 3
Zapraszam do zapoznania się z moim portfolio :blush:
[PORTFOLIO](https://github.com/ZofiaD/PORTFOLIO.git)


---





#### ENGLISH VERSION

# TASK 1 
## Subtask 1

9 	:blush:

## Subtask 3

Hi, my name is Zofia Dańko. I decided to participate in **Dare IT challenge** to gain experience and practical skills during web and mobile applications testing.
I expect interesting challenges, fun while learning, professional networking and career development.

## Subtask 4

The web application [Futbol Kolektyw](https://scouts-test.futbolkolektyw.pl/pl) is used to create and edit reports about football players and matches they played.

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
  
  ---

# TASK 2

## Subtask 1 - *Writing test cases based on User Story.*

Please find my test cases on [Test cases](https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing)

## Subtask 2 - *Writing test cases based on your "own experience"*

Please find my test cases on [Test cases](https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing)

## Subtask 3 - *Why do we write test cases?*

In my opinion we write test cases because it helps us plan tests.
They help verify the compliance of the software with the requirements.
They also contain helpful instructions for a new tester in a project.
Test cases allow for effective and consistent regression testing.

## Subtask 4 *Writing test cases based on your "own experience"* - ***PICK EAT UP*** - mobile application.

Please find my test cases on [Test cases](https://drive.google.com/drive/folders/1OZHrDLQ9Q7OqTHEhCYCJTAEUBQSixOHD?usp=sharing)

---

# TASK 3

## Subtask 2 - *Testing according to test plan and bug report.*

:point_right: [Bug Reports](https://drive.google.com/drive/folders/1ZBefbKlAniqDTgZPBl3wGLYppKZZWG9B?usp=sharing)


## Subtask 3 - *Test report.*

:point_right: [Test Report](https://drive.google.com/drive/folders/1ZBefbKlAniqDTgZPBl3wGLYppKZZWG9B?usp=sharing)

---

# TASK 4

## Subtask 2 - *Exploratory testing and bug report - OLX mobile app.*


:point_right: [Bug Reports](https://drive.google.com/drive/folders/1i8yyyPkfFo5nn885NUhzRrJreoPbNUPf?usp=sharing)

## Subtask 3

Users use the OLX application to search and add announcements concerning e.g. job search, services, sales, purchases and rentals. In my opinion, the application is user friendly and intuitive. Made for ordinary people. Customers don't feel frustration while using the application. It's really reliable. If I could add new features I would add a „Clear all filters” button and a way to switch interface language to English and Ukrainian. 

From my point of view the main difference between testing the mobile app and the web app is the possibility of different bugs occurring on different devices. Testers should be aware that mobile phones are exposed to factors such as internet connection issues or incoming/outgoing calls. The application may also behave differently in power saving mode or during charging. 



## Subtask 4 - *Bug report in Jira - SwipeTo application.*

![obraz](https://user-images.githubusercontent.com/102677799/217333186-0003e4aa-fd8c-4685-9309-f14841116f3a.png)



![DPP-3](https://user-images.githubusercontent.com/102677799/217334414-1e87ee74-b2f3-4cad-b948-f16edb2f44f6.png)


![DPP-4](https://user-images.githubusercontent.com/102677799/217334470-722b151a-0c8a-46fe-b53d-e707fd6fba49.png)



![DPP-5](https://user-images.githubusercontent.com/102677799/217335821-f0444c00-cf32-49cd-98c4-0e747c436e5e.png)

---

# TASK 5


## Subtask 3


1. Display the "actors" table in alphabetical order sorting by surname column.


**SELECT * FROM actors ORDER BY surname;**


![1](https://user-images.githubusercontent.com/102677799/218267967-e87bb1cf-8cbc-4404-849d-c4f035349fa1.png)



2. Display the movie which was made in 2019. 

**SELECT * FROM movies WHERE year_of_production= 2019;**

![2](https://user-images.githubusercontent.com/102677799/218268185-0c965922-56b3-4745-9d6a-42ffbf5c11d5.png)



3. Display all movies made between 1900 and 1999. 

**SELECT * FROM movies WHERE year_of_production BETWEEN 1900 and 1999;**


![between](https://user-images.githubusercontent.com/102677799/218268295-bd11087b-b22d-4afb-8dcc-d8c5a12a375f.png)



4. Display only titles and prices of movies that cost less than 7$.  

**SELECT title, price FROM movies WHERE price < 7;**


![4](https://user-images.githubusercontent.com/102677799/218268408-62e49918-59cb-47ac-a958-3782299cf512.png)



5. Use the logical "AND" operator to display actors with actor_id between 4-7 (4 and 7 should be displayed). Do not use "BETWEEN" operator.

**SELECT * FROM actors WHERE actor_id>= 4 and actor_id<= 7;**

![4-7](https://user-images.githubusercontent.com/102677799/218268529-35984004-9a20-4a76-82f7-746acb8dd434.png)



6. Display customers with id 2,4,6, use logical condition for this.

**SELECT * FROM  customers WHERE mod(customer_id,2) = 0;**


![6](https://user-images.githubusercontent.com/102677799/218268619-3e32e52e-d8ca-4b89-8b79-a172aa49d388.png)



7. Display customers with id 1,3,5, use "IN" operator.

**SELECT * FROM customers WHERE customer_id IN (1,2,5);**


![7](https://user-images.githubusercontent.com/102677799/218268708-806f50cb-f852-4a4b-864d-a16585547466.png)



8. Display the data of all persons from the 'actors' table whose name starts with 'An'. 


**SELECT * FROM actors WHERE name Like 'An%';**


![8](https://user-images.githubusercontent.com/102677799/218268978-8153e1ab-8e76-434b-b76b-b119985bbc51.png)



9. Display data of a customer who does not have an email address provided.


**SELECT * FROM customers WHERE email IS null;**

![9](https://user-images.githubusercontent.com/102677799/218269030-56880640-24c3-49e5-acae-0243e542e908.png)



10. Display all movies with price over 9$ and with movie_id between 2 and 8. 


**SELECT * FROM movies WHERE price > 9 and movie_id Between 2 and 8;**


![10](https://user-images.githubusercontent.com/102677799/218269108-8ed27fe5-b153-487b-aa8e-c7ca452ef573.png)

---

# TASK 6


## Subtask 1

11.
![11(0)](https://user-images.githubusercontent.com/102677799/220428469-274b6c42-8f87-467c-ba0e-ccd635f3626a.png)

![11v2](https://user-images.githubusercontent.com/102677799/220431225-dbed72c9-bd52-4f39-bdbc-a87bc3a57742.png)



12.
![12ost](https://user-images.githubusercontent.com/102677799/220609401-93a9be82-1585-4761-8987-e31af4f9baac.png)

![12 1](https://user-images.githubusercontent.com/102677799/220609422-e78492d4-0f2e-4283-8063-d4edc5161e0c.png)


13.
![13](https://user-images.githubusercontent.com/102677799/220428876-ac679e5f-3915-4b1d-8cca-337cbf9fbf1e.png)


![13(2)](https://user-images.githubusercontent.com/102677799/220431761-1ea33c82-d943-4db5-b4a1-cb4230f6060c.png)

14.
![14](https://user-images.githubusercontent.com/102677799/220428950-d82258ed-d0c4-4672-b41e-c02b533fd1ed.png)

![14(2)](https://user-images.githubusercontent.com/102677799/220428975-27a67859-0fae-48db-916e-4705849f3f84.png)

15.
 **ALTER TABLE customers ADD pseudonym varchar(3)**
 
![15](https://user-images.githubusercontent.com/102677799/220430151-5c9f519a-e581-47eb-885b-eb3f97c89969.png)

![15(2)](https://user-images.githubusercontent.com/102677799/220624002-e3edfe7e-a102-4855-9c3b-8dc0fe76597b.png)


16.

![16](https://user-images.githubusercontent.com/102677799/220430256-0aae29c8-69a9-4ddb-8abe-17ad2a923b6e.png)

![16(2)](https://user-images.githubusercontent.com/102677799/220430282-969a770b-1f2e-4fb5-b924-0f6e4c93d9fa.png)

17.
![17](https://user-images.githubusercontent.com/102677799/220430361-f99272de-32a0-4fdf-ad05-a045fa1d8a6e.png)

![17(2)](https://user-images.githubusercontent.com/102677799/220430392-963ba839-b867-41ea-9def-21d6423dff94.png)

18.

![18](https://user-images.githubusercontent.com/102677799/220430452-a42163d5-3133-4623-b59c-24e2d6cd109e.png)

19.

![19(2)](https://user-images.githubusercontent.com/102677799/220430497-d1fadedb-fe65-4c60-b1ee-9457e7370412.png)

![19](https://user-images.githubusercontent.com/102677799/220430477-7ee58b17-6ff2-4429-afc7-f41ab94af04c.png)

20.
![20](https://user-images.githubusercontent.com/102677799/220430526-3725566e-ee8c-4ccd-b57f-3c419f8f1be0.png)


![20(2)](https://user-images.githubusercontent.com/102677799/220430552-23c9f722-8e7f-4bd6-92ae-f7d42ecb9b68.png)

## Subtask 2

![subtask2](https://user-images.githubusercontent.com/102677799/220448859-98136365-b7d2-439c-943e-fbd0a4dca000.png)

## Subtask 3

Please find my portfolio on 
[PORTFOLIO](https://github.com/ZofiaD/PORTFOLIO.git)

