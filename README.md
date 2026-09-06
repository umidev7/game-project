# Neon Rift

Neon Rift is a complete asset-free 2D space shooter built with Python and Pygame.

## Run in VS Code

1. Install Python 3.10 or newer.
2. Open this folder in VS Code and select the Python interpreter.
3. In the integrated terminal, run:

   ```powershell
   py -m pip install -r requirements.txt
   py test.py
   ```

   On systems where `python` is configured instead of `py`, use `python -m pip` and `python test.py`.

## Controls

- `WASD` or arrow keys: move
- `Space`: fire
- `Esc`: pause or resume
- `Enter`: start or restart from keyboard
- Mouse: use the menu buttons

The game creates `neon_rift_high_score.txt` beside the script after the first scored run. Graphics, explosions, and sound effects are generated at runtime, so no asset download is required.