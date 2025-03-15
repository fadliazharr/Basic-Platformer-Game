# Basic-Platformer-Game

You can try the game in the link below: 
https://fadliazharr.github.io/Basic-Platformer-Game/

This project is a simple platformer game that demonstrates the principles of Object-Oriented Programming (OOP) using JavaScript. It features a player-controlled character that can move left and right, jump, and reach checkpoints placed throughout the level. The game incorporates gravity, collision detection with platforms, and a checkpoint system that tracks progress.

How the Game Works
1. **Start Screen** - When the game loads, a start screen appears with a title, instructions, and a 'Start Game' button. Pressing the button begins the game.
2. **Player Movement** - The player can move using the left and right arrow keys and can jump using the spacebar.
3. **Platforms** - The player must jump between platforms to progress through the level.
4. **Checkpoints** - The game has checkpoints that the player must reach. Upon reaching a checkpoint, a message is displayed.
5. **Final Checkpoint** - Once the final checkpoint is reached, the game stops the movement, and a completion message appears.

Technologies Used
- **HTML**: Provides the game structure, including a start screen and canvas element for rendering.
- **CSS**: Styles the start screen, buttons, and game elements for a visually appealing interface.
- **JavaScript**: Handles game logic, player movement, collision detection, and checkpoint tracking.

Key Features and Implementation
- **Canvas Rendering**: The game is rendered using the HTML5 Canvas API, allowing smooth animations.
- **Gravity Simulation**: The player's vertical movement is affected by gravity, making jumps realistic.
- **Collision Detection**: The player can land on platforms and cannot fall through them.
- **Checkpoint System**: Each checkpoint is programmed to be activated only when the previous one has been reached, ensuring progression.
- **Event Listeners for Controls**: Keydown and keyup events handle movement, ensuring a responsive control system.

How to Play
1. Click the 'Start Game' button to begin.
2. Use the arrow keys to move left and right.
3. Press the spacebar to jump onto platforms.
4. Reach the yellow checkpoints to progress.
5. Continue until you reach the final checkpoint.

Expected Output
- The player starts at the beginning of the level.
- As the player moves, platforms and checkpoints appear.
- Reaching a checkpoint triggers a message.
- On reaching the final checkpoint, the game displays a completion message and stops movement.

