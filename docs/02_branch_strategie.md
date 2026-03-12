# Branching-Strategie: GitHub Flow

Für die Black Market Software GmbH nutzen wir den **GitHub Flow**, da er leichtgewichtig ist und gut zu unserer kontinuierlichen Auslieferung passt.

## Die Regeln:
1. **Der `main`-Branch ist heilig:** Code im `main`-Branch muss immer stabil und lauffähig sein. Er ist durch Branch Protection Rules geschützt.
2. **Feature-Branches für jede Änderung:** Für neue Features, Bugfixes oder Dokumentationen erstellen wir aus dem `main` heraus einen neuen Branch (z. B. `feat/Name`, `bugfix/Name` oder `docs/Name`).
3. **Commits:** Wir nutzen konventionelle Commit-Nachrichten (Conventional Commits), um die Historie lesbar zu halten.
4. **Pull Requests:** Um Änderungen in den `main` zu integrieren, wird immer ein Pull Request (PR) erstellt.
5. **Merge:** Nach erfolgreichem Review wird der PR in den `main`-Branch gemerged.