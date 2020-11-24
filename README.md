<h1>TIC TAC TOE Implementation</h1>

<p align="center">
	<img src="gameWindow.PNG"></img>
</p>

<h2> Introduction </h2>

	TIC TAC TOE (also known as Noughts and Crosses or Xs and Os) is a simple game for two players, X and O , who
	take turns marking the spaces in a 3x3 grid.The player who succeds in placing three of their marks in a 	
	horizantal ,vertical or diagonal row wins the game. The basic idea is to use two-dimensional array (board) 	   
	to maintain the game board. Cells in this array store values that indicate if that cell is empty or stores 	      
	an X or O. In the code implemented the cells in the board array are intergers 2 and 1 representing X and O.
	The game operates in two modes.of 
		Mode 1 : Human vs Human where both the players are human.
		Mode 2 : Human vs Computer where the opponent is Computer(Minimax AI Algorithm).
		
## How to Play the Game :
	Choose the mode of the game in the GameWindow.
	Both the players choose either X or O to mark their cells.
	There will be a 3×3 grid UI implemented using swing.
	The player who chose O begins to play first.
	He clicks on the cell where he wishes to place O.
	If the player is a computer he automatically chooses a cell using Minimax Algorithm.
	Now, both O and X play alternatively until any one of the two wins.
	Winning criteria: Whenever any of the two players has fully filled one row/ column/ diagonal with his symbol 	     
	(X/ O), he wins and the game ends.
	If neither of the two players wins, the game is said to have ended in a draw
	
## MiniMax Algorithm
	Minimax is a decision-making algorithm, typically used in a turn-based, two player games. The goal of the algorithm is to find the optimal next move.

In the algorithm, one player is called the maximizer, and the other player is a minimizer. If we assign an evaluation score to the game board, one player tries to choose a game state with the maximum score, while the other chooses a state with the minimum score.

In other words, the maximizer works to get the highest score, while the minimizer tries get the lowest score by trying to counter moves.

It is based on the zero-sum game concept. In a zero-sum game, the total utility score is divided among the players. An increase in one player's score results into the decrease in another player's score. So, the total score is always zero. For one player to win, the other one has to lose.
