# QUENCH

Monochromatic dark theme for Visual Studio Code.

Black, white, and gray only. No color anywhere — not even for errors or warnings. Syntax hierarchy is expressed through **weight** and **brightness**, not hue.

Quenching is the process of rapidly cooling hot metal to lock it into its final, hardened form. That is what you do when you review code.

## Design

- Comments: near-invisible, italic. They are noise.
- Operators and punctuation: dark gray. Structural, not semantic.
- Strings and keywords: medium gray, bold. Language constructs.
- Types and constants: light gray, bold. Structural definitions.
- Functions and identifiers: near-white, bold. What the code does.

Built for long sessions in dark environments. Designed to disappear and let the structure speak.

Covers the full workbench: editor, sidebar, activity bar, status bar, tabs, terminal, panels, widgets, diffs, debugger, and Git decorations.

## Palette

| Role | Hex |
|---|---|
| Background | `#0a0a0a` |
| Surface | `#111111` |
| Hover / Selection | `#18181b` |
| Borders | `#27272a` |
| Comments / Inactive | `#3f3f46` |
| Operators / Punctuation | `#52525b` |
| Tags / Decorators | `#71717a` |
| Keywords / Strings | `#a1a1aa` |
| Variables / Identifiers | `#e4e4e7` |
| Types / Constants | `#d4d4d8` |

## Installation

```
ext install wlcvs.quench
```

Or clone and install locally:

```bash
git clone https://github.com/wlcvs/quench ~/.vscode/extensions/wlcvs.quench-1.0.0
```

Then set in `settings.json`:

```json
"workbench.colorTheme": "QUENCH"
```
