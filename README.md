## maze-generator
[view source code](https://github.com/dylanro/MazeGenerator)
This visualization tool uses a recursive backtracking algorithm to procedurally generate a random maze. A simple summary of the algorithm is as follows: you can imagine a squirrel that is occupied at the top left square. This squirrel chooses a random direction and moves there, removing the line separating the grid squares. This forms a path from the squirrel's origin square to its new currnt square. This process is repeated until the squirrel gets caught in a situation where it is unable to move given the conditions. Oh no! The squirrel must now backtrack until it is able to make a valid move. This process eventually creates the maze when all squares have been visited. This process also guarantees that there is a path from the start to the end of the maze (which could be the bottom right corner). This project was created in a team for a class project. Our team got experience with JavaScript, JQuery, HTML, CSS, and a few other languages and libraries.

A notable feature of the application is the starting screen. The user can change settings such as the colors of the maze, the speed of the vizualization, and the size. In addition to this, the maze generation screen itself allows the user to download a PNG image of that maze that got generated, or generate a completely new maze.
