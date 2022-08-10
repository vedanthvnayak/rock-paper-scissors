# rock-paper-scissors
vs computer python code

The familiar game of Rock, Paper, Scissors is played like this: at the same time, two players display one of three symbols: a rock, paper, or scissors.
A rock beats scissors, scissors beat paper by cutting it, and paper beats rock by covering it.
In this simulation, the computer has two different strategies that it can follow.

Rock, paper, scissors is an example of a zero-sum game without perfect information. Whenever one player wins, the other loses.
We can express this game using a payoff matrix that explains what one player gains with each strategy the players use. In the payoff matrix below, the rows represent player 1's possible strategies while the columns represent player 2's possible strategies.
1 represents a win for player 1, 0 a tie, and -1 a loss for player 1. So, for instance, the upper left entry is a 0 because if both players display rocks, they tie. 
The upper middle entry is a -1 because if player 1 displays a rock and player 2 displays paper, player 2 wins, and therefore, player 1 loses.

The computer's programmed strategies behaved very differently. In the first strategy, the computer chose its first four moves randomly and then cycled through these moves for the rest of the game.
If you were able to discover this strategy, it was easy to exploit it to continually beat the computer. This illustrates the pitfalls of a determined strategy. Often, an opponent who discovers your strategy can easily beat you.
In the second strategy, the computer simply chose randomly with an equal probability for each object. Even if you could tell that this was the computer's strategy, there was no way for you to use this to beat the computer consistently.
