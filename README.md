# Flappy Bird

A simple Flappy Bird clone built with Python and Pygame. Control the bird, dodge the pipes, and try to get the highest score possible.

## Features

- Animated bird with flapping movement
- Gravity-based movement and mouse-click jumping
- Randomly positioned pipes
- Collision detection
- Score tracking
- Scrolling ground
- Restart button after a game over

## Requirements

- Python 3
- Pygame Community Edition (`pygame-ce`)

## Project Structure

Make sure your project files are arranged like this:

```text
flappy-bird/
├── main.py
└── img/
    ├── bg.png
    ├── ground.png
    ├── restart.png
    ├── bird1.png
    ├── bird2.png
    ├── bird3.png
    └── pipe.png
```

The image filenames and folder structure must match the paths used in `main.py`.

## Installation

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Create and activate a virtual environment (recommended):

   ```bash
   python -m venv .venv
   ```

   On Linux:

   ```bash
   source .venv/bin/activate
   ```

   On Windows:

   ```powershell
   .venv\Scripts\activate
   ```

4. Install Pygame Community Edition:

   ```bash
   python -m pip install pygame-ce
   ```

## Run the Game

From the project directory, run:

```bash
python main.py
```

## Controls

| Action | Control |
| --- | --- |
| Start the game | Click the mouse |
| Make the bird flap | Left mouse button |
| Restart after game over | Click the restart button |
| Quit | Close the game window |

## How to Play

1. Click to start.
2. Click to make the bird flap and rise.
3. Avoid the pipes and the ground.
4. Pass through pipe gaps to increase your score.
5. If you collide with a pipe or the ground, the game ends. Click the restart button to try again.

## Built With

- Python
- Pygame Community Edition

## What I Learned

This project is a practical way to explore:

- Game loops and frame-rate control
- Sprite classes and sprite groups
- Keyboard/mouse input handling
- Collision detection
- Basic physics using velocity and gravity
- Image animation and transformations
- Random pipe generation
- Score tracking and game-state management

## Future Improvements

- Add sound effects and background music
- Add a high-score system
- Add keyboard controls
- Improve the start and game-over screens
- Add difficulty progression

---

Made as a Python game development project.
