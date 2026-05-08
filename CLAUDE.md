# HTML Presentation Generator Skill

Du erstellst professionelle HTML-Präsentationen als Single-File.

## Design-System

### Farben (CSS Variables)
- --accent-primary: #3b82f6 (Blau)
- --accent-secondary: #8b5cf6 (Lila)
- --bg-color: #0f172a (Dark Blue)
- --text-primary: #f1f5f9

### Visuelle Effekte
- Dark Mode mit Glassmorphism (backdrop-filter: blur)
- Gradient-Texte für Überschriften
- Subtile Animationen (fadeIn, slideInLeft)
- Progress-Bar oben

## Technische Anforderungen

- Alles in EINER HTML-Datei (CSS im `<style>`, JS im `<script>`)
- KEINE externen Dependencies oder CDNs
- Vanilla JavaScript
- Responsive: Sidebar (Desktop) / Hamburger-Menu (Mobile)

## Komponenten

| Komponente | Verwendung |
|------------|------------|
| Section | Jeder "Slide" = 100vh |
| Glass Card | Container für Inhalte |
| Feature Grid | Grid mit Icon-Karten |
| Timeline | Chronologische Abläufe |
| Accordion | FAQs, erweiterbare Inhalte |
| Code Block | Code mit Copy-Button |
| Highlight Box | Wichtige Hinweise |
| Eyebrow | Mono-Label über Section-Headlines (`.eyebrow`, `.eyebrow-row` mit `.dot`/`.sep`) |

## Erweiterte Design-Tokens (additiv, optional)

Neben den Basis-Variablen (`--accent-primary`, `--bg-color`, `--text-*`) liefert das Template eine reichere Token-Schicht für Layouts mit mehr Hierarchie:

- **Surfaces:** `--surface-1/2/3/inset`
- **Foreground:** `--fg-1/2/3/4`
- **Signal-Variants:** `--signal`, `--signal-hover/press/muted/glow/ring`
- **Funktional:** `--positive`, `--negative`, `--warning`
- **Type-Skala:** `--fs-eyebrow` (11px) bis `--fs-display` (80px), 11 Stufen
- **Spacing (8px-Basis):** `--s-1` (4px) bis `--s-32` (128px)
- **Radii:** `--r-sm/md/lg/xl/pill`
- **Motion:** `--ease-standard/out`, `--dur-fast/med/slow`

Bestehende Variablen bleiben unverändert. Die neuen Tokens sind opt-in — verwenden, wo sie passen, ignorieren, wo die Basis reicht.

## Interaktivität

- Keyboard-Navigation (Pfeiltasten für Slides)
- Scroll-Progress-Anzeige
- Copy-to-Clipboard für Code
- Mobile Hamburger-Menu

## Workflow

1. User beschreibt Präsentation (Thema, Slides, Zielgruppe)
2. Erstelle komplette HTML-Datei
3. Speichere als `presentations/[name]/index.html`
4. Commit mit aussagekräftiger Message
5. Push zu GitHub

## Ordnerstruktur

```
Presentations/
├── CLAUDE.md              ← Dieser Skill
├── index.html             ← Vorlage/Template
├── presentations/         ← Alle Präsentationen hier
│   ├── style-preview/     ← Design-Referenz
│   ├── claude-code-quickstart/
│   └── [neue-ppt]/        ← Neue Präsentationen
│       └── index.html
```

## Beispiel

User: "Erstelle eine Präsentation über Docker für Einsteiger, 6 Slides"

→ Erstelle HTML mit:
1. Was ist Docker?
2. Warum Container?
3. Installation
4. Erste Schritte (Befehle)
5. Dockerfile Basics
6. Nächste Schritte

## Hinweise

- Maximal 10-12 Slides pro Präsentation
- Weniger Text, mehr visuelle Elemente
- Deutsche Umlaute vermeiden in IDs
- Als Vorlage siehe: index.html in diesem Repository
