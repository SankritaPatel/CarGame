# Sankrita's Car Game

This is a simple car game developed using Pygame, where the player controls a car and tries to avoid colliding with other cars on the road.

## How to Play

1. **Installation**: Ensure you have Python and Pygame installed on your system. You can install Pygame using pip:

```
pip install pygame
```

2. **Clone the Repository**: Clone this repository to your local machine.
```
git clone https://github.com/SankritaPatel/CarGame.git
```
3. **Run the Game**: Navigate to the directory where the game files are located and run the Python script ```python car_game.py```.

4. **Controls**:
- Use the left arrow key (←) or 'A' key to move the player's car to the left lane.
- Use the right arrow key (→) or 'D' key to move the player's car to the right lane.
- Avoid colliding with other cars on the road.

5. **Scoring**: The game speeds up every 2000 iterations, making it progressively challenging. The player's score increases as they survive longer without colliding with other cars.

6. **Game Over**: The game ends when the player's car collides with another car. The player can restart the game by running the script again.

## Game Components

- **Player Car**: Represented by a car image, controlled by the player.
- **Enemy Cars**: Represented by another car image, moving down the screen in different lanes.
- **Road and Lanes**: The game screen consists of a road with marked lanes where the player and enemy cars move.

## Files Included

- `car_game.py`: Main Python script containing the game logic.
- `car.png`: Image file for the player's car.
- `otherCar.png`: Image file for the enemy car.
- `README.md`: Documentation file providing instructions and information about the game.

## Dependencies

- Python 3.x
- Pygame library

## Credits

- Developed by [Sankrita Patel]

## License

This project is licensed under the [MIT License](LICENSE).
