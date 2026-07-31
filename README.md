# Dilanti Light — Hermes Dashboard Theme

A modern light theme for the [Hermes Agent](https://hermes-agent.nousresearch.com/) web dashboard. Clean canvas, soft depth, Apple-inspired aesthetics.

![Theme: Light](https://img.shields.io/badge/type-light-blue)
![Hermes Dashboard](https://img.shields.io/badge/surface-Hermes%20Dashboard-0071e3)

## Screenshots

*(Add screenshots here after first release)*

## Installation

1. **Copy the theme file** to your Hermes dashboard themes directory:

   ```bash
   cp dilanti-light.yaml ~/.hermes/dashboard-themes/
   ```

2. **Activate it** by setting the theme in your Hermes config:

   ```bash
   hermes config set dashboard.theme dilanti-light
   ```

   Or edit `~/.hermes/config.yaml` directly:

   ```yaml
   dashboard:
     theme: dilanti-light
   ```

3. **Reload the dashboard.** The theme should be live immediately — no restart needed.

## Theme Details

| Property | Value |
|---|---|
| **Background** | `#f5f5f7` — Apple-style warm light gray |
| **Primary text** | `#1d1d1f` — near-black |
| **Accent** | `#0071e3` — Apple blue |
| **Cards** | Pure white (`#ffffff`) with subtle shadow |
| **Success / Warning / Destructive** | `#34c759` / `#ff9500` / `#ff3b30` |
| **Radius** | `0.75rem` (12px) |
| **Font (Sans)** | Inter, with SF Pro Display / Segoe UI fallbacks |
| **Font (Mono)** | JetBrains Mono, with SF Mono / Menlo fallbacks |
| **Base font size** | 15px, line-height 1.6 |

### Design principles

- **Apple-inspired palette** using the system colors from macOS / iOS
- **Soft depth** — cards have barely-visible shadows (`rgba(0,0,0,0.08)`) and hairline borders (`#e5e5ea`)
- **Frosted header** — backdrop-blur for a translucent sticky header effect
- **Minimal chrome** — thin scrollbars, smooth transitions, clean selection highlighting
- **Comfortable density** — generous spacing, not cramped

## Typography

Fonts are loaded from Google Fonts CDN:

- **Inter** (400–700) for all UI text
- **JetBrains Mono** (400–600) for code blocks and terminal

## Files

```
.
├── dilanti-light.yaml   # Theme definition
└── README.md            # This file
```

## Compatibility

Designed for Hermes Agent v0.19+.

## License

MIT — see [LICENSE](LICENSE).

## Contributing

This is a personal theme. Feel free to fork and customize for your own setup. Pull requests welcome if you spot improvements to contrast, accessibility, or cross-platform rendering.
