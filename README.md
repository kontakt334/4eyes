# 4 Eyez — repozytorium kolektywu

Wspólne źródło prawdy dla kolektywu 4 Eyez (produkcja wideo: teledyski i reklamy, Warszawa).
Tu trzymamy kontekst, zasady pracy, inspiracje i projekty — niezależnie od komputera i narzędzia.

## Struktura

```
4eyez/
├── CLAUDE.md              ← główny kontekst dla Claude (czytany automatycznie przez Claude Code / VS Code)
├── kontekst/
│   ├── o-nas.md           ← kim jesteśmy, ekipa, oferta
│   ├── styl-i-ton.md      ← jak mówimy, jak wyglądamy
│   └── klienci.md         ← z kim pracowaliśmy / z kim chcemy
├── marka/
│   ├── brand.md           ← kolory, fonty, zasady logo
│   └── assets/            ← logo, grafiki (małe pliki)
├── inspiracje/
│   └── README.md          ← linki, moodboardy, referencje
├── portfolio/
│   └── realizacje.md      ← lista prac z linkami
├── projekty/
│   └── _szablon/          ← szablon nowego projektu (brief, treatment, notatki)
└── strona/                ← kod strony internetowej
```

## Jak tego używać

**W aplikacji Claude (Desktop):** stwórz Projekt „4 Eyez”, wklej treść `CLAUDE.md` do instrukcji projektu,
a pliki z `kontekst/`, `marka/` i `portfolio/` wgraj do wiedzy projektu. Po większych zmianach w repo — podmień pliki w projekcie.

**W VS Code / lokalnie:** sklonuj repo (`git clone ...`). Claude Code w VS Code sam wczytuje `CLAUDE.md`
i ma dostęp do całego folderu — nic nie trzeba wgrywać.

**Zasada:** git jest źródłem prawdy. Zmieniasz coś w kontekście → commit → push → reszta robi pull.

## Czego NIE trzymamy w gicie

Footage, rendery, projekty Premiere/DaVinci/AE i inne ciężkie pliki — od tego jest dysk / NAS / chmura.
W repo zostawiamy tylko linki do nich. (Patrz `.gitignore`.)
