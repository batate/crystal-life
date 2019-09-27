# crystal-life
Conway's game of life in Crystal

[Conway's Game of Life ](https://en.wikipedia.org/wiki/Conway's_Game_of_Life) is less of a game and more of a list of processing rules that works on a grid. Here's the overview of the grid. 

- The game is played on a grid of squares. 
- Cells are either on or off. 
- A cell's neighbors are squares that touch a square, and diagonal neighbors are included. 
- One grid is called a generation. One generation is used to compute the next generation. 

These are the rules to compute the next generation. 

- If a live cell has more than three neighbors, in the next generation, it will die of overcrowding. 
- If a live cell has fewer than two neighbors, in the next generation, it will die of loneliness. 
- If an empty cell has exactly three neighbors, it will come to life in the next generation. 
- All other cells will stay the same in the next generation. 

To load this code, install Crystal and run `crystal play` from the directory with this read.me. 


