# Ringside Royalty

A glam, glitter-and-gold Omarchy theme: hot pink, sequin purple and spotlight gold.

![Ringside Royalty theme for Omarchy](preview.png)

Inspired by the sequins, spotlights and swagger of 1980s pro-wrestling entrances. Deep velvet purples carry the surfaces, hot pink takes the accent, and spotlight gold marks anything selected, so the whole desktop feels like the walk to the ring.

## Install

```bash
omarchy theme install https://github.com/Gleasonmt/omarchy-ringside-royalty-theme
```

Or from the desktop: open the Omarchy menu → **Install** → **Style** → **Theme**, and paste the URL above.
The theme then shows up as **Ringside Royalty** in the theme switcher.

Update it with `omarchy theme update`, and remove it with `omarchy theme remove ringside-royalty`.

Requires Omarchy 4.

## Intro

Switching to Ringside Royalty with its first wallpaper plays a six-second intro: the spotlight opens on the ring and two gold glints flash before it settles on the wallpaper.

![Ringside Royalty intro](docs/intro.webp)

Turn intros on or off with `omarchy theme bg intro toggle`.

## Gallery

| Terminal | Neovim |
|:---:|:---:|
| ![Terminal](docs/terminal.webp) | ![Neovim](docs/editor.webp) |
| **Lock screen** | **Palette** |
| ![Lock screen](docs/lock.webp) | ![Palette](docs/palette.webp) |

### Boot unlock screen

A pink-to-gold OMARCHY wordmark between two stars. Choose it with `omarchy plymouth switcher`.

![Boot unlock screen](docs/unlock.webp)

## Wallpapers

Ringside, Robe, Entrance, Shades and the Omarchy wordmark.

![Wallpapers](docs/wallpapers.webp)

## Palette

| Role | Key | Color |
|---|---|---|
| Surfaces | `background` | `#240a35` |
| Text | `foreground` | `#fbe9ff` |
| Accent | `accent` | `#ff2fa4` |
| Selection | `selection` | `#5c1f6e` |
| Comments / dim text | `dark_foreground` | `#c08fd6` |
| Red | `red` | `#ff3b6b` |
| Orange | `orange` | `#ff9e3d` |
| Yellow | `yellow` | `#ffd23f` |
| Green | `green` | `#9dff6a` |
| Cyan | `cyan` | `#3ee8ff` |
| Blue | `blue` | `#8a7cff` |
| Magenta | `magenta` | `#ff2fa4` |

Terminals, Neovim, btop, Hyprland borders and the rest of Omarchy are generated from `colors.toml`.
`shell.toml` sets the bar, menus, notifications and lock screen.

## What's included

- `colors.toml`, `shell.toml`, `btop.theme`: the palette and Omarchy shell styling
- `backgrounds/`: four original wallpapers, an Omarchy wordmark wallpaper, and an intro video in `backgrounds/intros/`
- `chromium.theme` and `icons.theme`: Chromium toolbar color and icon theme
- `unlock.png` and `preview-unlock.png`: boot unlock logo
- `keyboard.rgb`: RGB keyboard color for supported ASUS ROG and Framework 16 laptops
- `firefox/`: an optional matching Firefox theme. Load it from `about:debugging` → **This Firefox** → **Load Temporary Add-on** → `firefox/manifest.json`

## Credits

The wallpapers, intro video and unlock logo were created by the author for this theme.
The Omarchy wordmark comes from [Omarchy](https://github.com/omacom/omarchy) (MIT), recolored for this palette.
The unlock logo uses Noto Sans (SIL Open Font License).

## License

[MIT](LICENSE)
