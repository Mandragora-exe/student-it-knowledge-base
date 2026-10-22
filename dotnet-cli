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

---

## Narzędzia CLI .NET

| Polecenie | Przykład użycia | Opis działania |
| :--- | :--- | :--- |
| `dotnet --version` | `dotnet --version` | Sprawdza aktualnie używaną i zainstalowaną wersję zestawu .NET SDK. |
| `dotnet --list-sdks` | `dotnet --list-sdks` | Wyświetla listę wszystkich wersji SDK .NET zainstalowanych w systemie. |
| `dotnet new list` | `dotnet new list` | Wyświetla listę wszystkich dostępnych szablonów projektów, które można utworzyć (np. console, webapi). |
| `dotnet new console` | `dotnet new console` | Tworzy nowy projekt aplikacji konsolowej bezpośrednio w bieżącym katalogu. |
| `dotnet new console -n` | `dotnet new console -n MyApp` | Tworzy nowy projekt aplikacji konsolowej w nowym podkatalogu o nazwie `MyApp`. |
| `dotnet restore` | `dotnet restore` | Przywraca (pobiera) zależności i pakiety NuGet zdefiniowane w projekcie, wymagane do jego zbudowania. |
| `dotnet build` | `dotnet build` | Kompiluje projekt i jego zależności, wyświetlając ewentualne komunikaty o błędach i ostrzeżeniach. |
| `dotnet run` | `dotnet run --project MyApp` | Kompiluje (jeśli to konieczne) i natychmiast uruchamia wskazany projekt (np. `MyApp`). |
| `dotnet clean` | `dotnet clean` | Czyści katalogi wyjściowe projektu, usuwając pliki wygenerowane podczas poprzednich kompilacji (np. z folderów `bin` i `obj`). |
