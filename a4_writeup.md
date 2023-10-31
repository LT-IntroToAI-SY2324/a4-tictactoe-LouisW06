# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
It was difficult to get the code to not check for Xs and Os that went off the side of the board. Like if there were Xs in spots 2,3, and 4, it would say three in a row, even though not all the Xs are on the same row as spot 2 is in row one and spots 3 and 4 are row two.
2. Explain how you would add a computer player to the game.
I would add a computer player by having a program use a while loop to check through the list and then use if statements to find whether or not it has an X, O, or *, and then fill the spot with whichever team it is on.
3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
I suppose you could have the computer check what the spots on either side of it are filled with and then make a move when it finds two variables on either side that match, so it can fill in the middle with three in row. However, I understand it is probably more complicated to do than just that.
