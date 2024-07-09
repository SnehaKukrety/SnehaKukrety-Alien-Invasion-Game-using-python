**# Alien Invasion**

Alien Invasion is a 2D shooting game where the player controls a spaceship and shoots down waves of incoming aliens. The game is built using Python and the Pygame library.

**## Table of Contents**
- [Overview](#overview)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)

**## Overview**
In Alien Invasion, the player must shoot down the aliens before they reach the bottom of the screen or collide with the player's ship. The game gets progressively more challenging as the speed and number of aliens increase.

**## Installation**

**### Prerequisites**
- Python 3.x
- Pygame library

**### Steps**
1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/alien-invasion.git
    cd alien-invasion
    ```

2. **Create and activate a virtual environment** (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate    # On Windows: venv\Scripts\activate
    ```

3. **Install the required packages**:
    ```sh
    pip install pygame
    ```

**## How to Play**

1. Run the game:
    ```sh
    python alien_invasion.py
    ```

2. **Controls**:
    - **Right Arrow**: Move the ship to the right.
    - **Left Arrow**: Move the ship to the left.
    - **Spacebar**: Fire bullets.
    - **Q**: Quit the game.

3. **Objective**:
    - Shoot down all the aliens.
    - Avoid collisions with aliens.
    - Prevent aliens from reaching the bottom of the screen.

**## Project Structure**
games/

├── alien_invasion.py # Main game file

├── settings.py # Game settings

├── ship.py # Ship class

├── bullet.py # Bullet class

├── alien.py # Alien class

└── images/

├── ship.bmp # Ship image

└── alien.bmp # Alien image

└──Screenshot.png


****## Screenshots****

Screenshot.png

****## Contributing****

Contributions are welcome! Please fork the repository and create a pull request with your changes.



