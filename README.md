# Incremental Survivors

A self-contained **automatic vampire-survivors** game — an undying knight (and friends) grind down an endless horde on their own. Everything (world, audio, most effects) is generated or embedded, so the whole game is a single HTML file with no build step.

### ▶ Play it now: **https://kamilch1k.github.io/incremental-survivors/**

## Play

Use the link above, or open **`index.html`** in any modern browser. That's it.

- The hero fights and moves automatically; you steer the *meta*: pick a champion and a realm, then spend **Gold** (per-run power) in the Forge and **Souls** (permanent) in Ascend.
- Walk onto shrines and roaming chests for buffs, free levels, and new abilities (rolled on a non-blocking casino reel).
- Save/Load via copyable **codes** (bottom of the panel). Esc / P pauses.

## Local desktop mode

On Windows, run **`Start-DesktopBackground.ps1`** to launch the local game as a hands-free animated background. It starts in wallpaper mode automatically, hides the shop and HUD, keeps only damage numbers plus HP/XP bars, and cycles through every realm without clicks.

- Press **Esc** or **P** while the game has focus to return to the normal menu.
- Run **`Stop-DesktopBackground.ps1`** to close the background browser process.
- Browser tabs cannot set the Windows desktop background directly; for a true behind-icons wallpaper, use the script shortcut or paste the `?wallpaper=1` URL into a live wallpaper tool such as Lively Wallpaper.

## Features

- **Champions** — 8 unlockable heroes, each with distinct mods.
- **Realms** — The Dungeon (a big interconnected layout of rooms), Greenwood, The Heavens (open sky), and The Inferno — each with its own tiles, props, lighting, and enemy tint.
- **Abilities** — orbital blades, bolts, nova, chain lightning, aura, wraiths, throwing axes, spectral knives, holy water, storm calling, spike fields, war pigeons, cross boomerangs — auto-applied and auto-upgraded.
- **Bosses** every few waves, roaming ability/power chests, progression via gold upgrades, soul ascensions, missions, and offline gold.
- **Windows-2000 retro UI** and a procedural **Web Audio** soundtrack + SFX (toggle with the ♪ button).

## Credits

- **Pixel art** — *DungeonTileset II* by **0x72** (Robert Norenberg), licensed **CC0 1.0** (public domain). Floor tiles and several monster frames are from the same pack.
- **Fonts** — *Press Start 2P* & *VT323* (Google Fonts, OFL).
- **Music & sound** — procedural, synthesized live with the Web Audio API.

## License

The bundled pixel art is **CC0**. The game code is provided as-is by the author.
