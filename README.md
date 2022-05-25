# "Budowa i działanie witryn internetowych" - laboratorium 1

## Pobieranie i inicjowanie środowiska:

1. Otwórz okno linii poleceń.
2. Pobierz repozytorium z GitHub'a: `git clone https://github.com/WojciechThomas/bdwi2021-1.git`
3. Wejdź do pobranego folderu: `cd bdwi2021-1`
4. Utwórz wirtualne środowisko Pythona: `python -m venv venv`
5. Aktywuj wirtualne środowisko Pythona (przejrzyj Uwagi poniżej!): `.\venv\Scripts\activate.bat`
6. Zaktualizuj instalator pip: `python -m pip install --upgrade pip`
7. Zainstaluj wszystkie potrzebne biblioteki: `pip install -r requirements.txt`

### Uwagi:

- Jeśli używasz systemu MacOS lub Linux w punkcie 5. użyj polecenia `./venv/Scripts/activate`
- Jeśli używasz okna Powershell w systemie Windows:
  - po otwarciu nowego okna uruchom polecenie `Set-ExecutionPolicy RemoteSigned -Scope Process`
  - w punkcie 5. użyj polecenia `.\venv\Scripts\Activate.ps1`
- Nie używaj do pracy z Pythonem okna Git Bash w systemie Windows.

## Uruchamianie aplikacji

Możesz przetestować swoją instalację wpisując: `mkdocs serve`

Jeśli wszystko zostało poprawnie zainstalowane na ekranie powinny pojawić się komunikaty:

```
INFO     -  Building documentation...
INFO     -  Cleaning site directory
INFO     -  Documentation built in 0.25 seconds
INFO     -  [09:21:34] Watching paths for changes: 'docs', 'mkdocs.yml'
INFO     -  [09:21:34] Serving on http://127.0.0.1:8000/
 ```
 
Po wpisaniu w oknie przeglądarki internetowej podanego adresu (`http://127.0.0.1:8000` lub `http://localhost:8000`) przeglądarka 
powinna wyświetlić stronę aplikacji MKDocs. Działanie aplikacji zakończysz naciskając w oknie konsoli `Ctrl-C`.

Aby wygenerować statyczną wersję strony (np. do wgrania na serwer WWW) wykonaj polecenie: `mkdocs build`


Powodzenia!
