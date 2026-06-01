# Fresh Monokai

A Monokai-inspired color theme for the [Fresh](https://github.com/sinelaw/fresh) terminal text editor.

Monokai is a classic dark color scheme originally popularized by the Monokai theme for Sublime Text. This port brings the signature vibrant, high-contrast palette to Fresh with full editor, UI, syntax, diagnostic, and search coverage.

## Installation

```bash
git clone https://github.com/Zetaphor/fresh-monokai-theme.git ~/.config/fresh/themes/monokai
```

Then set the theme in your config:

```json
{ "theme": "monokai" }
```

Or switch via `Ctrl+P` → "Select Theme" → **Monokai**.

## Features

- Full editor colors (background, foreground, cursor, selection, line numbers, gutter, diffs)
- Complete UI palette (tabs, status bar, menus, popups, scrollbars, terminal, prompts)
- Syntax highlighting (keywords, strings, functions, types, constants, variables, operators, comments)
- Diagnostic colors (errors, warnings, info, hints)
- Search match highlighting
- Inheritance from the built-in `dark` base theme — only overrides what's different

## Colors

| Role       | RGB                 | Hex       |
|-----------|---------------------|-----------|
| Background| `[39, 40, 34]`      | `#272822` |
| Foreground| `[248, 248, 242]`   | `#f8f8f2` |
| Pink      | `[249, 38, 114]`    | `#f92672` |
| Yellow    | `[230, 219, 116]`   | `#e6db74` |
| Green     | `[166, 226, 46]`    | `#a6e22e` |
| Cyan      | `[102, 217, 239]`   | `#66d9ef` |
| Purple    | `[174, 129, 255]`   | `#ae81ff` |
| Gray      | `[117, 113, 94]`    | `#75715e` |

## Repository

https://github.com/Zetaphor/fresh-monokai-theme

## License

MIT
