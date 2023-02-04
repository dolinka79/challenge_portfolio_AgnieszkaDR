# challenge_portfolio_AgnieszkaDR
# Witam Cię na moim profilu w Githubie - Repozytorium DARE IT Challenge. I hope you enjoy it ! 
# Miłego oglądania. Agnieszka Dolińska-Rakowska
## TASK 1
### Subtask 1.    Ilość uzyskanych punktów z testu to: 9/10 ! Hurra !
### Subtask 2. Dodaj nowe repozytorium do GitHub - DODANE !!! Właśnie je oglądasz ...
### Subtask 3. 
#### 3.1. Dlaczego zdecydowałam się na udział w challenge portfolio? 
#### Cześć, jestem Agnieszka, mama, żonka i być może przyszła testerka oprogramowania. Moim celem jest zmiana obecnej ścieżki zawodowej (jestem inżynierem sanitarnym) na branżę IT. Chciałabym moim portfolio zachęcić potencjalnych pracodawców do jego odwiedzenia oraz zapoznania się z moją osobą, umiejętnościami, celami itd. 
#### 3.2. Dlaczego zdecydowałam się na udział w projekcie? 
#### Projekt pomoże mi stworzyć pierwsze portfolio i usystematyzować zdobytą dotychczas wiedzę teoeretyczną w zakresie testowania manualnego oprogramowania, a w przyszłości zaowocuje kolejnym krokiem - testami automatycznymi. 
#### 3.3. Co mną kierowało? Jaki jest mój cel? 
#### Jestem osobą ciekawą świata, gotową na nowe wyzwania zawodowe, posiadam długoletnie doświadczenie zawodowe oraz wysoko rozwinięte zdolności interpersonalne (jak to mawiają: "gdzie chłop nie może, tam mnie pośle").
#### 3.4. Jakie są moje oczekiwania wobec projektu? 
#### ... kolejny etap w zdobyciu wisienki na torcie -> pracy w branży IT.
### Subtask 4. Testy eksploracyjne – poznaj aplikację https://scouts-test.futbolkolektyw.pl/pl :
#### 4.1. Na czym polega aplikacja? Do czego służy? 
#### Aplikacja umożliwia przeglądanie wskaźników, umiejętności i pozycji zawodników, generowaniu raportów, po zalogowaniu się do profilu.
#### 4.2. Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może bym coś zmieniła? 
#### Funkcjonalności w aplikacji: dodawanie/edycja informacji na temat gracza, dodawanie / edycja meczu dla gracza, zmiana języka strony (do wybory dwa języki: angielski, polski), logowanie do profilu głównego aplikacji / strony za pomoca hasła i loginu; możliwość generowania wydruku i danych ze strony, tworzenie rapotów; filtrowanie informacji na stronie / wyszukiwarka; umożliwienie kontaktu z zespołem Dev. 
#### 4.3. Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie? 
#### Interfejs strony nie przypadł mi do gustu; logo strony jest mało czytelne, umieszczone, według mojej oceny, w nieprawidłowym miejscu. Brakuje profesjonalnej edycji strony.  
#### 4.4. Czy aplikacja jest intuicyjna? 
#### Tak, wg mnie aplikacja jest intuicyjna, chociaż poprawiłabym ją, z zastosowaniem podlist. 
#### 4.5. Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? 
#### Zauważone przeze mnie błędy:
#### 1. Brak możliwości zalogowania poprzez przeglądarkę Chrome - żaden z podanych użytkowników i hasła "nie wchodzi". Po wpisaniu i próbie akceptacji, w celu zalogowania (na stronie głównej do logowania - Scouts panel ) - pojawia się komunikat: "niepraawidłowe hasło lub użytkownik" w języku angielskim: "Identifier or password invalid". 
#### 2. W "Scouts panel" - Main page, po wybraniu zakładki "Players" i profilu konkretnego zawodnika, przy próbie edytowania danych wskazanych w profilu gracza - pojawia się komunikat: "Cannot save player" po wciśnięciu przycisku "Submit".
#### 3. W "Scouts panel" - Main page, po wybraniu zakładki "Players" i profilu konkretnego zawodnika, przy próbie edytowania danych wskazanych w profilu gracza - pola wyboru i do wpisania przyjmują dwolone, niepoprawne dane, np. height - przyjmuje ujemne dane liczbowe; pola, które powinny przyjmowac dane im przeznaczone, tj.np. pola do wpisania danych cyfrowo-liczbowych przyjmują dane literowe, znaki specjalne etc.
#### 4. W "Scouts panel" - Main page, po wybraniu zakładki "Players" i profilu konkretnego zawodnika, przy próbie edytowania danych wskazanych w profilu gracza po wciśnięciu przycisku "Clear", dane pozostają bez zmian, a powinny zostać usunięte z tego profilu. 
#### 5. W Main page, po wybraniu w prawym górnym menu "Download CSV" (oznaczenie: chmurka ze strzałką w dół, obok symbolu drukarki, po lewej jego stronie), generowany jest plik .xls, gdzie po jego otwarciu, widoczne są zapisane nieuszeregowane dane. 
#### 6. Będąc na stronie głównej - po wybraniu "Gracze" (przy wybranym języku polskim do obsługi strony) - opcje w prawym górnym rogu w pasku po najechaniu na nie kursorem myszy ich opisy są wyświetlane w języku angielskim, pomimo, iż wybrany został język polski do obsługi strony. 
#### 7. Będąc na stronie głównej - po wybraniu "Gracze" lub pod graczami - "Mecze" (przy wybranym języku polskim strony) - opcje edycji - akceptacji edycji lub wprowadzonych danych: jako "Submit" / "Clear" (przyciski edycji) są opisane w języku angielskim, pomimo, iż wybrany został język polski do obsługi strony. 
### 8. Zalecenia z mojej strony / moje propozycje usprawnienia działania strony:
#### 8.1. Brakuje (wg mojej oceny) usprawnień na stronie, polegających na możliwości wyboru informacji wprowadzanych np. do profili graczy, edycji / wprowadzania meczu w profilach graczy (zastosowałabym listy rozwijalne z możliwością wyboru)
#### 8.2. Zastosowałabym wyszczególnienie jednostki czasu w przypadku edycji / wprowadzania danych do zakładki "Edycja meczu dla gracza" (Gracz -> wybór gracza - > "Mecze" -> w oknie: "Dodawanie meczu dla gracza ..." lub "Edycja meczu dla gracza ..." - w polu: "Czas gry" - brakuje jednostki czasu, jaką należy wybrać (minuty, godziny, sekundy ?).
#### 8.3. Po wybraniu w Scouts Panel / profilu głównym: zakładki Dev Team Contakt - pojawia się przekierowanie do Slacka - powinien zostać stworzony formulacz kontaktowy lub pozostawiony e-mail i dane kontaktowe, celem umożliwienia kontaktu z zespołem (przekierownaie do Slacka bez posiadania hasła i loginu do grupy w nim, uniemożliwia kontakt).
### Subtask 5. Jira – DLA CHĘTNYCH - zadanie wykonane - działamy już w grupie !
## Task 2. Przypadki testowe
### Subtask 3. Dlaczego piszemy przypadki testowe? 
#### Test casy są pisane w celu uszczegółowienia scenariuszy wysokiego poziomu i zebrania tych informacji w jednym miejscu. Ponadto dzięki przypadkom testowym możliwe 
### https://drive.google.com/drive/folders/1pqQ-1TuMhR0din42cYWBFgTMZBYOqDQV?usp=sharing
# Task 3. Raportowanie błędów
### https://drive.google.com/drive/folders/1HbXGeI_B_8EhXLirP0Xdfd7-24dX7o0x?usp=sharing
# Task 4. Testowanie aplikacji mobilnych
## Subtask 1 - Utworzenie formatki do zgłaszania błędów systemu 
### https://drive.google.com/drive/folders/1h1SSTyLwgF2zBfc5SpQN31eXqX3zx7-0?usp=sharing
## Subtask 2 - Testowanie eksploracyjne i raportowanie błędów  
### https://drive.google.com/drive/folders/1h1SSTyLwgF2zBfc5SpQN31eXqX3zx7-0?usp=sharing 
# Subtask 3 - Do czego służy aplikacja mobilna olx.pl ?
## Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?
### Aplikacja ta stanowi portal ogłoszeniowy, służy do zamieszczania ogłoszeń przez sprzedających i kupujących, wyszukiwanie ogłoszeń, zakup towarów poprzez aplikację, płatności za towary dzięki jej funkcjom, kontakt pomiędzy klientami. 
## Kto ma być użytkownikiem końcowym aplikacji?
### Uzytkownikiem końcowym aplikacji są firmy lub osoby prywatne chcące dokonac sprzedaży, zakupu towarów poprzez aplikację. 
## Czy według Ciebie aplikacja jest user friendly?
### TAK, jest user friendly. Tak, według mojej oceny aplikacja jest bardzo przyjazna dla użytkownika, intuicyjna. 
## Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? 
### Usprawniłabym działania aplikacji poprzez eliminajcę błędów, które zamieściłam w portfolio. 
## Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej a natywnej?
### Wygodniej jest według mojej oceny pracować z użyciem aplikacji mobilnej, gdyż użycie jej za pomocą smartfona może odbywac się w każdym miejscu, o dowolnej porze. Może być to jednak, z drugiej strony, utrudnieniem dla osób starszych, które często nie potrafią sprawnie obłużyć smartfona. 
