# TIC-TAC-TOE-GAME

The classic Tic-Tac-Toe game (also called Noughts and Crosses) or Xs and Os is a paper-and-pencil game for two players, X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.

In this code, I've used minimax algorithm to help the computer where to go for the next move and win the puzzle.



# A BRIEF ON MINIMAX ALGORITHM
-> Mini-max algorithm is a recursive or backtracking algorithm which is used in decision-making and game theory. It provides an optimal move for the player assuming that opponent is also playing optimally.

-> Mini-Max algorithm uses recursion to search through the game-tree.

-> Min-Max algorithm is mostly used for game playing in AI. Such as Chess, Checkers, tic-tac-toe, go, and various tow-players game. This Algorithm computes the minimax decision for the current state.

-> In this algorithm two players play the game, one is called MAX and other is called MIN.

-> Both the players fight it as the opponent player gets the minimum benefit while they get the maximum benefit.

-> Both Players of the game are opponent of each other, where MAX will select the maximized value and MIN will select the minimized value.

-> The minimax algorithm performs a depth-first search algorithm for the exploration of the complete game tree.

-> The minimax algorithm proceeds all the way down to the terminal node of the tree, then backtrack the tree as the recursion.




![image](https://github.com/adisehdev/TIC-TAC-TOE/assets/97792541/b270f7d6-2f9e-4dfc-b994-069c2e3a59d6)





# TIME AND SPACE COMPLEXITY ANALYSIS

MINIMAX algorithm performs complete depth first exploration of the game tree. If the maximum depth of the tree is m (9 for Tic-Tac-Toe) and there are b (5 for Tic-Tac-Toe) legal moves at each node, then the time complexity of MINIMAX algorithm is O(bm) and the space complexity is O(m). Due to this exponential time complexity, this algorithm is impractical for games that are moderately more complex than Tic-Tac-Toe.

