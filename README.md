Tic-Tac-Toe Game
* Overview
This project is a simple yet engaging web version of the classic Tic-Tac-Toe game. Two players (X and O) take turns clicking on a 3×3 grid to try to get three of their marks in a row — horizontally, vertically, or diagonally.
Built entirely using HTML, CSS, and JavaScript, it runs in any modern browser with no additional setup or dependencies.

* Game Logic
- Players: Alternates between Player X and Player O.
- Winning Conditions: If a player lines up 3 marks in any direction, they win.
- Draw: If all cells are filled and no winner, it's a tie.
- Restart: The "Play Again" button resets the game for a new round.

* File Structure
All content is packed into a single HTML file with embedded styles and script for simplicity.
* HTML
- Creates the structure of the game: title, message display, board, and restart button.
- The board contains 9 individual divs representing the cells, each with a data-cell attribute.
- Each cell contains an empty <span> for rendering X or O.
  * CSS
- Gives the page a soft gradient background and centers the board.
- Uses a responsive grid layout for the board and cells.
- Adds hover effects and disables clicks once a cell is taken.
- Responsive design adapts fonts and spacing for smaller screens.
  * JavaScript
Controls game behavior:
- startGame() initializes board state and adds click listeners.
- handleClick() manages cell marking, win/draw detection, and turn switching.
- checkWin(player) compares current cell layout against predefined winning combinations.
- isDraw() checks if all cells are filled with no winner.
- restartBtn.addEventListener('click', startGame) links the restart button to reset the board.

* How to Run
- Save the code into a file named tic-tac-toe.html.
- Open it with any web browser (Chrome, Firefox, Edge, etc.).
- Play the game by clicking on the cells.
- Click "Play Again" to restart the match.

* Enhancements You Could Add
Here are a few ideas to build on:
| Feature | Description | 
| Scoreboard | Keep track of wins/draws for each player | 
| AI Opponent | Let the user play against the computer | 
| Themes | Switch between dark/light modes or custom board styles | 
| Sound Effects | Add audio feedback for moves and wins | 



* Notes
- This version is intended for local play between two humans.

