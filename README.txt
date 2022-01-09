This game is called Bingo and it is created using Unix and bash. A player can play
the game by calling the game and providing a "card" as a command-line input.
The card must be a file which has six lines in total. The first line contains
an integer which is a seed to be used in random variable generation.
The following five lines form a 5X5 matrix of integers. The program will then generate
random numbers within proper ranges and check if they exist among the card numbers.
If they do, they get marked on the card. A user wins when a row, a column, or all four corners
are marked.