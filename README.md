# Dig, Dig, Repeat (Mathified Version) - Game

## Overview

"Dig, Dig, Repeat (Mathified Version)" is a modified version of the original **Dig, Dig, Repeat** game, now featuring math-based challenges. In this interactive, grid-based game, the player navigates through a maze while solving math problems. The goal is to reach the designated "True Goal" block at the bottom-right corner of the grid. Along the way, players must solve math challenges after every move and avoid teleporters, which reset the player’s position.

## Features

- **Math Challenges**: 
  - Players must solve a math problem (addition, subtraction, multiplication, or division) every time they move. Incorrect answers will cost the player a life.
  
- **Teleporters**: 
  - Teleporters reset the player’s position to the starting point without losing any lives.
  
- **True Goal**: 
  - The player must reach the True Goal block (🟢) at the bottom-right corner of the grid.
  
- **Lives Management**: 
  - Players start with 3 lives ❤️ and lose a life for incorrect answers. Correct answers allow the player to continue without penalty.
  
- **Randomized Grid**: 
  - The grid is randomly generated at the start of each game, ensuring every playthrough is unique.
  
- **Timer**: 
  - Time is tracked, and the goal is to reach the True Goal as quickly as possible.

- **Responsive UI**:
  - The UI shows the number of lives remaining, elapsed time, and the current game status (such as hitting a teleporter or answering a question).

## Installation

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your browser to play the game.
   (or)
1.Open terminal where the files are saved
    ```bash
   python -m http.server
   ```
  2. Open browser and navigate to
     ```bash
     0.0.0.0:8000
     ```

### 1. Main Menu:
Upon starting the game, you will be presented with a **Main Menu**. The game includes only one mode:
- **Mathified Mode**: The player navigates through the grid while solving math problems. If the player answers incorrectly, they lose a life.

### 2. Gameplay:
- Use the arrow keys (`Up`, `Down`, `Left`, `Right`) to move the player through the grid.
- The player starts at the top-left corner of the grid (position `[0,0]`).
- Each time the player moves, a random math problem will appear. The player must answer correctly to avoid losing a life.
- Teleporters (🟣) will reset the player's position to the start of the grid without affecting the number of lives.
- The goal is to reach the True Goal block (🟢) at the bottom-right corner of the grid.
- Once the player reaches the True Goal block (🟢), the game ends, and the time taken is displayed.

### 3. UI Elements:
- **Lives**: Displays the number of lives remaining.
- **Timer**: Tracks the time spent in the game.
- **Status**: Displays the current game message, such as when the player hits a teleporter or answers a question.

### 4. Restarting the Game:
- You can restart the game by clicking the "Restart" button in the game screen or return to the **Main Menu** to start a new game.


### **Game Logic**:
- The game is built using **HTML**, **CSS**, and **JavaScript**.
- The grid is randomly generated at the start of each game, and the player must navigate it.
- The game features random placement of **Teleporters** and the **True Goal**.
- Movement is controlled using arrow keys, and each block's type is checked to update the player's state.

### **Grid Generation**:
- The grid is created dynamically in JavaScript, where each cell in the grid is either empty, a teleporter, or the True Goal block.
- The player moves across the grid by interacting with the arrow keys, and the current position is updated as the player moves.

### **UI Rendering**:
- The game uses the **Canvas API** to draw the grid, player, and other UI elements like lives and timer.
- CSS styles are used to create the **terminal-themed UI** with green and black colors to give it a retro look.
- The game screen is updated continuously, and the player's position is redrawn after every move.

## Technologies Used

- **HTML5**: Used for the basic structure of the game.
- **CSS3**: Used for styling the game interface and making it responsive.
- **JavaScript**: Used for handling the game logic, grid generation, movement, and player interaction.

## Credits

- **Developer**: [Umesh Sriraj Adabala]
- **Special Thanks**: [Level Devil Game on poki.com]

## License

This project is open-source and licensed under the [MIT License](LICENSE).

---

Enjoy playing "Dig, Dig, Repeat (Mathified Version)"! Challenge yourself to solve math problems and reach the True Goal as quickly as possible! 🕹️
