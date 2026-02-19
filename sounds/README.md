# Game sounds (T-016)

Place royalty-free SFX here to replace in-game placeholders.

1. In `src/config/assets.ts` set **`useRealSfx: true`**.
2. Add these files (names must match exactly):
   - **attack.ogg** — tower attack / projectile hit (e.g. from [Kenney Impact Sounds](https://kenney.nl/assets/impact-sounds), CC0)
   - **death.ogg** — enemy death (e.g. from Kenney Impact Sounds, CC0)

Format: OGG preferred; Phaser 3 also supports MP3. If files are missing and `useRealSfx` is true, the loader will fail.

See `project-management/tickets/T-016/implementation/README.md` for full asset list and licenses.
