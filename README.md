# awesome-fresh
A curated list of **Fresh Editor** plugins, themes, keymaps, configs, and community resources.

> Fresh is a terminal-based text editor focused on a familiar, VS Code-ish workflow, with **TypeScript plugins running in a sandboxed Deno environment**.

---

## Contents
- [awesome-fresh](#awesome-fresh)
  - [Contents](#contents)
  - [Official](#official)
  - [Plugins](#plugins)
    - [Built-in (ships with Fresh)](#built-in-ships-with-fresh)
    - [Third-party](#third-party)
  - [Themes](#themes)
    - [Third-party themes](#third-party-themes)
    - [Built-in themes + Theme tooling](#built-in-themes--theme-tooling)
  - [Keymaps](#keymaps)
  - [Languages](#languages)
  - [Configs](#configs)
  - [Packaging \& Install Options](#packaging--install-options)
  - [Community](#community)
  - [Articles \& Videos](#articles--videos)
  - [Contributing](#contributing)
    - [Submission format](#submission-format)
  - [License](#license)

---

## Official
- **[Fresh Editor (main repo)](https://github.com/sinelaw/fresh)** — source, docs, built-in plugins/themes/keymaps, release notes
- **[Official website](https://sinelaw.github.io/fresh/)**
- **Built-in ecosystem directories (in the main repo)**  
  Fresh ships with `plugins/`, `themes/`, and `keymaps/` directories in-tree.

---

## Plugins
> Fresh supports plugins written in **TypeScript** and run in a **sandboxed Deno environment**.

### Built-in (ships with Fresh)
Fresh includes a growing set of built-in plugins (and plugin-related features like TODO highlighting, merge conflict helpers, path completion, etc.).

- [Built-in plugins](https://github.com/sinelaw/fresh) (browse the repo)

### Third-party
> If you know of more third-party plugins, please PR them in!
- **[Herdr Plugin](https://github.com/rvalledorjr/herdr-fresh)** - A herdr plugin that runs Fresh, the terminal IDE, as a file viewer and editor inside a herdr pane.
- **[Copilot Plugin](https://github.com/Hezkore/fresh-copilot)** - GitHub Copilot plugin for the Fresh terminal based IDE & text editor.
- **[UnRAID Plugin](https://github.com/johnngone/fresh-editor-unraid)** - An Unraid plugin that installs Fresh, a modern, full-featured terminal text editor with familiar keybindings, mouse support, and IDE-level features.
- **[WakaTime plugin](https://github.com/Jelloeater/fresh-plugin-wakatime)** - Automatic time tracking for your coding activity in the Fresh editor.
- **[Unibeautify for Fresh](https://github.com/hofftodd/fresh-plugins/tree/main/unibeautify)** - Format the active buffer (or just the selection) with the right formatter for each language.
- **[Fresh Codespell](https://github.com/thedadams/fresh-codespell)** - Code-aware spell checking for the Fresh terminal editor, powered by the CSpell command-line tool.
- **[Fresh Simple Runner](https://github.com/zongou/fresh-simple-runner)** - Fresh editor simple-runner extension
- **[Fresh Claude Plugin](https://github.com/mruff-aeq/fresh-claude)** - Claude Code IDE layout for fresh terminal editor. One command, full cockpit
- **[Fresh Markdown Previewer](https://github.com/sunnypdater/fresh-md-pretty)** - A Fresh terminal editor plugin that renders .md files as a beautiful, color-highlighted preview panel — automatically on open, with live re-render as you type.

---

## Companion Stuff
> Things that are not plugins, but have to do with the Fresh editor
> - **[Fresh Web GUI](https://github.com/amirhosseindavoody/fresh-gui)** - Self hosted web GUI using Fresh as it's editor


---

## Themes

### Built-in themes + Theme tooling
Fresh includes a `themes/` directory in the main repo.
Fresh also has a **Theme Editor** with schema + UI features (see release notes).

### Third-party themes
- **[Catppuccin for Fresh](https://github.com/milon/catppuccin-fresh)** — Latte / Frappé / Macchiato / Mocha  
- **[Fresh Monokai](https://github.com/Zetaphor/fresh-monokai-theme)** — Monokai-inspired dark theme with full editor, UI, syntax, and diagnostic coverage
- **[XScriptor Themes](https://github.com/xscriptor-colors/fresh)** - Custom color themes for Fresh, the terminal text editor. This repository contains multiple JSON theme files compatible with Fresh.
- **[Light Table Theme](https://github.com/clojens/cheerup-lighttable-theme)** - A Light Table IDE theme based on the Borealis theme and the Cheer up emo kid colorscheme.
- **[Fresh Rose Theme](https://github.com/Y8ungS8ul/fresh-rose-themes)** - A dark pink theme for the Fresh editor, featuring bright, saturated colors.
- **[Bluloco Theme](https://github.com/Nandaleio/bluloco-fresh)** - A collection of Bluloco color scheme themes for Fresh Editor, featuring both dark and light theme.
- **[Vesper Theme](https://github.com/h1st0ry3D/fresh-vesper-theme)** -  A modern and clean color theme for Fresh (terminal text editor)
  

---

## Keymaps
Fresh includes a `keymaps/` directory in the main repo.
Release notes frequently mention keymap improvements (especially around terminal-friendly macOS bindings).

---

## Languages
Language packs and bundles for Fresh Editor.

- _(None widely-established yet — ecosystem is young)_  
  If you’ve published one, open a PR and we’ll list it.

> Contribute language packs under `languages/`.

---

## Configs
Fresh ships an example config in the main repo (`config.example.json`).

- **[Example config (in repo)](https://github.com/sinelaw/fresh)**

> If you have a “great default” config (LSP presets, UI layout, sensible keybinding tweaks, etc.), PR it here under a `configs/` folder.

---

## Packaging & Install Options
Fresh supports multiple install methods (brew, AUR, Debian/Ubuntu packages, rpm, AppImage, Flatpak, npm/npx, cargo-binstall, crates.io, nix).

- [Arch Linux AUR package page]((https://aur.archlinux.org/packages/fresh-editor))

---

## Community
- **[GitHub Discussions (Fresh)](https://github.com/sinelaw/fresh/discussions)**  
- **[GitHub Issues (Fresh)](https://github.com/sinelaw/fresh/issues)**
- **[Show HN thread (early discussion + context)](https://news.ycombinator.com/item?id=46135067)**

---

## Articles & Videos
> These are useful for onboarding, feature discovery, and spreading the word.

- **[“Fresh: The Terminal Editor that Opens 2GB Logs…” (Medium)](https://medium.com/@trivajay259/fresh-the-terminal-editor-that-opens-2gb-logs-in-600ms-with-40mb-ram-6522c7d7bd64)**

---

## Contributing
PRs welcome — especially for:
- plugins
- themes
- keymaps
- config packs (LSP presets, minimal configs, “VS Code-ish defaults”, etc.)
- docs / tutorials / videos

### Submission format
Add your link under the right section using this format:

- **Name** — one-line description  
  URL

---

## License
This list is provided under the MIT License.  
Fresh itself is GPL-2.0 licensed.
