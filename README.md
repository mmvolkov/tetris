# Tetris

Classic Tetris game built with HTML5 Canvas API.

## How to Play

Open `tetris.html` in any modern browser.

### Controls

| Key | Action |
|-----|--------|
| `←` `→` | Move left/right |
| `↑` | Rotate |
| `↓` | Soft drop |
| `Space` | Hard drop (+10 points) |
| `P` / `Esc` | Pause |
| `Enter` / `R` | Restart (after Game Over) |

### Scoring

- Hard drop: +10 points
- Lines cleared: +100 × level per line
- Level increases every 10 lines (speed increases)

## Technical Details

- Single HTML file with embedded CSS and JavaScript
- Canvas API for rendering
- No external dependencies
- Supports Russian and English keyboard layouts
