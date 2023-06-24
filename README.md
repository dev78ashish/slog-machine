# Slot Machine Game

This is a simple command-line slot machine game implemented in JavaScript.

## Game Description

The game allows players to deposit money, place bets on a configurable number of lines, and spin the reels. The objective is to match symbols on the lines and win credits based on the symbol values. Players can continue playing until they run out of money or choose to stop.

## How to Play

1. Run the script using Node.js.
2. Enter a deposit amount to start the game.
3. Specify the number of lines to bet on (1-3).
4. Enter the bet amount per line.
5. The reels will spin and display the results.
6. Winnings will be calculated based on the matched symbols and added to the balance.
7. The player can choose to play again or exit.

## Prerequisites

- Node.js installed on your machine.

## Instructions

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/slot-machine-game.git

1. Navigate to the project directory:
   ```shell
   cd slot-machine-game

2. Install the dependencies:
   ```shell
   npm install

3. Run the game:
   ```shell
   node index.js

## Customization
The game can be customized by adjusting the following parameters in the index.js file:

symbols_count: Define the count of symbols (A, B, C, D) available in the game.
symbol_values: Assign values to the symbols (A, B, C, D).
ROWS: Specify the number of rows in the slot machine.
COLS: Specify the number of columns in the slot machine.
Feel free to modify these parameters to create your own variations of the game.
