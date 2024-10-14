In this task I implemented the game 2048.

HTML and CSS are already written. The basic structure of the game class is also already written. I extended it with my own methods. Required methods: constructor with initialState() parameter, getState(), getScore(), getStatus(), moveLeft(), moveRight(), moveUp(), moveDown(), start(), restart().

The game board is 4 x 4. Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n. The player can move the cells with the keyboard arrows. All numbers must be moved in the chosen direction until all empty cells are filled. 2 equal cells must be merged into a double number. A merged cell cannot be merged twice in one move. A move is possible if at least one cell is changed after the move. After a move, a random empty cell will show 2 or 4. The probability of 4 is 10%. When any cell shows 2048, a victory message will appear. If there are no more moves available, then a game over message will be shown. The game start message will disappear when the game starts. The "Start" button changes to "Restart" after the first move. The "Restart" button resets the game to the initial state. The score increases with each move. The score increases by the sum of all the combined cells.

The game consists of 2 main parts:
- game logic, written in the src/modules/Game.class.js module, which exports the game class;
- game user interface, written in src/index.html with the main.js script, which uses an instance of the Game class.


- [DEMO LINK](https://vneholiuk.github.io/2048-portfolio-project/)
- [MOCK-UP](https://play2048.co)
