# PONG Game using Python and Turtle

This is a simple implementation of the classic game PONG using Python and Turtle graphics library. The game is created using object-oriented programming concepts.

## Game Rules

Two players control paddles on opposite sides of the screen. The objective is to use the paddles to hit a ball back and forth between each other without missing it. A player scores a point when the other player misses the ball. The first player to reach a certain number of points (usually 11) wins the game.

## How to Play

- Player 1 uses the "W" and "S" keys to move the paddle up and down, respectively.
- Player 2 uses the up and down arrow keys to move the paddle.
- The game starts with the ball in the center of the screen, and it will automatically move towards one of the players.
- If a player misses the ball, the other player scores a point and the ball resets in the center of the screen.
- The game ends when one player reaches the winning score.

## How to Run

- Make sure you have Python 3 installed on your machine.
- Clone the repository to your local machine.
- Open a terminal and navigate to the directory where the repository is located.
- Run the command `python main.py` to start the game.

## How it Works

The game is created using object-oriented programming concepts. There are four classes:

- `Ball`: represents the ball in the game. It has properties like position, velocity, and size, and methods for updating its position and bouncing off walls and paddles.
- `Paddle`: represents a player's paddle. It has properties like position, size, and speed, and methods for moving up and down and checking for collisions with the ball.
- `Scoreboard`: represents the score for each player. It has properties like font size and color, and methods for updating and displaying the score.
- `Game`: represents the game itself. It has properties like the window size and the winning score, and methods for updating the game state and handling input.

The `main.py` file creates an instance of the `Game` class and starts the game loop, which updates the game state and draws the graphics on the screen. The game loop runs at a fixed framerate using the `turtle.ontimer()` method.

## Dependencies

- Python 3
- Turtle graphics library (included in standard Python library)

## Credits

This game was created by @pandeysarvagya as a fun programming exercise. Feel free to modify and use the code for your own projects.
