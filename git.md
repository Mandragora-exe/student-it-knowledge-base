# Git - Ściąga

## Podstawowe polecenia

| Polecenie | Przykład użycia | Co opisać |
|---|---|---|
| `git clone` | `git clone URL` | Pobranie repozytorium i utworzenie lokalnego katalogu |
| `git status` | `git status` | Sprawdzenie gałęzi oraz plików zmienionych i przygotowanych |
| `git add` | `git add docs/warp/git.md` | Dodanie konkretnego pliku do obszaru staging |
| `git commit` | `git commit -m "docs: add Git cheatsheet"` | Zapis przygotowanych zmian z czytelnym komunikatem |
| `git push` | `git push -u origin feature/git-cheatsheet` | Publikacja nowej gałęzi i ustawienie śledzenia |
| `git pull` | `git pull --ff-only origin main` | Pobranie zmian bez tworzenia merge commita |
| `git fetch` | `git fetch origin` | Pobranie informacji o zmianach bez modyfikacji plików |
| `git branch` | `git branch` | Wyświetlenie lokalnych gałęzi |
| `git switch` | `git switch -c feature/nazwa` | Utworzenie i przełączenie na nową gałąź |
| `git log` | `git log --oneline -5` | Podgląd ostatnich commitów |

---

## git clone

```bash
git clone https://github.com/user/repo.git
```

Pobiera zdalne repozytorium i tworzy lokalny katalog projektu.

---

## git status

```bash
git status
```

Pokazuje:

- aktualną gałąź
- zmodyfikowane pliki
- pliki dodane do staging area
- pliki nieśledzone

---

## git add

```bash
git add docs/warp/git.md
```

Dodanie pojedynczego pliku do staging area.

```bash
git add .
```

Dodanie wszystkich zmian.

---

## git commit

```bash
git commit -m "docs: add Git cheatsheet"
```

Tworzy commit z opisem zmian.

---

## git push

```bash
git push -u origin feature/git-cheatsheet
```

Publikuje gałąź w zdalnym repozytorium.

---

## git pull

```bash
git pull --ff-only origin main
```

Pobiera najnowsze zmiany z repozytorium.

---

## git fetch

```bash
git fetch origin
```

Aktualizuje informacje o zmianach bez scalania.

---

## git branch

```bash
git branch
```

Wyświetla lokalne gałęzie.

```bash
git branch -a
```

Wyświetla wszystkie gałęzie.

---

## git switch

```bash
git switch