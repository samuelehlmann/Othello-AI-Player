# Othello-AI-Player

UPLOADING SOON

I made this program for my artificial intelligence course in Fall 2019, and I received all possible points for it. Its purpose is to make a program which could play the game othello using AI methods.

The stipulations for the assignment were:
* It must implement the game of Othello correctly and allow two humans to play it against each other
* It must implement the minimax algorithm to play othello, with an optional debug mode
* It must implement alpha-beta pruning for the minimax algorithm

Additionally, if it can reliably beat a human who is trying to win, bonus points were awarded.

In addition, on top of these requirements (and not for the receipt of bonus points), I added the following functionality.
* The Monte Carlo tree search, which is limited by a user defined time limit (note that it needs a large time limit for reasonable results)
* A player that randomly chooses moves (albeit, mainly for testing purposes)
* The ability for the minimax player to use different heuristics, which can be selected by the user, with two included in the program:
  * A simple heuristic one which only does the sum of the pieces
  * A more complex heuristic that attempts to calculate the number of "safe" spaces (i.e, spaces that cannot be lost)
