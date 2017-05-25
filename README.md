Let's practice from an existing codebase.

This repository contains the code for existing tic tac toe game programming in JavaScript using React. You can see it running [here](https://codepen.io/susir/pen/PmLvmY).

You'll be adding a feature to this game.

This tic-tac-toe game currently:

* lets you play tic-tac-toe
* indicates when one player has won the game
* stores the history of moves during the game

### Setting up

* Fork and clone this repository.

* You can run this with `npm start` from inside the `tictactoe` directory.

### Task

Your job is to allow players to jump back in time to see older versions of the game board.

Each move in the move list should be a link to jump back to that move. If you click any move link, the board should immediately update to show what the game looked like at that time.

Also, update `handleClick` to be aware of `stepNumber` when reading the current board state so that you can go back in time, then click in the board to create a new entry.

> Hint: It's easiest to `.slice()` off the extra elements from history at the very top of `handleClick`.

You can see the desired solution here. (link)

- Note that the steps past the one you jump to do not need to disappear off the list. That is to say, from this:
Clicking step 6 takes us to this:

The board is reset, but moves 7-10 are still visible in the move list until a new move is made.


### <<< hints about state >>>


## Solution

Solution code is provided in the solution_src folder. Please give this your best go before looking! A changelist is also provided in that folder with a brief explanation.

This project was based off this Facebook tutorial. Click inside the link to see a step by step tutorial of building out this tic tac toe app.

*NOTE* The walk through for this question is also in this tutorial (near the end), so don't look until you've given it a thorough try!

https://facebook.github.io/react/tutorial/tutorial.html
