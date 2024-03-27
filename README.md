# Sankrita's Car Game

Welcome to Sankrita's Car Game, a simple Pygame-based game where you navigate a car through traffic on a busy road. Can you avoid collisions and survive as long as possible?

## How to Play

1. **Installation**: Ensure you have Python and Pygame installed on your system.
```
pip install pygame
```
   
2. **Clone the Repository**: Clone this repository to your local machine.
```
git clone https://github.com/SankritaPatel/CarGame.git
```
3. **Run the Game**: Navigate to the directory where the game files are located and run the Python script `cargame.py`.
```
python cargame.py
```

4. **Controls**:
   - Use the left arrow key (←) or 'A' key to move the car to the left lane.
   - Use the right arrow key (→) or 'D' key to move the car to the right lane.
   - Avoid collisions with other cars on the road.

5. **Scoring**: The game speeds up every 2000 iterations, making it progressively challenging. Survive as long as possible to achieve a high score.

6. **Game Over**: The game ends when your car collides with another car. You can restart the game by running the script again.

## Features

- **Player Car**: Control a car using keyboard inputs to navigate through traffic.
- **Enemy Cars**: Avoid collisions with randomly generated enemy cars moving in opposite lanes.
- **Dynamic Difficulty**: The game becomes faster and more challenging over time.
- **Scoring System**: Compete with yourself or others to achieve the highest score.

## Files Included

- `cargame.py`: Main Python script containing the game logic.
- `car.png`: Image file for the player's car.
- `otherCar.png`: Image file for the enemy car.

## Dependencies

- Python 3.x
- Pygame library

## Screenshots

![Game Screenshot](https://github.com/SankritaPatel/CarGame/blob/main/game.png)

## Credits

- Developed by [Sankrita Patel]

## License

This project is licensed under the [MIT License](LICENSE).
