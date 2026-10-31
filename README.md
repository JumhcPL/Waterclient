# WATERCLIENT — podgląd sklepu

Strona statyczna przygotowana do GitHub Pages. Otwórz index.html.

Metody na ekranie: karta, BLIK, paysafecard. Płatności NIE są podłączone. Przycisk zakupu jest celowo nieaktywny, a widok licencji jest wyraźnie oznaczoną demonstracją.

Klucze demonstracyjne:
Nie są to klucze aktywujące WATERCLIENT. Nie umieszczaj rzeczywistych licencji ani sekretów operatora w publicznym repozytorium.

Do wdrożenia sprzedaży: ustal cenę i ważność, skonfiguruj konto operatora (np. Przelewy24) oraz serwer z bazą zamówień i licencji. Serwer rejestruje transakcję, weryfikuje powiadomienie operatora i kwotę, a następnie przydziela jeden klucz atomowo. Sam powrót z płatności nie potwierdza zakupu. Dostęp do klucza wymaga prywatnego tokenu zamówienia lub logowania. Program WATERCLIENT musi osobno obsługiwać sprawdzanie licencji.

Cena: 30 zł. Okres ważności: 30 dni. Dodano oryginalne archiwum Java jako downloads/WATERCLIENT_JAVA.zip. Analiza kodu bajtowego wykazała jeden klucz zaszyty w metodzie logowania, bez sprawdzania zakupów na serwerze. Klucz można odzyskać z pliku JAR; przed sprzedażą należy zmienić mechanizm licencji. Nie dodano rzeczywistych kluczy do publicznego HTML. Nowe klucze demonstracyjne nie są obsługiwane przez obecną aplikację.


