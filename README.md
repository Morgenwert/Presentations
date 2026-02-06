# Morgenwert Presentations

Create interactive HTML presentations with Claude Code and deploy to GitHub Pages.

## Quick Start

```
/ppt Topic of presentation
```

That's it. Claude creates a complete HTML presentation in Morgenwert design.

## Examples

| Input | Result |
|-------|--------|
| `/ppt AI in Customer Service` | Morgenwert design, asks for content |
| `/ppt Training for New Employees` | Morgenwert design, asks for slides |
| `/ppt Presentation for Client XY` | Asks for client CI (colors, style) |

## Default Settings (Morgenwert)

- **Light Mode** - White background, professional
- **Colors**: Dark blue (#1e40af), Medium blue (#3b82f6), Orange (#f97316)
- **Repository**: `Morgenwert/Presentations`
- **Design**: Subtle shadows, clean typography

## Interactive Elements

You can request the following elements:

- **Tabs** - Group content
- **Accordions** - FAQ-style, expandable
- **Timeline** - Processes, workflows
- **Statistic Boxes** - Highlight numbers
- **Feature Cards** - Display benefits
- **Highlight Boxes** - Tips, important notes
- **Code Blocks** - With copy button
- **ROI Calculator** - Calculate return on investment
- **Price Calculator** - Calculate project costs

See all elements live in the [Style Preview](presentations/style-preview/index.html).

## Client Presentations

When you say "for client XY", Claude asks for:
- Client colors (hex codes)
- Design style (Modern, Corporate, Creative)
- Light or Dark mode

## Folder Structure

```
Presentations/
├── CLAUDE.md               # Skill instructions
├── index.html              # Template
├── README.md               # This file
└── presentations/          # All presentations
    ├── style-preview/      # Design preview
    ├── claude-code-quickstart/
    └── [new-ppt]/          # New presentations here
```

## Live URLs

After push, presentations are available at:
```
https://morgenwert.github.io/Presentations/presentations/[folder-name]/
```

## Style Preview

Complete design preview with all elements and calculators:

| Version | Link |
|---------|------|
| Local | [presentations/style-preview/index.html](presentations/style-preview/index.html) |
| Online | [morgenwert.github.io/Presentations/presentations/style-preview/](https://morgenwert.github.io/Presentations/presentations/style-preview/) |

Includes: Cards, Tabs, Accordions, Timeline, Statistics, ROI Calculator, Price Calculator

## Templates

| Language | Local | Online |
|----------|-------|--------|
| Deutsch | [index.html](index.html) | [morgenwert.github.io/Presentations/](https://morgenwert.github.io/Presentations/) |
| English | [index-en.html](index-en.html) | [morgenwert.github.io/Presentations/index-en.html](https://morgenwert.github.io/Presentations/index-en.html) |
