# Snake Game

A classic Snake game implementation written in Rust using the Piston game engine.

## Description

This is a simple Snake game where the player controls a snake that moves around the screen, eating food to grow longer while avoiding collisions with walls and its own body. The game automatically restarts after a game over.

## Prerequisites

- Rust (latest stable version)
- Cargo (comes with Rust)

## Dependencies

- `piston_window` (0.117.0) - For graphics and window management
- `rand` (0.8) - For random number generation (food placement)

## Installation

1. Clone or download this repository
2. Navigate to the project directory:
   ```bash
   cd snake
   ```
3. Build the project:
   ```bash
   cargo build --release
   ```

## Running the Game

To run the game, use:
```bash
cargo run
```

Or run the optimized release version:
```bash
cargo run --release
```

## Controls

- **Arrow Keys** (Up, Down, Left, Right) - Control the snake's direction
- **ESC** - Exit the game

## Game Rules

1. Use the arrow keys to control the snake's movement
2. Eat the red food squares to grow the snake longer
3. Avoid hitting the walls or the snake's own body
4. The game automatically restarts after a collision
5. The snake cannot move in the opposite direction of its current movement

## Project Structure

```
src/
├── main.rs    - Entry point and main game loop
├── game.rs    - Game logic and state management
├── snake.rs   - Snake entity implementation
└── draw.rs    - Rendering and drawing utilities
```

## Features

- Smooth snake movement with automatic progression
- Random food generation that avoids snake body
- Collision detection with walls and self
- Automatic game restart after game over
- Prevention of reverse direction movement
- Simple and intuitive arrow key controls

## Author

Warushika Wijayarathna

## License

This project is open source. Feel free to modify and distribute as needed.

## Contributing

Feel free to fork this project and submit pull requests for any improvements or bug fixes.
