# Contributing to ProCoach Prompts

Danke für dein Interesse, zu diesem Projekt beizutragen! 🎉

## 📋 Inhaltsverzeichnis

- [Code of Conduct](#code-of-conduct)
- [Wie kann ich beitragen?](#wie-kann-ich-beitragen)
- [Prompt-Richtlinien](#prompt-richtlinien)
- [Pull Request Prozess](#pull-request-prozess)
- [Stil-Guide](#stil-guide)

---

## Code of Conduct

Dieses Projekt folgt einem offenen und respektvollen Umgang. Wir erwarten von allen Beitragenden:

- Respektvolle und konstruktive Kommunikation
- Offenheit für Feedback und andere Meinungen
- Fokus auf das Wohl der Community

---

## Wie kann ich beitragen?

### 🐛 Bugs melden
- Nutze das Issue-Template für Bug Reports
- Beschreibe das Problem so genau wie möglich
- Gib an, mit welchem LLM du getestet hast

### 💡 Neue Prompts vorschlagen
- Öffne ein Issue mit dem Tag `[Feature Request]`
- Beschreibe den Use Case und die Zielgruppe
- Erkläre, warum dieser Prompt die Sammlung bereichert

### 📝 Prompts einreichen
- Fork das Repository
- Erstelle deinen Prompt nach den [Prompt-Richtlinien](#prompt-richtlinien)
- Teste den Prompt gründlich
- Öffne einen Pull Request

### 🔧 Bestehende Prompts verbessern
- Fehler korrigieren
- Formulierungen optimieren
- Wissenschaftliche Quellen ergänzen

---

## Prompt-Richtlinien

### Qualitätskriterien

Jeder Prompt muss folgende Kriterien erfüllen:

#### ✅ Pflicht

| Kriterium | Beschreibung |
|-----------|--------------|
| **Evidenzbasiert** | Empfehlungen basieren auf wissenschaftlichen Erkenntnissen |
| **Interview-First** | Systematische Informationssammlung vor Planerstellung |
| **Sicherheit** | Disclaimer und Warnhinweise bei Gesundheitsthemen |
| **Verständlichkeit** | Klare Sprache, Fachbegriffe werden erklärt |
| **Getestet** | Funktioniert mit mindestens 2 LLMs (z.B. GPT-4, Claude) |

#### 🎯 Empfohlen

- Adaptive Logik (Nachfragen je nach Antwort)
- Modularer Aufbau (kombinierbar mit anderen Prompts)
- Beispiel-Konversation im `/examples` Ordner
- Mehrsprachigkeit (DE + EN)

### Prompt-Struktur

```markdown
# [Prompt-Name]

## Beschreibung
Kurze Beschreibung des Prompts und seiner Zielgruppe.

## Anwendungsbereich
- Zielgruppe
- Use Cases
- Voraussetzungen

---

## Systemprompt

[Hier der eigentliche Prompt]

---

## Nutzungshinweise
- Tipps zur optimalen Nutzung
- Bekannte Einschränkungen

## Changelog
- v1.0 (YYYY-MM-DD): Initial release
```

### Dateinamenskonvention

- Kleinbuchstaben
- Bindestriche statt Leerzeichen
- Beschreibender Name
- `.md` Endung

**Beispiele:**
- `nutrition-coach.md` ✅
- `NutritionCoach.md` ❌
- `prompt1.md` ❌

---

## Pull Request Prozess

### 1. Fork & Clone

```bash
git clone https://github.com/DEIN-USERNAME/procoach-prompts.git
cd procoach-prompts
```

### 2. Branch erstellen

```bash
git checkout -b feature/mein-neuer-prompt
```

Naming Convention für Branches:
- `feature/beschreibung` – Neue Prompts
- `fix/beschreibung` – Bugfixes
- `docs/beschreibung` – Dokumentation
- `improve/beschreibung` – Verbesserungen

### 3. Änderungen committen

```bash
git add .
git commit -m "Add: Neuer Yoga-Coach Prompt"
```

Commit-Message-Format:
- `Add:` – Neue Dateien/Features
- `Fix:` – Bugfixes
- `Update:` – Aktualisierungen
- `Remove:` – Entfernungen
- `Docs:` – Dokumentation

### 4. Push & Pull Request

```bash
git push origin feature/mein-neuer-prompt
```

Dann auf GitHub einen Pull Request öffnen.

### 5. Review

- Mindestens 1 Review erforderlich
- Feedback umsetzen oder diskutieren
- Nach Approval wird gemerged

---

## Stil-Guide

### Sprache

- **Deutsch** als Hauptsprache (Prompts können zusätzlich EN haben)
- Du-Form in Prompts (nicht Sie)
- Aktive Formulierungen bevorzugen
- Fachbegriffe in Klammern erklären

### Markdown

- Überschriften hierarchisch nutzen (`#`, `##`, `###`)
- Codeblöcke mit Syntax-Highlighting
- Tabellen für strukturierte Informationen
- Emojis sparsam und konsistent einsetzen

### Formatierung

```markdown
# Überschrift 1
## Überschrift 2
### Überschrift 3

**Fett** für wichtige Begriffe
*Kursiv* für Betonungen
`Code` für technische Begriffe

> Blockquotes für Hinweise/Warnungen

- Aufzählungen
- mit Bindestrichen

1. Nummerierte
2. Listen
```

---

## Fragen?

Öffne ein Issue mit dem Tag `[Question]` oder starte eine Discussion.

---

Danke, dass du ProCoach Prompts besser machst! 💪
