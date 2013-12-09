## TicTacToe

### Idea:
Create a simple game of TicTacToe in thimble that can take advantage of together.js for multiplayer, and localstorage for saving gameplay (or at least some stats).

The project will be created twice (a lot of the logic is reusable), first w/ a html table for the grid, the second w/ the canvas.

This will allow us to explain the differences, and reasons why you should use certain methods over others. Beginnings of moving people toward a more intermediate understanding of web development.

**Implimentation One:**  
html + css + javascript + `<table>` for grid

**Implimentation Two:**  
html + css + javascript + `<canvas>` for grid

**Best Method:**  
`<canvas>` as `<table>` is for presenting tabular data, which this game is not. It does however work, and its worth showing as it can help introduce DOM manipulation.

The game logic should be the same accross both implimentatons.
Makes:

### Complete versions:
* `<table>` based:
	* https://fuzzyfox.makes.org/thimble/tictactoe-table-version
* `<canvas>` based:
	* https://fuzzyfox.makes.org/thimble/tictactoe-canvas-version
