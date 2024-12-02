# Water-Sort
## Algorithm:
The code is a Python script that uses the Pygame library to create a game called "Water Sort". The game involves
sorting colored liquids in tubes.
The script initializes Pygame, sets up the game window, defines game parameters such as tube colors, and creates
functions for generating the initial game state, drawing the tubes on the screen, calculating moves, and checking for
victory conditions.
The game logic involves selecting a tube, selecting a destination tube, and then moving the top color in the selected
tube to the destination tube if certain conditions are met (e.g. the destination tube is not full and the color on top of the
destination tube matches the color being moved). The game loop runs continuously, updating the screen, handling user
input, and checking for victory conditions.

## Steps of algorithm:
1. Import necessary libraries: The code imports the "copy", "random", and "pygame" libraries
to be used in the game.
2. Initialize pygame: The pygame library is initialized using the "pygame.init()" function.
3. Set up game parameters: The code sets up various game parameters such as window size,
caption, font, frames per second (fps), color choices, tube colors, initial colors, number of
tubes, new game flag, selected flag, tube rectangles, selected rectangle, and win flag.
4. Define function to generate starting state: The function "generate_start()" generates a
random starting state for the game. It randomly selects the number of tubes and assigns
colors to each tube. It returns the number of tubes and their corresponding colors.

5. Define function to draw tubes: The function "draw_tubes()" draws the tubes on the game
window based on the number of tubes and their colors. It calculates the spacing between tubes
and their positions on the window. It also highlights the selected tube rectangle.
6. Define function to calculate move: The function "calc_move()" calculates the move made by
the player. It checks if the move is valid by comparing the color on top of the selected tube with
the color on top of the destination tube. If the move is valid, it moves the color(s) from the
selected tube to the destination tube.
7. Define function to check victory: The function "check_victory()" checks if the player has
won the game by checking if all tubes are filled with exactly 4 colors of the same type.
8. Main game loop: The code enters the main game loop using a "while" loop. It handles game
events such as quitting the game, mouse clicks, and key presses. It updates the game state based
on the player's actions and redraws the game window accordingly. It also checks for game
victory conditions using the "check_victory()" function.

9. Update game display: The code updates the game display using the
"pygame.display.update()" function to reflect the changes made during the game loop.
10. Handle game over and restart: If the player wins the game, the code sets the win flag to
True and displays a victory message. If the player clicks the restart button, the code generates a
new random starting state for a new game.
11.Handle game exit: If the player closes the game window or presses the quit key, the game
loop is exited and the pygame library is uninitialized using the "pygame.quit()" function, ending
the game.

![image](https://github.com/user-attachments/assets/8b71008d-6d9d-4656-91e4-65444e06f484)

![image](https://github.com/user-attachments/assets/c2eaaaf2-0e51-426b-9e7b-f4813b2b51e6)





