# BattleshipGameProject
Battleship

## Overview
Battleship is a classic Java game that brings the popular board game Battleship to life using Karel the Robot. The game provides a fun and interactive way to locate and sink hidden ships on the game board. You control Karel the Robot and use arrow keys to navigate while using the space bar to fire "shots" at enemy ships represented by other robots.

## How to Play
1. Download or clone the following Java files to your project folder:
   - `Battleship.java`: The main class that incorporates and uses code from other classes.
   - `EasySound.java`: A utility class to add sound effects.
   - `Player.java`: A class that allows the user to control the robot and "shoot" ships.
   - `Ship.java`: A class that adds all the robots representing the ships to the game board.
2. Ensure that you have the necessary sound files (`connect.wav`, `noConnect.wav`, `winGame.wav`, `loseGame.wav`, and `hitBefore.wav`) in your project folder to enable sound effects during gameplay.
3. Compile and run the `Battleship.java` file using a Java compiler.
4. In the game window, use the arrow keys (UP, DOWN, LEFT, RIGHT) to navigate Karel the Robot on the game board.
5. Press the SPACE bar to fire a "shot" and try to hit the hidden ships represented by other robots.
6. When Karel hits a ship, you'll hear a "HIT!" sound effect and the ship section will be marked with a beeper. The game will keep track of your hits and the remaining ship sections.
7. If you hit all the ship sections, the game will announce that you won, and the board will change to a victory scene. If you run out of attempts (60 attempts), you lose the game.

## Game Features
- **Real-time Gameplay**: Battleship uses Karel the Robot's graphics and allows you to play the game in real-time, providing an engaging gaming experience.
- **Sound Effects**: The game comes with various sound effects to enhance gameplay. You'll hear HIT and MISS sounds as you fire shots at enemy ships.
- **Game Progress Tracking**: The game tracks your hits, remaining attempts, and the number of ship sections you've sunk.
- **Victory Scene**: Celebrate your victory with a special victory scene when you successfully sink all the hidden ships.

## Game Rules
- The game board is a grid of size 10x10, with ships represented by robots placed at specific locations on the grid.
- Navigate Karel the Robot to fire shots at enemy ships. Use the arrow keys (UP, DOWN, LEFT, RIGHT) to move.
- When you hit a ship, it will be marked with a beeper, and you'll hear a "HIT!" sound.
- If you try to hit a spot you've already hit, the game will notify you, and you won't lose any attempts.
- You have 60 attempts to sink all the ships. If you run out of attempts, you lose the game.

## Dependencies
- The Battleship game requires Java and the Karel the Robot library to run.

## Installation
1. Clone the repository to your local machine using `git clone`.
2. Compile the Java files using a Java compiler.
3. Ensure that you have the necessary sound files (`connect.wav`, `noConnect.wav`, `winGame.wav`, `loseGame.wav`, and `hitBefore.wav`) in your project folder for sound effects.

## Credits
- The original concept of the Battleship game is a classic board game.
- The `EasySound` class is provided by Gary Litvin, the author of "Java Methods: Object-Oriented Programming and Data Structures."
- The implementation of the Battleship game and integration with Karel the Robot are created by Pranavh Joshua Vallabhaneni

## License
This project is licensed under the MIT License.
