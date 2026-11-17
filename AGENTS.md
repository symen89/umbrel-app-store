# AGENTS.md

<!-- BEGIN:werkafspraken SIM-294 -->
## Werkafspraken voor agents

Geldt voor elke agent en elke opdracht in deze repo. Deze repo is publiek.

### Algemeen
1. Werk altijd op een branch met een PR. Nooit direct op `main` (of de standaardbranch) committen of pushen.
2. Elke PR krijgt een review vóór merge.
3. Geen merge en geen release zonder de letterlijke go van de eigenaar. De goedkeuring van een agent telt niet als go.
4. Geen secrets in code, commits, logs, PR-teksten of chat. Nooit `.env`-, sleutel- of walletbestanden openen of citeren.
5. Elke opdracht begint met een Linear-kaart in team SIM. De sleutel staat in de branchnaam (bijv. `feat/SIM-301-korte-naam`) en in de PR-titel of -beschrijving, zodat Linear de PR koppelt.
6. Elke opdracht eindigt met dit blok:

```
TERUGMELDING
kaart: SIM-xxx (korte omschrijving)
repo/branch/commit:
PR: <url>
tests: <aantal geslaagd/overgeslagen, typecheck, lint>
CI: groen/rood/loopt
open punten:
wie deed wat:
wacht op eigenaar: ja/nee + wat
```

7. Commits staan op naam van de vaste bot-identiteit, tot er een eigen GitHub-identiteit voor de agent is. Nooit committen onder de naam van de eigenaar.
8. Geen force-push. Geen repo-instellingen wijzigen.

### Specifiek voor deze repo
- Publiek: geen interne namen van systemen, hostnamen, IP-adressen, bedragen of andere interne details in bestanden, commits of PR-teksten.
- Geen credentials in de repo; wachtwoorden komen uit de seed per app op het apparaat.
<!-- END:werkafspraken SIM-294 -->
