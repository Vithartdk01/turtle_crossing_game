#  Turtle Crossing Game
Guide a turtle across a busy road filled with moving cars. 
Each level increases the speed of the cars, making the game more challenging and exciting as you progress. 
The goal is to help the turtle reach the other side safely while avoiding collisions.
# How the Code Works?
- Screen Setup: Creates a 600x600 pixel window and disables automatic screen updates for smoother animation.
- Object Creation:
    - Player: Represents the turtle the user controls.
    - CarManager: Handles creating and moving car objects.
    - Scoreboard: Manages and displays the player's level and game over message.
- User Input: Listens for the "Up" arrow key. When pressed, the player's turtle moves upward.
- Main Game Loop: Repeats as long as the game is active:
     - Waits 0.1 seconds between frames for consistent speed.
     - Updates the screen to reflect all changes.
     - Creates new cars and moves all existing cars forward.
- Collision Detection: Checks if any car is close to the player (within 20 pixels). If a collision is detected, the game ends and "Game Over" is displayed.
- Level Progression:
     - If the player reaches the finish line at the top:
          - The player is reset to the starting position.
          - Car speed increases (making the next level harder).
          - The scoreboard updates to show the new level.
- Exit: The game window closes when clicked after the game ends.

