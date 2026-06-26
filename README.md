# NULL

Monochromatic dark theme for Visual Studio Code.

Black, white, and gray only. No color anywhere — not even for errors or warnings. Syntax hierarchy is expressed through **weight** and **brightness**, not hue.

## Design

- Comments: near-invisible, italic. They are noise.
- Operators and punctuation: dark gray. Structural, not semantic.
- Strings and keywords: medium gray, bold. Language constructs.
- Types and constants: light gray, bold. Structural definitions.
- Functions and identifiers: near-white, bold. What the code does.

Built for long sessions in dark environments. Designed to disappear and let the structure speak.

## Palette

| Token | Hex | Role |
|---|---|---|
| bg | `#0a0a0a` | Editor background |
| surface | `#111111` | Widgets, panels |
| surface2 | `#18181b` | Hover, selection |
| border | `#27272a` | Borders |
| subtle | `#3f3f46` | Comments, inactive chrome |
| faint | `#52525b` | Operators, punctuation |
| dim | `#71717a` | Tags, decorators |
| muted | `#a1a1aa` | Keywords, strings |
| text | `#e4e4e7` | Variables, identifiers |
| bright | `#d4d4d8` | Types, constants |

## Installation

Install from the VS Code Marketplace or:

```
ext install wlcvs.null
```
