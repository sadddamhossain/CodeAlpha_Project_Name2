# CodeAlpha_Project_Name2
# PACMAN GAME
Here are the steps to create a basic Pacman game using Python and the `pygame` library:

1. Import the `pygame` library.
2. Initialize `pygame` by calling `pygame.init()`.
3. Set up constants for the screen size, cell size, and movement speeds for Pacman and ghosts.
4. Create a class for Pacman with attributes for position, direction, and score.
5. Create a class for Ghost with attributes for position and color.
6. Define helper functions like `draw_grid` to draw grid lines on the screen and any other necessary functions.
7. Create instances of Pacman and multiple Ghost objects.
8. Generate random food positions and store them in a list.
9. Set up the game loop using `pygame.display.set_mode()` and `pygame.time.Clock()`.
10. Inside the game loop, handle events, such as quitting the game.
11. Update Pacman's and ghosts' positions based on their current directions.
12. Check for collisions with walls and other game objects (food, ghosts).
13. Handle user input to control Pacman's movement.
14. If Pacman collides with a ghost, end the game and display the score.
15. Draw the Pacman, ghosts, food, and grid lines on the screen using `pygame.draw` functions.
16. Update the display using `pygame.display.flip()`.
17. Use `clock.tick()` to limit the frame rate and control the game's speed.

Note: These steps provide a high-level overview of creating a basic Pacman game. You will need to implement the details for each step in Python code to build a working game.
