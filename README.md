# awesome-fresh 😎
A curated list of **Fresh Editor** plugins, themes, keymaps, configs, and community resources.

> Fresh is a terminal-based text editor focused on a familiar, VS Code-ish workflow, with **TypeScript plugins running in a sandboxed Deno environment**.

---

## Contents
- [Official](#official)
- [Plugins](#plugins)
- [Themes](#themes)
- [Keymaps](#keymaps)
- [Configs](#configs)
- [Packaging & Install Options](#packaging--install-options)
- [Community](#community)
- [Articles & Videos](#articles--videos)
- [Contributing](#contributing)
- [License](#license)

---

## Official
- **Fresh Editor (main repo)** — source, docs, built-in plugins/themes/keymaps, release notes  
  https://github.com/sinelaw/fresh
- **Official website**  
  https://sinelaw.github.io/fresh/
- **Built-in ecosystem directories (in the main repo)**  
  Fresh ships with `plugins/`, `themes/`, and `keymaps/` directories in-tree.

---

## Plugins
> Fresh supports plugins written in **TypeScript** and run in a **sandboxed Deno environment**.

### Built-in (ships with Fresh)
Fresh includes a growing set of built-in plugins (and plugin-related features like TODO highlighting, merge conflict helpers, path completion, etc.).

- Built-in plugins (browse the repo):  
  https://github.com/sinelaw/fresh

### Third-party
> If you know of more third-party plugins, please PR them in!

- _(None widely-established yet — ecosystem is young)_  
  If you’ve published one, open a PR and we’ll list it.

---

## Themes

### Third-party themes
- **Catppuccin for Fresh** — Latte / Frappé / Macchiato / Mocha  
  https://github.com/milon/catppuccin-fresh

### Built-in themes + Theme tooling
Fresh includes a `themes/` directory in the main repo.
Fresh also has a **Theme Editor** with schema + UI features (see release notes).

---

## Keymaps
Fresh includes a `keymaps/` directory in the main repo.
Release notes frequently mention keymap improvements (especially around terminal-friendly macOS bindings).

---

## Configs
Fresh ships an example config in the main repo (`config.example.json`).

- Example config (in repo):  
  https://github.com/sinelaw/fresh

> If you have a “great default” config (LSP presets, UI layout, sensible keybinding tweaks, etc.), PR it here under a `configs/` folder.

---

## Packaging & Install Options
Fresh supports multiple install methods (brew, AUR, Debian/Ubuntu packages, rpm, AppImage, Flatpak, npm/npx, cargo-binstall, crates.io, nix).

- Arch Linux AUR package page:  
  https://aur.archlinux.org/packages/fresh-editor

---

## Community
- **GitHub Discussions (Fresh)**  
  https://github.com/sinelaw/fresh/discussions
- **GitHub Issues (Fresh)**  
  https://github.com/sinelaw/fresh/issues
- **Show HN thread (early discussion + context)**  
  https://news.ycombinator.com/item?id=46135067

---

## Articles & Videos
> These are useful for onboarding, feature discovery, and spreading the word.

- “Fresh: The Terminal Editor that Opens 2GB Logs…” (Medium)  
  https://medium.com/@trivajay259/fresh-the-terminal-editor-that-opens-2gb-logs-in-600ms-with-40mb-ram-6522c7d7bd64

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
This list is provided under the CC0 / public-domain spirit unless otherwise stated.  
Fresh itself is GPL-2.0 licensed.
