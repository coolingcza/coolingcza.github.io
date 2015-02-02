---
title: Description of a Couple of Items in Hilary's PSR Game
---

Item 1:
Hilary's Player objects track the moves that are made as well as the scores.  The moves
are recorded during the game playing loop (line 158 in Game class) using the Player class
method add_moves.  This record can then be reported at the end of the game by 
Game#print_move_array.

Item 2:
The output in the round winning logic branches is a lot of fun to read! :)  The logic is
very comprehensive and contains a different output for each move pair.