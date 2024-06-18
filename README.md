Slot Machine Game

This is a simple console-based slot machine game implemented in JavaScript. The game allows users to deposit money, place bets, and spin the slot machine to try their luck.

Features

Deposit Money: Users can deposit an amount to start playing.

Determine Number of Lines to Bet On: Users can choose how many lines to bet on (1 to 3 lines).

Collect a Bet Amount: Users place a bet for each line.

Spin the Slot Machine: The slot machine spins and displays the result.

Check If the User Won: The game checks if the user has won based on the symbols on the slot machine.

Handle Winnings or Losses: The game adjusts the user's balance based on the result of the spin.

Play Again or Exit: Users can choose to play again or exit if they run out of money.

How to Play

Deposit Money:

When prompted, enter the amount of money you want to deposit.

The game will not start until a valid deposit amount is entered.

Choose Number of Lines:

When prompted, enter the number of lines you want to bet on (between 1 and 3).

Place a Bet:

When prompted, enter the bet amount per line.

The bet amount must be valid and within your current balance.

Spin the Slot Machine:

The slot machine will spin and display a 3x3 grid of symbols.
Check Winnings:

The game will check the symbols on the lines you bet on.
If the symbols on any line match, you win an amount based on the symbol values and your bet.
Adjust Balance:

Your balance will be updated based on your winnings or losses.
Play Again or Exit:

If you have money left, you will be asked if you want to play again.
Enter 'y' to play again or 'n' to exit the game.
If your balance is zero, the game will end.
Running the Game
To run the game, you need Node.js installed on your computer. Follow these steps:

Install Node.js:

Download and install Node.js from nodejs.org.
Save the Game Script:

Save the provided game script to a file, for example, slotMachineGame.js.
Run the Game:

Open your terminal or command prompt.
Navigate to the directory where you saved slotMachineGame.js.
Run the game using the command:

bash
node slotMachineGame.js
