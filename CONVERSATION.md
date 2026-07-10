# Brick Breaker - Development Log

## Date: July 2026

### Features Implemented
- Black & white minimalist design (900x600 canvas)
- Paddle controls (mouse + keyboard)
- 7 rows × 12 columns of bricks
- Brick breaking with physics
- Ball speed increase per brick hit (+1.5%)
- Ball speed decrease on wall/paddle hit (-1.5%)
- Dynamic brick colors based on score (grayscale brightens with score)
- Flashing bricks at 800+ score
- Particle effects on brick destruction (10 particles burst)
- Pause menu (P key / Escape)
- Sound effects (Web Audio API - brick hit, paddle hit, wall bounce, lose life, game over, win)
- Centered brick layout
- Ball stuck fix (paddle + walls)
- Lives system (3 lives)
- Score tracking
- Win/Game Over screens
- GitHub Pages deployment

### Controls
| Action | Input |
|--------|-------|
| Move paddle | Mouse or ← → arrow keys or A/D |
| Start/Restart | SPACE or Click |
| Pause/Resume | P or Escape |

### Score Tiers (Brick Colors)
| Score | Brightness |
|-------|------------|
| 0-99 | Dark gray |
| 100-199 | Medium dark |
| 200-349 | Medium |
| 350-499 | Light |
| 500-699 | Lighter |
| 700+ | Nearly white |
| 800+ | Flashing white |

### Deployment
- Repo: https://github.com/fountainnsz-ux/brick-breaker
- GitHub Pages: https://fountainnsz-ux.github.io/brick-breaker/brick-breaker.html

### Tech Stack
- Single HTML file (no dependencies)
- HTML5 Canvas
- Web Audio API for sounds
