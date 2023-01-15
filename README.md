# challenge_portfolio_AgnieszkaDR
# Witam Cię na moim profilu w Githubie :) I hope you enjoy it :) 
## Miłego oglądania. Agnieszka Dolińska-Rakowska
## TASK 1
### Subtask 1.    Ilość uzyskanych punktów z testu to:
### Subtask 3. 
#### 3.1. Dlaczego zdecydowałam się na udział w challenge portfolio? 
#### Cześć, jestem Agnieszka, mama, żonka i być może przyszła testerka oprogramowania. Moim celem jest zmiana obecnej ścieżki zawodowej (jestem inżynierem sanitarnym) na branżę IT. Chciałabym moim portfolio zachęcić potencjalnych pracodawców do jego odwiedzenia oraz zapoznania się z moją osobą, umiejętnościami, celami itd. 
#### 3.2. Dlaczego zdecydowałam się na udział w projekcie? 
#### Projekt pomoże mi stworzyć pierwsze portfolio i usystematyzować zdobytą dotychczas wiedzę teoeretyczną w zakresie testowania manualnego oprogramowania, a w przyszłości zaowocuje kolejnym korkiem - tstami automatycznymi. 
#### 3.3. Co mną kierowało? Jaki jest mój cel? 
#### Jestem osobą ciekawą świata, gotową na nowe wyzwania zawodowe, posiadam długoletnie doświadczenie zawodowe oraz wysoko rozwinite zdolnościinterpersonalne ("gdzie chłop nie może, tam mnie pośle) ;)
#### 3.4. Jakie są moje oczekiwania wobec projektu? 
### ... kolejny etap w zdobyciu wisienki na torcie - pracy w branży IT :)
### Subtask 4. Testy eksploracyjne – poznaj aplikację https://scouts-test.futbolkolektyw.pl/pl :
#### 4.1. Na czym polega aplikacja? Do czego służy? Aplikacja uożliwia przeglądanie wskaźników, umiejętności i pozycje zawodników, po zalogowaniu się do profilu.
#### 4.2. Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może bym coś zmieniła? 
#### Funkcjonalności w aplikacji: dodawanie/edycja informacji na temat gracza, dodawanie / edycja meczu dla gracza, zmiana języka strony (do wybory dwa języki: angielski, polski), logowanie do profilu głównego aplikacji / strony za pomoca hasła i loginu; możliwośc generowanie wydruku i danych ze strony; filtrowanie informacji na stronie / wyszukiwarka; umożliwienie kontaktu z zespołem Dev. 
#### 4.3. Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?
#### 4.4. Czy aplikacja jest intuicyjna? 
#### 4.5. Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? 
#### Zauważone błędy:
#### 1. Brak możliwości zalogowania poprzez przeglądarkę Chrome - żaden z podanych użytkowników i hasła "nie wchodzi". Po wpisaniu i próbie akceptacji, w celu zalogowania (na stronie głównej do logowania - Scouts panel: ) - pojawia się komunikat: niepraawidłowe hasło lub użytkownik" w języku angielskim: "Identifier or password invalid". 
#### 2. W Scouts panel" - Main page, po wybraniu zakładki "Players" i profilu konkretnego zawodnika, przy próbie edytowania danych wskazanych w profilu gracza - pojawia się komunikat: "Cannot save player" po wciśnięciu przycisku "Submit".
#### 3. W Scouts panel" - Main page, po wybraniu zakładki "Players" i profilu konkretnego zawodnika, przy próbie edytowania danych wskazanych w profilu gracza - pola wyboru i do wpisania przyjmują dwolone, niepoprawne dane, np. height - przyjmuje ujemne dane liczbowe; pola, które powinny przyjmowac dane im przeznaczone, tj.np. pola do pwisania danych cyfrowo-liczbowych przyjmują dane literowe, znaki specjalne. 
#### 4. W Scouts panel" - Main page, po wybraniu zakładki "Players" i profilu konkretnego zawodnika, przy próbie edytowania danych wskazanych w profilu gracza po wciśnięciu przycisku "Clear", dane pozostają bez zmian,a powinny zostac usunięte z profilu gracza. 
#### 5. W Main page, po wybraniu w prawym górnym menu "Download CSV" (oznaczenie: chmurka ze strzałką w dół, obok symbolu drukarki, po lewej jego stronie), generowany jest plik .xls, gdzie po jego otwarciu, widoczne są zapisane nieuszeregowane dane: 
Christiano,"Ronaldo ","1000-03-01","ktr7ir86fyufujh","No. 2","2.5555555555555554","[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object 
aaa,"bbb","1000-03-01","lewa obrona","Odra Opole","3","[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object]","[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object]"
!@#$%^1234,"d","0001-03-12","najstarsi gĂłrole ni wiedzo hej","Fajny","1.25","[object Object],[object Object],[object Object],[object Object]","[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object],[object Object]"

#### 6. Zalecenia z mojej strony / usprawnienia działania strony:
#### 6.1. Brakuje (wg mojej oceny) usorawnień na stronie, polegających na możliwości wyboru informacji wprowadzanych np. do prodili graczy, edycji / wprowadzania meczu w profilach graczy (zastosowałabym listy rozwijalne z możliwością wyboru np. w przypadku: ....)
#### 6.2. Zastosowałabym wyszczególnienie jednostki czasu w przypadku edycji / wprowadzania danych do zakładki "Edycja meczu dla gracza" (Gracz -> wybór gracza - > "Mecze" -> Dodawanie meczu dla gracza ... lub Edycja meczu dla gracza ... - w polu: Czas gry - brakuje jednostki czasu, jaką należy wybrać (minuty, godziny, sekundy ?).
#### 6.3. Po wybraniu w Scouts Panel / profilu głównym: zakładki Dev Team Contakt - pojawia się przekierowanie do Slacka - powinien zostać stworzony formulacz kontaktowy lub pozostawiony e-mail i dane kontaktowe, celem umożliwienie kontaktu z ekipą (przekierownaie do Slacka bez posiadania hasła i loginu dop grupy w nim, nie umożliwia skutecznego kontaktu).
