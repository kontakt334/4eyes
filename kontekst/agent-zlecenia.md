# Agent do pozyskiwania zleceń

**Status: NIE URUCHOMIONY.** Czekamy na odpowiedzi na pytania startowe (sekcja "Do ustalenia") i wyraźną zgodę.
Do tego czasu nic nie publikujemy i niczego nie wysyłamy.

## Zadanie
Przeglądać Useme, Fiverr, wskazane grupy na Facebooku i inne źródła (dodane później), wyszukiwać zlecenia
pasujące do naszego profilu i przygotowywać rekomendacje do akceptacji.

## Ocena ogłoszeń (0–100)
Kryteria: dopasowanie kompetencji, opłacalność, wiarygodność klienta, kompletność wymagań, termin,
ryzyko problemów/oszustwa. Odrzucamy spam, podejrzane oferty, bardzo niskie budżety i zlecenia spoza naszych kompetencji.
Alert e-mail tylko powyżej progu (domyślnie 75/100).

## Karta oferty (dla każdej ciekawej)
Źródło i link, klient, opis, budżet i termin, ocena z uzasadnieniem, ryzyka, proponowana cena i termin,
gotowa spersonalizowana odpowiedź, lista rzeczy do doprecyzowania.

## Proces akceptacji
1. Bez zgody nic nie wysyłamy.
2. Rekomendacja e-mailem z opcjami: AKCEPTUJ / POPRAW / ODRZUĆ.
3. Po jednoznacznym "AKCEPTUJ": ponowna weryfikacja treści, ceny, terminu i odbiorcy; pokazanie finalnej wersji
   (i ostatnie potwierdzenie, jeśli formularz tworzy zobowiązanie finansowe lub prawne); wysyłka przez właściwą platformę;
   zapis daty, treści i statusu.
4. CAPTCHA, 2FA, ręczne potwierdzenia: zatrzymujemy się i prosimy o wykonanie kroku. Zabezpieczeń nigdy nie obchodzimy.

## Zasady ofert
- Żadnych masowych, identycznych wiadomości; każda odpowiedź odnosi się do konkretnego ogłoszenia.
- Naturalnie, konkretnie, bez przesadnego marketingu.
- Nie wymyślamy doświadczenia, klientów, wyników ani portfolio. Opieramy się wyłącznie na `portfolio/realizacje.md`.
- Nie obiecujemy ceny ani terminu, których wcześniej nie ustaliliśmy.
- Nie kontaktujemy się poza platformą, jeśli regulamin tego zabrania.
- Nie ujawniamy danych poufnych ani danych innych klientów.

## Bezpieczeństwo i regulaminy
- Tylko konta z legalnym dostępem; przestrzegamy regulaminów Useme, Fiverr, Facebooka i grup.
- Bez niedozwolonego scrapingu i spamu; preferujemy API, alerty, integracje.
- Żadnych haseł w notatkach ani wiadomościach.
- Minimalizujemy dane osobowe. Przy wątpliwościach: stop i pytanie.

## Raportowanie
- Tabela (kolumny): data, platforma, link, klient, temat, budżet, wynik, status, data zgłoszenia, odpowiedź klienta, następny krok.
  Plik: `kontekst/zlecenia-tabela.csv` (do założenia po starcie).
- Raz dziennie krótkie podsumowanie: liczba przejrzanych, rekomendowanych, zaakceptowanych i wysłanych,
  odpowiedzi klientów, sprawy wymagające decyzji.

## Do ustalenia (pytania startowe)
1. Zakres usług
2. Technologie i kompetencje
3. Portfolio i prawdziwe referencje
4. Minimalny budżet
5. Model rozliczenia
6. Dostępność i maks. liczba projektów
7. Języki
8. Wykluczone branże i rodzaje zleceń
9. Adres do powiadomień
10. Lista grup i źródeł
11. Częstotliwość monitorowania
12. Próg alertu

Odpowiedzi: _jeszcze brak_
