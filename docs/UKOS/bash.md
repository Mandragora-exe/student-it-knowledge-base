# Notatki z Terminala

## System Kontroli Wersji (Git)
[WARP](docs/warp/git.md)

| Polecenie | Znaczenie |
| :--- | :--- |
| `git status` | Pokazuje stan repozytorium (zmienione, śledzone i nieśledzone pliki). |

### Przykład użycia Git
```bash
git status
```

---

## Podstawowe Polecenia Bash

| Polecenie | Przykład użycia | Opis działania |
| :--- | :--- | :--- |
| `pwd` | `pwd` | Wyświetla pełną ścieżkę do bieżącego katalogu roboczego. |
| `ls` | `ls -la` | Listuje zawartość katalogu w formacie szczegółowym, wliczając pliki ukryte (zaczynające się od kropki). |
| `cd` | `cd docs/ukos`<br>`cd ..` | **Przechodzenie między katalogami:**<br>`docs/ukos` – wejście do określonej ścieżki.<br>`..` – powrót do katalogu nadrzędnego. |
| `mkdir` | `mkdir -p docs/ukos` | Tworzy nowy katalog. Opcja `-p` automatycznie tworzy również brakujące katalogi nadrzędne w ścieżce. |
| `touch` | `touch bash.md` | Tworzy nowy, pusty plik o podanej nazwie lub aktualizuje znacznik czasu jego ostatniej modyfikacji, jeśli plik już istnieje. |
| `cp` | `cp bash.md bash-backup.md` | Kopiuje plik.<br>*Ważne:* Aby skopiować cały katalog wraz z zawartością, należy użyć opcji rekurencyjnej `-r`. |
| `mv` | `mv bash-backup.md archive.md` | Przenosi plik do nowej lokalizacji lub zmienia jego nazwę. |
| `rm` | `rm archive.md` | **Usuwa plik.**<br>*Ostrzeżenie:* Ta operacja trwale usuwa plik i omija kosz systemowy. |
| `cat` | `cat bash.md` | Wyświetla całą zawartość wskazanego pliku bezpośrednio w oknie terminala. |
| `clear` | `clear` | Czyści bieżący widok ekranu terminala. Nie usuwa historii wpisywanych wcześniej poleceń. |
| `rm` | `rm` | Usuwa pliki bez kosza. |
