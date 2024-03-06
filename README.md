# slot-machine

Welcome to the Slot Machine Game! This simple terminal-based game allows you to experience the excitement of playing a classic slot machine right from your command line interface.

## How to Play

Installation: This game runs on JavaScript. Make sure you have Node.js installed on your machine to run the game script.

### Starting the Game:

Simply execute the provided JavaScript code in your terminal to start the game.

bash
Copy code
node project.js

## Gameplay

Upon starting the game, you will be prompted to enter a deposit amount. This is the initial amount of money you'll have to play with.
Next, you'll be asked to choose the number of lines to bet on (1-3). The more lines you choose, the higher the potential winnings or losses.
Then, you'll need to enter the bet amount per line. Make sure your bet is within the limits of your current balance and the number of lines you've chosen.
After placing your bet, the reels will spin, and the symbols will be displayed in a grid format in the terminal.
If the symbols line up across any of the selected lines, you'll win a certain amount based on the combination and your bet.
Your winnings will be added to your balance, and the game will prompt you if you want to play again.
The game continues until you run out of money or choose not to play again.

## Game Controls

Use your keyboard to enter numerical values and choices as prompted.
Follow the on-screen instructions to navigate through the game.

## Code Structure

The JavaScript code consists of several functions:

deposit(): Allows the player to make an initial deposit to start the game.
getNumberOfLines(): Prompts the player to choose the number of lines to bet on.
getBet(balance, lines): Takes the player's balance and chosen lines as input and prompts the player to enter their bet per line.
spin(): Simulates spinning the reels and generates random symbols for each reel.
transpose(reels): Transposes the reel matrix to represent the grid format of the symbols.
printRows(rows): Prints the symbols in a grid format.
getWinnings(rows, bet, lines): Calculates the player's winnings based on the symbol combinations and bet amount.
game(): The main function that orchestrates the entire game flow.

## Enjoy the Game!

Get ready to test your luck and see if you can win big in this exciting Slot Machine Game. Have fun spinning those reels and may fortune favor you!
