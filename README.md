# Neon Rift

Neon Rift is a complete asset-free 2D space shooter built with Python and Pygame.

## Install and Run on Windows

1. Clone or download this GitHub repository.
2. Open the project folder in VS Code.
3. Open the integrated terminal.
4. Create the virtual environment:

   ```powershell
   uv venv
   ```

5. Install the dependencies:

   ```powershell
   uv pip install -r requirements.txt
   ```

6. Run the game:

   ```powershell
   uv run python test.py
   ```

### Troubleshooting

If you see `ModuleNotFoundError: No module named 'pygame'`, install the dependencies in the uv environment:

```powershell
uv pip install -r requirements.txt
```

If you see `externally-managed-environment`, do not install packages into the system Python with `pip`. Use `uv venv` and the uv commands above instead.

## Project Structure

- `README.md`: installation, controls, and project information.
- `requirements.txt`: pinned Python dependencies.
- `test.py`: main game entry point; run this file to start Neon Rift.
- `space_game.py`: game implementation, including menus, levels, combat, sounds, and rendering.
- `.gitignore`: files excluded from Git, including the virtual environment.

## Controls

- `WASD` or arrow keys: move
- `Space`: fire
- `Esc`: pause or resume
- `Enter`: start or restart from keyboard
- Mouse: use the menu buttons

The game creates `neon_rift_high_score.txt` beside the script after the first scored run. Graphics, explosions, and sound effects are generated at runtime, so no asset download is required.