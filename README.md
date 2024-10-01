# Snake-Game
## Overview
This project is a simple Snake game implemented in Python using the turtle graphics library and the freegames module. The player controls a snake that moves around the screen to eat food, growing in size each time it eats. The game ends if the snake runs into itself or the boundaries of the screen.

## Prerequisites
Before running the game, ensure that you have Python installed along with the necessary modules.

## Required Python Modules:
turtle (part of Python's standard library)
random (part of Python's standard library)
freegames (a third-party package)

## Installing freegames:
If you don't have the freegames package installed, you can install it using pip. Open a terminal or command prompt and run:

``` pip install freegames ```

## How to Run the Game
Save the game code in a file (e.g., snake_game.py).
Open a terminal or command prompt.
Navigate to the directory where your script is saved.
Run the script using the following command:

```python snake_game.py```

Once the game starts, you will control the snake with the arrow keys on your keyboard.

## Game Controls
Right Arrow Key: Move the snake right.
Left Arrow Key: Move the snake left.
Up Arrow Key: Move the snake up.
Down Arrow Key: Move the snake down.

## Game Rules
The snake moves automatically in the direction it is facing.
The player must direct the snake to eat the green square (the "food").
Each time the snake eats the food, it grows in length.
The game ends if the snake collides with the screen boundary or itself.
The snake's length is printed to the console each time it eats food.

## Code Explanation
Main Components:
vector(): A function from the freegames module used to represent the position and movement of the snake and food.

change(x, y): This function changes the direction in which the snake is moving.

inside(head): This function checks whether the snake's head is inside the game boundaries.

move(): The core game loop. It moves the snake, checks for collisions, and updates the position of the snake and food. If the snake eats the food, the food is relocated to a random position. The snake grows in size with each piece of food eaten.

## Graphics:
square(x, y, size, color): This function is used to draw each segment of the snake and the food. The size of the square is 9, and the colors change based on whether it's part of the snake or the food.

setup(): Initializes the game window with a size of 420x420 pixels and positions it on the screen.

ontimer(): This function ensures that the move() function is repeatedly called after a set delay (100 milliseconds), creating the illusion of smooth movement.

## Event Listeners:
onkey(): Links the arrow keys to the change() function to control the snake's direction.

## Additional Notes
The game runs in an infinite loop until the snake collides with itself or the boundary.
To stop the game, you can close the game window or press Ctrl+C in the terminal.

## Output:
![image](https://github.com/user-attachments/assets/641f57c7-8c59-4c03-a883-5ab0b351dde9)

![image](https://github.com/user-attachments/assets/0eaec946-d7ff-40ea-8378-14131dbbc088)



