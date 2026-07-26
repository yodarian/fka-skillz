# Copilot Instructions

Zentrale Konfiguration für GitHub Copilot in diesem Repository.

## Skills

Skills sind in `.agents/skills/` organisiert und werden von Copilot automatisch geladen.

## Agents

Agents sind in `.agents/` organisiert und werden von Copilot automatisch erkannt.

## Test-Umgebung

Das Laravel-Projekt unter `/laravel` dient zum Testen und Validieren der Skills in einer realen Projektumgebung.

## Best Practices

1. Jeder Skill/Agent bekommt einen eigenen Ordner mit einer `SKILL.md` oder `AGENT.md`
2. Aussagekräftige Namen für Skills und Agents verwenden
3. Dokumentation direkt in den Dateien maintainen
4. Test-Ergebnisse im Laravel-Projekt validieren
