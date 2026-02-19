# Game assets (T-016)

Place royalty-free art here to replace in-game placeholders. Enable in `src/config/assets.ts`.

## Tiles

- Set **`useRealTiles: true`**.
- Add **tiles.png**: 64×32 px image with two 32×32 tiles side by side — **first tile = path**, **second = buildable** (matches `map.json` and `placement.ts`).
- Sources: [Kenney Tower Defense Top-Down](https://kenney.nl/assets/tower-defense-top-down), [OpenGameArt 32×32 grass/path](https://opengameart.org/content/simple-tile-set-grass-and-dirt-path-32x32) (CC0). Export or slice to match dimensions.

## Tower

- Set **`useRealTowerSprites: true`**.
- Add **tower.png**: single tower/turret sprite (will be tinted per element). Suggested: one tile from [Kenney Tower Defense Top-Down](https://kenney.nl/assets/tower-defense-top-down) (CC0).

## Enemies

- Set **`useRealEnemySprites: true`**.
- Add:
  - **enemy_basic.png**
  - **enemy_fast.png**
  - **enemy_tank.png**
- Suggested: [Kenney Monster Builder Pack](https://kenney.nl/assets/monster-builder-pack) or [Platformer Art Extended Enemies](https://kenney.nl/assets/platformer-art-extended-enemies) (CC0). Pick or compose three distinct sprites.

If any file is missing when its flag is true, the loader will fail. See `project-management/tickets/T-016/implementation/README.md` for full list and licenses.
