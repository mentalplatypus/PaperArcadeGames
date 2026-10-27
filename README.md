# Paper Arcade

A collection of small browser games drawn in a graph-paper style. Each game is a single HTML file with no build step and no dependencies beyond Google Fonts.

**Play:** https://mentalplatypus.github.io/PaperArcadeGames/

## Games

| Game | Folder | About |
| --- | --- | --- |
| Snake | `snake/` | Eat apples, grow longer, avoid the walls and your own tail. |
| Tic-Tac-Toe | `tictactoe/` | Play the computer or a friend on the same screen. |
| Minesweeper | `minesweeper/` | Three board sizes, flags, and best times. |
| Ruler Merge | `ruler/` | Slide equal lengths together to double them. Make a 128 cm line to win, working around the ink blots. |
| Sudoku | `sudoku/` | Three difficulty levels, pencil notes, and undo. |
| Dots & Boxes | `dots/` | Draw lines between dots and close boxes to claim them. Play the computer or a friend on 3×3, 4×4 or 5×5 boards. |

## Running locally

Open `index.html` in a browser. No server is needed.

## Adding a game

1. Create a folder next to the others with an `index.html` inside.
2. Give the game a `← All games` link to `../index.html`.
3. Add a card for it in the `<ul class="games">` list in the root `index.html`.
