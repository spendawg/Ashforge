# Ashforge Refactor

Project structure:
- `index.html` — markup
- `css/styles.css` — all styles
- `js/game.js` — all current game logic
- `assets/maps/veridia_world_map.png` — world map image

## Next cleanup passes
1. Split `js/game.js` into modules like `worldmap.js`, `combat.js`, `inventory.js`, `save.js`, and `ui.js`.
2. Move large content/data objects into separate data files.
3. Replace inline `onclick` handlers with event listeners over time.

Open `index.html` in a browser to run the game.
