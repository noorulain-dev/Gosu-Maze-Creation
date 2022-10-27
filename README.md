# Gosu-Maze-Creation
Creates a maze in the box without colliding with the walls until a path is found, using GOSU library. 

Program Features:

CELL
- have a pointer to the neighbouring cells
- Set the pointers to nil
- default is not vacant i.e is a wall.
- this stops cycles - set when you travel through a cell

GAME WINDOW
- Left click on cells to create a maze with at least one path moving from left to right.  The right click on a cell for the program to find a path through the maze. When a path is found it will be displayed in red.

SEARCH
- start a recursive search for paths from the selected cell, it searches till it hits the East 'wall' then stops. It does not necessarily find the shortest path

BUTTON CLICK
- Reacts to button press, left button marks a cell vacant
Right button starts a path search from the clicked cell

WALK
- This will walk along the path setting the on_path for each cell to true. Then draw checks this and displays them a red colour.

UPDATE
- This is a procedure i.e the return value is 'undefined'

DRAW
- Draw (or Redraw) the window. This is procedure i.e the return value is 'undefined'
