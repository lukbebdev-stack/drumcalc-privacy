# Polityka Prywatności aplikacji DrumCalc

Niniejsza polityka prywatności określa zasady gromadzenia, wykorzystywania i przechowywania informacji przez aplikację mobilną **DrumCalc** (zwaną dalej „Aplikacją”), stworzoną przez dewelopera **Siasiek**.

## 1. Jakie dane gromadzimy?

### Dane wprowadzane przez użytkownika
Aplikacja pozwala na tworzenie kalkulacji finansowych. W ramach korzystania z funkcji „Udostępnij” lub „Archiwum w chmurze”, następujące dane są przesyłane do bazy danych Firebase (Cloud Firestore):
*   Nazwy kalkulacji.
*   Imiona/nazwy uczestników.
*   Kwoty wydatków oraz przypisane kategorie.
*   Daty utworzenia wpisów.

### Dane zbierane automatycznie
Podczas korzystania z Aplikacji, usługi stron trzecich mogą zbierać anonimowe informacje techniczne:
*   **Firebase Remote Config:** Służy do sprawdzania dostępności nowych wersji aplikacji.
*   **Google Play Services:** Podstawowe dane o urządzeniu i systemie operacyjnym w celu zapewnienia stabilności działania.

## 2. Cel gromadzenia danych
Dane przesyłane do chmury są gromadzone wyłącznie w celu:
1.  **Udostępniania kalkulacji:** Generowanie unikalnego linku, który pozwala innym użytkownikom (znającym ten link) na pobranie danych.
2.  **Kopii zapasowej:** Umożliwienie użytkownikowi przywrócenia swoich danych po reinstalacji aplikacji.
3.  **Synchronizacji:** Odświeżania danych w udostępnionych kalkulacjach.

## 3. Bezpieczeństwo danych
*   **Firestore:** Dane przechowywane są w chmurze Google Firebase. Dostęp do konkretnej kalkulacji jest możliwy tylko dla osób posiadających unikalny, losowo wygenerowany identyfikator (ID dokumentu).
*   **Szyfrowanie:** Wszystkie dane są przesyłane między Aplikacją a serwerem przy użyciu bezpiecznego protokołu HTTPS.
*   **Anonimowość:** Aplikacja nie wymaga zakładania konta, podawania adresu e-mail ani numeru telefonu. Dane w chmurze nie są powiązane z Twoją tożsamością w świecie rzeczywistym.

## 4. Usługi stron trzecich
Aplikacja korzysta z usług Google, które posiadają własne polityki prywatności:
*   [Google Play Services](https://www.google.com/policies/privacy/)
*   [Firebase Remote Config / Firestore](https://firebase.google.com/support/privacy)

## 5. Prawa użytkownika
Użytkownik ma prawo do:
*   Wglądu w swoje dane (poprzez samą Aplikację).
*   Usunięcia danych – usunięcie kalkulacji lokalnie oraz w chmurze (za pomocą funkcji „Usuń” w menu aplikacji).

## 6. Kontakt
W razie pytań dotyczących niniejszej polityki prywatności, możesz skontaktować się z deweloperem pod adresem: lukbebdev@gmail.com
