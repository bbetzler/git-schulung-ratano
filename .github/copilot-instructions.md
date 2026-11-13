# Anweisungen für GitHub Copilot

Die verbindlichen Projektregeln stehen in `AGENTS.md`. Kurzfassung:

- Nur reines HTML und CSS. Kein JavaScript, keine Frameworks, keine neuen Abhängigkeiten.
- Ändere nur die Dateien und Zeilen, die das Issue verlangt. Keine Umformatierung anderer Stellen.
- Farben nur über die Variablen in `:root` in `style.css`.
- Commit-Messages auf Deutsch, im Imperativ.
- Niemals direkt auf `main` pushen. Pull Requests enthalten `Closes #<nummer>`.
- Bei einem Merge-Konflikt: zuerst beide Seiten erklären, dann erst lösen.
