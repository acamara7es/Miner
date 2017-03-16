# Minesweeper

## Objective of the game

In spite of the name, the game consists in discovering all the boxes of the board that **not** contains mines, avoiding the ones they have

## How to play

- To open a box simply click on it, see that it has changed its contents by:
  - **A number** between 1 and 8: There are that number of mines near the cell.
  - **Void**: There are no mines nearby. Cells are automatically opened until "numbered" cells are found.
  - **A mine with red background**: Bad luck :( You have hit a mine and you have lost the game.
- You can lock a cell with a long press and a flag will appear. To be able to open the cell, again make a long press.
- To start a new game click on the face button.

## Game Modes
Este juego dispone de 3 niveles predefinidos diferentes y la posibilidad de crear nuevas configuraciones con las limitaciones (por cuestiones de usabilidad) que aparecen en la siguiente tabla: 

| Level  | Size | Mines | % Mines |
| --- |---|---|---|
|     Easy     |    8   |       6        |    9.375%    |
|  Intermediate   |   10   |       15       |     15%     |
|    Expert    |   12   |       30       |   20.83%    |
| Custom | 3 - 20 | 1 - 80% cells | 0.25% - 80% |

## Sounds
If you have pressed in a cell without a mine you will hear a sound that identifies the contents of the cell.
- If you hear a beep, there are an odd number of mines nearby.
- If you hear 2 beeps, there are an even number of mines nearby.
- The more mines there are, the sharper it will be. Therefore, the most tomb sounds are for 1 or 2 mines, and the sharpest for 7 or 8 mines.
- If you press on an empty cell you will hear a scale with the 4 sounds used in the previous cases (from serious to sharp).

When the game is over there is also a scale of sounds, from the most serious to the sharpest if you win, and from sharpest to the most serious if you lose.
