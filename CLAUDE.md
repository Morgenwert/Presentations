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

## Interaktivität

- Keyboard-Navigation (Pfeiltasten für Slides)
- Scroll-Progress-Anzeige
- Copy-to-Clipboard für Code
- Mobile Hamburger-Menu

## Workflow

1. User beschreibt Präsentation (Thema, Slides, Zielgruppe)
2. Erstelle komplette HTML-Datei
3. Speichere als `[name].html` im Repository
4. Commit mit aussagekräftiger Message
5. Push zu GitHub

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
