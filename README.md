# A Little Bday Quest

## IF YOU ARE PLANNING TO PLAY THIS GAME FIRST, DON'T READ THIS README



A quirky, puzzle-driven 2D adventure game built with Pygame.  
Explore rooms, collect keys, read notes, unlock doors, and solve a portal puzzle to finish your quest!

---

## Features

- **Multiple Levels:** Traverse through several uniquely designed rooms.
- **Directional Movement:** Move and rotate your character with WASD and arrow keys.
- **Interactable Furniture:** Open drawers, collect keys, and discover hidden notes.
- **Notes System:** Read in-game notes with a custom UI overlay.
- **Locked Doors:** Find and use keys to unlock doors and progress.
- **Portal Puzzle:** Solve a final puzzle by submitting the correct answer in `answer.txt`.
- **Debug Tools:** Visualize hitboxes for easier debugging.

---

## Controls

- **WASD / Arrow Keys:** Move and change direction.
- **E:** Interact with doors, shelves, and notes.
- **ESC:** Quit the game or close overlays.

---

## How to Play

1. **Install dependencies:**
    ```bash
    pip install -r requirements.py
    ```

2. **Run the game:**
    ```bash
    python thegame.py
    ```

3. **Explore:** Move around, interact with objects, and read notes to find clues.
4. **Collect Items:** Pick up keys and use them to unlock doors.
5. **Solve the Portal:** When you reach the portal, create an `answer.txt` file with the correct answer to finish the quest.

---

## File Structure

- `thegame.py` — Main game logic and loop.
- `sprites/` — All game graphics (player, doors, furniture, notes, etc.).
- `answer.txt` — Your answer for the portal puzzle (created by the player).
- Other dependencies: `requests` (for portal logic).

---

## Notes

- The game runs in fullscreen mode at 1920x1080 by default.
- All assets must be present in the `sprites/` directory.
- The portal puzzle requires a running server at `http://127.0.0.1:8000` (you can change to whatever you want) for the final request (see `get_data_from_server()`).

---

## Credits

- Game and code by LLL9177
- Built with [Pygame](https://www.pygame.org/)
