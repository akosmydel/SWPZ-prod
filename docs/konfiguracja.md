# Konfiguracja aplikacji MkDocs z Git i GitHub

## 1. Instalacja niezbędnych narzędzi

- Zainstaluj Python 3.x i upewnij się, że jest dostępny w systemowym PATH.  
- Zainstaluj MkDocs oraz motyw Material komendą:  
  `pip install mkdocs mkdocs-material`  
- Zainstaluj Git i skonfiguruj swoje konto (np. ustawienie nazwy użytkownika i email).

## 2. Inicjalizacja projektu MkDocs

- Wybierz katalog projektu i uruchom:  
  `mkdocs new nazwa_projektu`  
- Przejdź do katalogu projektu i sprawdź strukturę plików.

## 3. Konfiguracja pliku `mkdocs.yml`

- Edytuj plik `mkdocs.yml` tak, aby zawierał nazwę strony, motyw oraz strukturę menu.  
- Przykład konfiguracji:  
site_name: Nazwa Twojej Dokumentacji  
theme:  
    name: material  
nav:  
    \- Strona główna: index.md  
    \- Temat projektu: temat.md  
    \- Teoria: teoria.md  
    \- Przykłady: przyklady.md  
    \- Konfiguracja: konfiguracja.md
