# Strona statyczna — Gabriela & Patryk

To repozytorium zawiera prostą, statyczną stronę przygotowaną do publikacji na GitHub Pages.

Szczegóły:
- Treść: Polska
- Imiona: Gabriela i Patryk
- Data wydarzenia: 17.07.2026
- Miejsce plików dla Pages: `/docs` (folder `docs` na gałęzi `main`)

Jak opublikować (krótko):
1. Zatwierdź i wypchnij zmiany do zdalnego repozytorium (branch `main`).
2. Otwórz ustawienia repo na GitHub: Settings → Pages.
3. W sekcji "Source" wybierz: branch `main` i folder `/docs`, zapisz.
4. Po chwili strona będzie dostępna pod adresem:

   `https://pkoniu.github.io/gabriela-patryk-2026`

(Konto właściciela repozytorium to `pkoniu`, stąd powyższy adres — jeśli repozytorium należy do innego użytkownika/organizacji, adres będzie inny.)

Podgląd lokalny:

Możesz sprawdzić stronę lokalnie, uruchamiając prosty serwer HTTP w katalogu `docs`:

```bash
# z katalogu repozytorium
cd docs
python3 -m http.server 8000
# otwórz http://localhost:8000 w przeglądarce
```

Dodatki:
- Plik `.nojekyll` w `docs/` wyłącza przetwarzanie Jekyll na GitHub Pages.
- Jeśli chcesz własną domenę, dodaj plik `CNAME` w `docs/` z nazwą domeny.

Jeśli chcesz, mogę dodać formularz RSVP, mapę dojazdu, galerię zdjęć lub automatyczne deployment z GitHub Actions — powiedz, co potrzebujesz.