# Pong Game

This is a Python implementation of the classic Pong game using the `turtle` module. The game features paddles, a bouncing ball, and a scoring system. It's a fun project to learn about basic game mechanics and the `turtle` module in Python.

## Features
- Two paddles controlled by the keyboard.
- A ball that bounces off walls and paddles.
- A scoring system to keep track of points for each player.
- Smooth animations using `turtle.Screen`.

## How to Play
1. Run the Python script to start the game.
2. Control the paddles:
   - **Right Paddle:**
     - Move Up: Press the `Up` arrow key.
     - Move Down: Press the `Down` arrow key.
   - **Left Paddle:**
     - Move Up: Press the `W` key.
     - Move Down: Press the `S` key.
3. Prevent the ball from passing your paddle. If the ball crosses your side, the opponent scores a point.
4. The game continues indefinitely or until you exit.

## Prerequisites
- Python 3.x

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pong-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pong-game
   ```
3. Ensure all required files are present:
   - `main.py`
   - `paddle.py`
   - `ball.py`
   - `score_board.py`

## Running the Game
Run the `main.py` file using Python:
```bash
python main.py
```

## File Structure
```
.
├── main.py          # Main script to run the game
├── paddle.py        # Paddle class implementation
├── ball.py          # Ball class implementation
├── score_board.py   # Scoreboard class implementation
```

## Gameplay Preview
![Pong Game Demo](https://github.com/nishnarudkar/PongGame/blob/main/Game_Preview.png)  


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributions
Contributions are welcome! If you'd like to improve this project, feel free to submit a pull request.

## Acknowledgments
- Inspired by the classic Pong game.
- Built with the `turtle` module in Python.

---
Enjoy the game! 🎮
