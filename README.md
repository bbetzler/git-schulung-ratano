# Team-Seite

Übungsprojekt für unsere Git- und GitHub-Schulung. Eine statische Seite ohne Build und ohne Abhängigkeiten.

## Aufbau

| Datei | Inhalt |
| --- | --- |
| `index.html` | Startseite mit der Teamliste |
| `style.css` | Das einzige Stylesheet, die Akzentfarbe steht in `--akzent` |
| `team/_vorlage.html` | Vorlage für eine Profilseite |
| `AGENTS.md` | Regeln für Coding-Agenten (Claude Code, Codex, Copilot) |
| `CLAUDE.md` | Verweist für Claude Code auf `AGENTS.md` |
| `.github/copilot-instructions.md` | Kurzfassung der Regeln für GitHub Copilot |
| `kursmaterial/` | Kursleitfaden, Spickzettel und Folien als PDF |

## Mitmachen

1. Issue aussuchen oder zugewiesen bekommen
2. `git pull`, dann einen Branch anlegen: `git switch -c issue-<nr>-<kurz>`
3. Ändern, committen, pushen
4. Pull Request mit `Closes #<nr>` erstellen und um Review bitten
