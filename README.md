# Car Game - Pygame

A simple car racing game built using Pygame, where the player controls a car on a three-lane road, dodging other vehicles as they appear. The game gets progressively more difficult as the player's score increases, with vehicles moving faster as more cars are passed.

## Features
- **Three-lane Racing:** The player can switch between three lanes to avoid other vehicles.
- **Dynamic Difficulty:** As the player's score increases, the speed of the game increases.
- **Collision Detection:** Game ends upon collision with other vehicles.
- **Score Tracking:** Keeps track of the number of vehicles passed.
- **Crash Animation:** Displays a crash image when a collision occurs.
- **Replay Option:** After game over, the player can choose to replay or quit.

## How It Works
The game window is set at 500x500 pixels with a central road having three lanes. The player controls a car starting in the middle lane. Cars appear randomly in any of the three lanes, and the player has to avoid collisions by switching lanes using the left and right arrow keys.

The game ends if the player's car collides with another vehicle, either from the side (lane changing) or head-on. After a crash, a game-over message is displayed, and the player is prompted to replay or quit the game.

## Installation
To run this game on your local machine, follow these steps:

1. **Install Python:** Ensure that Python is installed on your system. You can download it from the official site: [Python.org](https://www.python.org/downloads/).

2. **Install Pygame:** This game uses the Pygame library. To install Pygame, run:
   ```bash
   pip install pygame
   
3. Clone this Repository
```bash
  https://github.com/skjawadahmed/car-game.git.git
  cd car-game
```

5. Click on app.py file

4. Run this command in terminal
```bash
  python car_game.py
```
ENJOY GAMING!

#Screenshots
![Screenshot 2024-09-11 232615](https://github.com/user-attachments/assets/91338637-1691-417e-b207-d70b051bb583)
![Screenshot 2024-09-11 232720](https://github.com/user-attachments/assets/8d8d9fbc-4f3c-4f30-b78f-238442f81155)
