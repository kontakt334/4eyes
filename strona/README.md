# Strona 4 Eyez

Jeden plik: `index.html` (CSS i JS w środku, bez budowania). Otwierasz w przeglądarce i działa.
Treści (portfolio, o nas, kontakt) bierzemy z `../portfolio/` i `../kontekst/`.

## Stan: szablon pokazowy v1 (7.10.2026)
Układ oparty na wnioskach z `../inspiracje/research-portfolio-inspiracje.md`.
Wszystko w `[nawiasach kwadratowych]` to placeholdery do podmiany.

**Sekcje:** hero (4 kadry), Prace (grid + filtry), Jak pracujemy, Ekipa, Kontakt.
Menu tylko: Prace / Ekipa / Kontakt.

**Pomysł:** „4 Eyez” = cztery kadry. Hero to cztery okna z loopami, które otwierają się jak oczy
(jedyna animacja na starcie). Na kafelkach prac po najechaniu pojawiają się znaczniki kadru kamery.

**Z researchu wzięliśmy:** wideo od pierwszej sekundy, ciemne tło, grid z hover-preview, filtry
Teledyski / Reklamy / Foto, flagowiec (⭐) największy i na górze, credits przy każdej pracy,
kontakt widoczny od razu, proces dla klientów komercyjnych bez cennika.

## Jak podmienić placeholdery
- **Hero:** w każdym `.frame` wstaw `<video autoplay muted loop playsinline src="...">` (loop 3–5 s, bez dźwięku).
- **Kafelek pracy:** dodaj `data-preview="loop.mp4"` (podgląd na hover) i `data-video="klip.mp4"` (pełne wideo w oknie).
  Flagowiec to kafelek z klasą `is-flagship` — zawsze pierwszy.
- **Tytuły:** klucz „Artysta — Utwór” albo „Marka — Kampania”. Dane w `data-title`, `data-label`, `data-year`
  i w tekście kafelka (kredyty w oknie projektu są w `<dialog id="project">`).
- **Kolory i fonty:** zmienne na górze CSS (`:root`). Aktualne wartości są w `../marka/brand.md` jako robocze.
- **Stopka:** usuń zdanie o szablonie pokazowym, gdy treści będą prawdziwe.

## Do zrobienia
- Prawdziwe loopy, tytuły i credity (po uzupełnieniu `../portfolio/realizacje.md`).
- Logo i finalne kolory/fonty (`../marka/brand.md`).
- Ekipa i krótki opis (`../kontekst/o-nas.md`), mail / Instagram / YouTube.
- Sekcja „Jak pracujemy” to szkic — popraw pod realny proces albo wyrzuć.
- Hosting loopów (Vimeo / własne mp4) i domena.
- Wersja na własnych fontach (teraz Google Fonts), jeśli zależy nam na RODO / szybkości.
