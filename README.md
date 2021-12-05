# connect4
### Arhum Zafar / Winter 2021
<br>

Having recently learned about [alpha-beta pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning), I stumbled upon an application on how it can be used to speed up the time it takes certain algorithms to solve. In particular, this [video](https://www.youtube.com/watch?v=l-hh51ncgDI), by [Sebastian Lague](https://pastebin.com/rZg1Mz9G), shows how alpha beta pruning can speed up the [minimax search algorithm](https://en.wikipedia.org/wiki/Minimax), illustrated using the game of chess.
<br>
<br>
The video inspired me to create a similar AI for Connect 4. Likewise to the chess example, the AI uses alpha-beta pruning to influence the time in which the minimax algorithm takes to identify the best move possible to minimize the opponent's chance of placing 4 pieces next to one another (horizontally, vertically, & diagonally). 
<br>
<br>
The "game board" itself can be seen as a matrix. Once a player places their piece on the game board, the matrix is pooled and then convolved -- similar to the functionality of a convolutional neural net -- for the minimax algorithm to then identify the next best move.


