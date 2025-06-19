# Przykłady

Poniżej przedstawiamy przykładowe zastosowania MkDocs i integracji z GitHub w pracy zespołowej:

## Przykład 1: Tworzenie nowej sekcji dokumentacji

1. Utwórz nową gałąź w repozytorium dla swojej funkcji.  
2. Dodaj nowy plik Markdown w folderze `docs/`.  
3. Dodaj wpis w pliku `mkdocs.yml`, aby nowa sekcja pojawiła się w menu.  
4. Przetestuj lokalnie zmiany przez `mkdocs serve`.  
5. Zrób commit i push na zdalne repozytorium.  
6. Utwórz Pull Request na GitHub, gdzie zespół oceni i scali zmiany.

## Przykład 2: Publikacja dokumentacji

- Po zatwierdzeniu zmian na gałęzi głównej wykonaj `mkdocs build`, aby zbudować statyczną stronę.  
- Następnie opublikuj stronę na GitHub Pages za pomocą `mkdocs gh-deploy`.

## Szczegółowa instrukcja wdrożeniowa

Pełną instrukcję krok po kroku znajdziesz w pliku [Instrukcja wdrożeniowa](konfiguracja.md).