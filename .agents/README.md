# Agents

Dieser Ordner enthält spezialisierte Agents für GitHub Copilot.

## Struktur

Jeder Agent hat seinen eigenen Ordner mit einer `AGENT.md` Datei:

```
.agents/
├── agent-name-1/
│   └── AGENT.md
├── agent-name-2/
│   └── AGENT.md
└── ...
```

## Erstellung eines neuen Agents

1. Erstelle einen neuen Ordner mit einem aussagekräftigen Namen (z.B. `code-reviewer`)
2. Erstelle eine `AGENT.md` Datei mit:
   - Beschreibung des Agents
   - Spezialgebiet/Fokus
   - Anweisungen für den Agent
   - Zusammenarbeit mit Skills

Copilot wird den Agent automatisch erkennen und laden.

## Beispiel AGENT.md

```markdown
# Code Reviewer Agent

Spezialisiert auf Code-Reviews und Qualitätsprüfung.

## Fokus

- Sicherheit
- Performance
- Best Practices

## Anweisungen

- ...
```
