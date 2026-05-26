# Panel szkolenia AI

Panel dla osoby prowadzącej szkolenie „Nowe kompetencje cyfrowe w praktyce - praktyczne wykorzystanie AI”.

## Zawartość

- `index.html` - główna strona panelu,
- `app.js` - logika ćwiczeń, narzędzi i generatora QR,
- `assets/logo-wup.jpeg` - logo WUP,
- `assets/icon.svg` - ikona aplikacji,
- `prompts/` - osobne strony z pełnymi promptami,
- `manifest.json` i `service-worker.js` - podstawowe pliki PWA.

## Publikacja na GitHub Pages

1. Utwórz nowe repozytorium na GitHubie.
2. Wgraj całą zawartość folderu z paczki.
3. Wejdź w `Settings` → `Pages`.
4. Wybierz branch `main` i folder `/root`.
5. Zapisz ustawienia.
6. Po chwili GitHub pokaże link do strony.

## Uwaga

Generator QR korzysta z zewnętrznego API do tworzenia obrazu kodu QR, dlatego wymaga internetu.
Przycisk „Generator certyfikatów” ma link tymczasowy `#` i wymaga podmiany na właściwy adres.
