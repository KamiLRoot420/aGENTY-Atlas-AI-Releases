# Atlas AI — publiczny kanał aktualizacji danych

Repozytorium dystrybuuje **wyłącznie cztery rejestry danych** potrzebne do działania Atlas AI. Nie zawiera kodu źródłowego, pełnych opisów platform, algorytmów ani prywatnych konfiguracji.

- `data/update-manifest.json` — lista plików i kontrolne SHA-256.
- `Base/encyklopedia/03_ZRODLA_I_METODOLOGIA/*.json` — zatwierdzone rejestry benchmarków, statusów modeli, parametrów endpointów i szacunkowych ocen dopasowania do roli.

Atlas AI sprawdza ten kanał po uruchomieniu oraz co sześć godzin podczas działania. Pobiera tylko zmienione pliki i nie uruchamia zdalnego kodu.

**Ważne:** automatyczna synchronizacja GitHub nie oznacza, że benchmarki są automatycznie pobierane od producentów. Dane są aktualne wyłącznie do dat w poszczególnych źródłach i wymagają weryfikacji przed kolejną publikacją.

© 2026 Roots Lab. All rights reserved. Publiczne udostępnienie tych plików nie oznacza udzielenia licencji na dalszą redystrybucję lub adaptację.
