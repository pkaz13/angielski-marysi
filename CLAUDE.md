# Angielski Marysi

Materiały wspierające naukę angielskiego Marysi (dziewczyny Piotra), która uczy się z Duolingo. Duolingo jest głównym narzędziem, materiały to tylko wsparcie.

## Przed pracą przeczytaj

- `PROFIL.md`: co Marysia już zna, fakty do przykładów, zasady prywatności. Plik jest w `.gitignore` (tylko lokalnie). Nie commitować.
- `GLOSSARY.md`: słownictwo projektu (np. „operator (czasownik posiłkowy)”)
- `docs/adr/`: decyzje (np. materiały nie wyprzedzają kursu Duolingo)

## Zasady materiałów

- Reguły po polsku, przykłady po angielsku z polskim tłumaczeniem.
- Przykłady z życia Marysi (z `PROFIL.md`), nie ogólniki.
- Sekcja o konstrukcji gramatycznej zawsze w tej kolejności: kiedy używać (3 przykłady na zastosowanie) → słowa-sygnały → budowa (tabela odmiany przez wszystkie osoby; twierdzenie, przeczenie, pytanie; formy pełne i skrócone) → krótkie odpowiedzi → pułapki.
- Kolory (zawsze z pogrubieniem, żeby działały w druku czarno-białym): operator `.op` niebieski, końcówki `-s/-ing` `.end` czerwone, słowa-sygnały `.sig` zielone.
- Bez ćwiczeń w ściągach.

## Technicznie

- Zwykły HTML i wspólny `style.css`, bez kroku budowania. Najpierw układ pod telefon (Android, Chrome), plus styl do druku na A4.
- `index.html` to katalog materiałów: każdy nowy materiał to osobna strona, dopisana do listy w `index.html`.
- Publikacja: publiczne repo `pkaz13/angielski-marysi`, GitHub Pages (`https://pkaz13.github.io/angielski-marysi/`), serwowane z gałęzi `main`, katalog główny. `.nojekyll` wyłącza przetwarzanie przez Jekyll.
