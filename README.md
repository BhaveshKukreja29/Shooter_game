# Space Shooter Game

A simple 2D space shooter game implemented in C using the BGI (Borland Graphics Interface) library.

## Description

This game is a classic space shooter where the player controls a spaceship at the bottom of the screen. The objective is to shoot down enemy ships while avoiding them. The game ends when the player reaches a score of 9 or when an enemy ship reaches the bottom of the screen.

![Screenshot 2024-09-29 023646](https://github.com/user-attachments/assets/13482b7b-7add-4ada-9b6b-c45a3da6b6b8)

![Screenshot 2024-09-29 023821](https://github.com/user-attachments/assets/4e3b1bd5-f822-483e-871c-9f76a12b93a8)

![Screenshot 2024-09-29 023709](https://github.com/user-attachments/assets/86e14eda-ff8c-4d0e-809a-d6afb7c5ad7a)

## Features

- Player-controlled spaceship
- Enemy ships that move downwards
- Shooting mechanism
- Score tracking
- Victory and defeat conditions

## Requirements

- Turbo C++ or a compatible C compiler with BGI support
- DOS environment or DOSBox for modern systems

## How to Run

1. Ensure you have Turbo C++ installed or set up DOSBox with Turbo C++.
2. Copy the source code into a new file with a `.c` extension (e.g., `spaceshooter.c`).
3. Compile and run the program in Turbo C++.

## Controls

- Left Arrow: Move spaceship left
- Right Arrow: Move spaceship right
- Up Arrow: Shoot

## Game Rules

- Shoot down enemy ships to increase your score.
- The game ends in victory when you reach a score of 9.
- If an enemy ship reaches the bottom of the screen, you lose.

## Code Structure

- `main()`: Game loop and menu
- `game()`: Main game function
- `handle()`: Handles user input
- `updateWorld()`: Updates game state
- `movebullet()`, `moveenemy()`: Move game objects
- `detect()`: Collision detection
- `drawspaceship()`, `drawenemy()`, `drawbullet()`: Render game objects
- `updateScore()`: Display current score
- `celebrate()`, `death()`: End game screens

## Notes

- This game uses the BGI library, which is specific to older C compilers like Turbo C++.
- The game assumes a specific screen resolution and may need adjustments for different displays.

## Future Improvements

- Add levels with increasing difficulty
- Implement power-ups
- Add sound effects and background music
- Create a high score system
- Add explosions

Feel free to modify and expand upon this game! Happy coding and gaming!
