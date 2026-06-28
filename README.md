# LF2_19 (Rust / F.LF-compatible JSON package)

Content package for **[flf-rust](https://github.com/sn99/flf-rust)** — the Rust/WASM port of [Project-F/F.LF](https://github.com/Project-F/F.LF).

Mirrors [Project-F/LF2_19](https://github.com/Project-F/LF2_19) data/sprites/UI/sound/backgrounds, converted from AMD `define({...})` JS modules to **JSON** for the Rust loader.

## Hosted assets (GitHub Pages)

**https://sn99.github.io/LF2_19/**

`manifest.json` entry point. Engine config:

```json
{ "package": "https://sn99.github.io/LF2_19" }
```

## Layout

- `manifest.json` — package manifest
- `data/` — object frames (characters, weapons, specials, effects)
- `sprite/`, `bg/`, `UI/`, `sound/`, `AI/`

## License / credits

Original LF2 by Marti Wong & Starsky Wong. Package structure follows Project F LF2_19. Used for open reimplementation compatibility.
