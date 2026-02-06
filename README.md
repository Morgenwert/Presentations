# Morgenwert Presentations

Interaktive HTML-Präsentationen mit Claude Code erstellen und auf GitHub Pages deployen.

## Schnellstart

```
/ppt Thema der Präsentation
```

Das war's. Claude erstellt eine komplette HTML-Präsentation im Morgenwert-Design.

## Beispiele

| Eingabe | Ergebnis |
|---------|----------|
| `/ppt KI im Kundenservice` | Morgenwert-Design, fragt nach Inhalten |
| `/ppt Schulung für neue Mitarbeiter` | Morgenwert-Design, fragt nach Slides |
| `/ppt Präsentation für Kunde XY` | Fragt nach Kunden-CI (Farben, Stil) |

## Was automatisch verwendet wird (Morgenwert)

- **Light Mode** - Weißer Hintergrund, professionell
- **Farben**: Dunkelblau (#1e40af), Mittelblau (#3b82f6), Orange (#f97316)
- **Repository**: `Morgenwert/Presentations`
- **Design**: Dezente Schatten, klare Typografie

## Interaktive Elemente

Bei Bedarf kannst du folgende Elemente anfordern:

- **Tabs** - Inhalte gruppieren
- **Accordions** - FAQ-Stil, aufklappbar
- **Timeline** - Ablauf, Prozesse
- **Statistik-Boxen** - Zahlen hervorheben
- **Feature Cards** - Vorteile darstellen
- **Highlight Boxes** - Tipps, wichtige Hinweise
- **Code Blocks** - Mit Copy-Button
- **ROI-Rechner** - Return on Investment berechnen
- **Preiskalkulator** - Projektkosten kalkulieren

Alle Elemente siehst du live in der [Style Preview](presentations/style-preview/index.html).

## Kunden-Präsentationen

Wenn du sagst "für Kunde XY", fragt Claude nach:
- Kundenfarben (Hex-Codes)
- Design-Stil (Modern, Corporate, Kreativ)
- Hell oder Dunkel

## Ordnerstruktur

```
Presentations/
├── CLAUDE.md               # Skill-Anweisungen
├── index.html              # Vorlage/Template
├── README.md               # Diese Datei
└── presentations/          # Alle Präsentationen
    ├── style-preview/      # Design-Vorschau
    ├── claude-code-quickstart/
    └── [neue-ppt]/         # Neue Präsentationen hier
```

## Live URLs

Nach dem Push ist die Präsentation erreichbar unter:
```
https://morgenwert.github.io/Presentations/presentations/[ordner-name]/
```

## Style Preview

Die komplette Design-Vorschau mit allen Elementen und Rechnern:

| Version | Link |
|---------|------|
| Lokal | [presentations/style-preview/index.html](presentations/style-preview/index.html) |
| Online | [morgenwert.github.io/Presentations/presentations/style-preview/](https://morgenwert.github.io/Presentations/presentations/style-preview/) |

Enthält: Cards, Tabs, Accordions, Timeline, Statistiken, ROI-Rechner, Preiskalkulator

## Templates

| Sprache | Lokal | Online |
|---------|-------|--------|
| Deutsch | [index.html](index.html) | [morgenwert.github.io/Presentations/](https://morgenwert.github.io/Presentations/) |
| English | [index-en.html](index-en.html) | [morgenwert.github.io/Presentations/index-en.html](https://morgenwert.github.io/Presentations/index-en.html) |

