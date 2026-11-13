# Regeln für Coding-Agenten

Gilt für Claude Code, Codex und GitHub Copilot.

Dieses Repo ist ein Übungsprojekt für eine Git-Schulung. Halte Änderungen klein und nachvollziehbar.

- Nur reines HTML und CSS. Kein JavaScript, keine Frameworks, keine neuen Abhängigkeiten.
- Ändere nur die Dateien und Zeilen, die das Issue verlangt. Keine Umformatierung anderer Stellen.
- Neue Profilseiten liegen in `team/` und basieren auf `team/_vorlage.html`.
- Farben nur über die Variablen in `:root` in `style.css`.
- Ein Branch pro Issue, Name: `issue-<nummer>-<kurzbeschreibung>`. Ausnahme: Der Copilot Coding Agent auf GitHub benennt seine Branches selbst (`copilot/…`).
- Commit-Messages auf Deutsch, im Imperativ, z. B. „Füge Footer-Link hinzu“.
- Niemals direkt auf `main` pushen. Pull Requests enthalten `Closes #<nummer>`.
- Bei einem Merge-Konflikt: zuerst beide Seiten erklären, dann erst lösen.
