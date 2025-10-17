# Snake and Egg Game

This is a simple Snake and Egg game implemented using HTML, CSS, and JavaScript. The objective of the game is to control the snake to eat the egg and grow longer. The game ends if the snake collides with the walls or itself.

## How to Play

- Use the arrow keys on your keyboard to control the direction of the snake:
  - **Left Arrow**: Move left
  - **Up Arrow**: Move up
  - **Right Arrow**: Move right
  - **Down Arrow**: Move down
- The snake will grow longer each time it eats the egg.
- The game ends if the snake runs into the walls or itself.
- Click the "Restart" button to start a new game.

## Files

- `index.html`: The HTML file that contains the structure of the game.
- `styles.css`: The CSS file that styles the game canvas and button.
- `script.js`: The JavaScript file that contains the game logic.

## Setup

1. Clone the repository or download the files.
2. Open `index.html` in a web browser to start the game.

## Customization

- You can adjust the size of the game board by changing the `width` and `height` attributes of the `<canvas>` element in `index.html`.
- The speed of the game can be adjusted by changing the interval time in `setInterval(draw, 100);` in `script.js`. A smaller number will make the game faster.

## License

This project is open-source and available under the MIT License.