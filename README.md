# Artillery Defense Arcade Game

Artillery Defense is a browser-based game where players defend their base by shooting down enemy paratroopers before they land. The game features various enemy types, power-up crates, and an CPU controller for automated gameplay. Aim and shoot with the mouse, it is also mobile friendly.

You can try the game at: https://www.craygen.com/artillery/

## Game Configuration

The game configuration is defined in the `GAME_CONFIG` object, which includes settings for initial lives, difficulty levels, spawn timers, entity speeds, and CPU player parameters.

The `AIController` class manages automated gameplay, including target selection, aiming, firing, and special actions. It adjusts its parameters based on the game's difficulty level.

## Code Structure

The game is written entirely in HTML, CSS and JavaScript. The JavaScript code handles the game logic, rendering, and user interactions, all graphics are created with CSS.

Key components include:

- The `GAME_CONFIG` object defines various game settings such as initial lives, difficulty levels, spawn timers, entity speeds, and AI parameters.
- The `AIController` class manages automated gameplay, including target selection, aiming, firing, and special actions.
- The `Game` class handles the main game logic, including updates, rendering, and user input handling.
- Classes such as `Cannon`, `Bullet`, `Plane`, `Airship`, `Paratrooper`, and `Crate` represent different game entities, each with their own properties and methods for updating and drawing.
- The `AudioManager` class handles sound effects for various game actions.
- The code includes event listeners for mouse and touch interactions, allowing players to control the game on both desktop and mobile devices.

## Screenshots

<img src="https://github.com/user-attachments/assets/484c621a-2b2a-4f93-9196-f7b821e5a377" alt="artillery_start" width="300">

<img src="https://github.com/user-attachments/assets/57c384b8-5f95-444f-91ae-683b2da429ca" alt="artillery_start" width="300">

## Getting Started

Clone the repository or download the single index.html file. 

## Contributing

This game was made with AI using Claude Sonnet 3.7. Feel free to submit issues or pull requests if you have any improvements or bug fixes.

## License

This project is licensed under the GPL-3.0 License.
