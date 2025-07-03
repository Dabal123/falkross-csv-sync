# Falk&Ross CSV Sync

Ten projekt automatycznie:
- pobiera plik CSV z Falk&Ross (z autoryzacją),
- usuwa pierwszy wiersz,
- zapisuje wynik w repozytorium jako `falkross_de_clean.csv`.

### 🔧 Konfiguracja

1. Przejdź do: **Settings → Secrets and variables → Actions → Secrets**
2. Dodaj dwa sekrety:

| Nazwa           | Wartość                        |
|------------------|---------------------------------|
| `FALKROSS_USER`  | `102094-5-nadrukinasztuki`     |
| `FALKROSS_PASS`  | `0k5X62WD`                     |

### 🔄 Harmonogram

Workflow działa **automatycznie co godzinę** dzięki CRON w GitHub Actions.

Możesz też uruchomić go ręcznie w zakładce **Actions → Pobierz CSV co godzinę → Run workflow**.
