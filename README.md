# connascence-tictactoe

Welcome to code example where you can focus on practicing connascence. Please find the attached PDF where the connascence types are described.

## Challenge

Challenge is to create a web service to run Tic Tac Toe. it connects to our backend in the cloud to do some magic we don't know. For this, we have an idea of an interface to start with. 

We have identified the following three key actions / methods.

* void AddPlayer(name, token) -> Adds a player to the game
* ??? start(); {sleep 1 sec} -> This method calls external API in the cloud. We mimick this with a 1 second sleep.
* string Winner() -> For the client of our software, we need to return the name of the winner Base64 encoded!

There maybe some methods missing, and please add those.
If you need to change the proposed three, please discuss with facilitators.

## Tic Tac Toe rules
• X always goes first.
• Players alternate placing X’s and O’s on the board.
• Players cannot play on a played position.
• A player with three X’s or O’s in a row (horizontally, vertically, diagonally) wins.
• If all nine squares are filled and neither player achieves three in a row, the game is a draw.
