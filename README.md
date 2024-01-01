# Snake_Game
CS61C Project: Creating a Snake Game (snek) 

A snake game can be represented by a grid of characters. The grid contains walls, fruits, and one or more snakes. 
The grid has the following special characters:

// denotes a wall. (space character) denotes an empty space. * denotes a fruit.
wasd denotes the tail of a snake.
^<v> denotes the body of a snake.
WASD denotes the head of a snake.
x denotes the head of a snake that has died.
Each character of the snake tells you what direction the snake is currently heading in:

w, W, or ^ denotes up
a, A, or < denotes left
s, S, or v denotes down
d, D, or > denotes right
At each time step, each snakes moves according to the following rules:

Each snake moves one step in the direction of its head.
If the head crashes into the body of a snake or a wall, the snake dies and stops moving. When a snake dies, the head is replaced with an x.
If the head moves into a fruit, the snake eats the fruit and grows by 1 unit in length. Each time fruit is consumed, a new fruit is generated on the board.
