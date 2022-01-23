# MineSweeper
- The player selects the game's board size and presses a button to confirm.
- Then a function called "createTable()" is activated/
- The function initializes two variables by the gamer's selections: sizeRow and sizeCell.
and displays on the screen a table of the desired size. each cell has diffrent attributes.
In addition the function defines the size of an array called "array" as the number
of cells in the table and another array called "randomNums" size of one-fifth
of the number of cells in the table where the mines will be stored.
At the end calls the function "randomNum()".

- The function randomNum initializes the array "randomNums" in random
and different numbers. These are the places that will contain a mine.

- Once a player clicks on a cell we get to a function called "press()" with the
cell's number. The function check if this cell contains a mine if so, the game is over,
and all the cells that contain a mine will be exposed,colored red and a bomb will be written on them.
else displays the number of the mines around this cell. In case there aren't mines around
the cell will colord gray, and all the surrounding cells that do not contain a mine will be exposed.


-Once a player right clicks on a cell, the cell will be colord green and will have a suspect written on it,
another right-click will return the cell to its previous state and remove the suspicion.

Input for example:
-----------------
10, 10

Output for example:
-------------------
a board size 10*10
