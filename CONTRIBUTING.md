# Contributing to awesome-fresh

Thanks for your interest in contributing to **awesome-fresh**!  
This repo exists to collect **high-quality, practical resources** for the Fresh editor: plugins, themes, keymaps, configs, and docs.

The goal is usefulness over quantity.

---

## What belongs here

We welcome contributions in these categories:

- **Plugins** (TypeScript, sandboxed, Fresh-compatible)
- **Themes** (JSON theme files or well-documented external themes)
- **Keymaps** (ready-to-use presets)
- **Configs** (opinionated, documented setups)
- **Docs** (guides, tutorials, ecosystem notes)

---

## Contribution rules (please read)

1. **One logical addition per PR**  
   Small, focused PRs are easier to review and merge.

2. **Prefer real files over links**  
   - If it can live in this repo, include it.
   - If not, include a clear link with documentation.

3. **Documentation is required**  
   - Plugins and themes must include a `README.md`
   - Explain *what it does*, *why it exists*, and *how to use it*

4. **Keep examples minimal and working**  
   - No experimental or broken code
   - No placeholder content in final submissions

5. **Be explicit and opinionated**  
   “Sensible defaults” should be explained, not implied.

---

## Where things go

| Type      | Location              |
|-----------|-----------------------|
| Plugins   | `plugins/`            |
| Themes    | `themes/`             |
| Keymaps   | `keymaps/`            |
| Configs   | `configs/`            |
| Docs      | `docs/`               |

External-only resources should be documented in Markdown files inside the relevant folder.

---

## Plugin guidelines

- Written in **TypeScript**
- Compatible with Fresh’s plugin API
- No network access unless explicitly documented
- No telemetry, tracking, or analytics

Include:
- `plugin.ts`
- `README.md`
- Clear installation steps

---

## Theme guidelines

- Valid Fresh theme JSON
- Human-readable color naming where possible
- Include screenshots if linking to an external repo

---

## Config guidelines

- Commented where appropriate
- Focused on a specific use case (performance, minimalism, VS Code-like, etc.)
- Should not assume undocumented plugins

---

## How to submit

1. Fork the repo
2. Create a feature branch
3. Add your contribution in the correct folder
4. Open a PR with:
   - What it does
   - Who it’s for
   - Any known limitations

---

## Code of conduct

Be respectful.  
No gatekeeping, no hostility, no bikeshedding for its own sake.

---

## License

By contributing, you agree that your contribution may be redistributed under the terms of this repository’s license.