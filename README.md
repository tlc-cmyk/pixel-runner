# Pixel Runner

A tiny 16-bit style side-scrolling dodge/collect game. One HTML file, no dependencies — works offline.

## How to play

1. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).
2. On the title screen, press **Space** or **Enter** to start.
3. Survive as long as you can, jump over obstacles, and grab coins/stars.

## Controls

| Key | Action |
|-----|--------|
| ← / → (or A / D) | Move left / right |
| Space / ↑ / W | Jump |
| R / Space / Enter | Restart after Game Over |

## Goal

- Hitting spikes, crates, or blobs = **Game Over**
- Coins = **+10** score, stars = **+50**
- Distance traveled also increases score slowly
- Speed ramps up over time (shown as `x1.0` … in the top-right)

## Technical notes

- Logical canvas: **480×270** (16:9), CSS-scaled ~2× with `image-rendering: pixelated`
- All sprites are drawn procedurally (no image files)
- Pure HTML + CSS + JS; no CDN or network required
