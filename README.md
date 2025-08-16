# 🎰 Slot-Machine

A simple **command-line based slot machine game** written in JavaScript (node.js)
Players can enter a certain amount of money to begin playing, by placing bets across the lines of the slot machine, "spin" the slots, and be awarded on a win and loss on a losing bet

## Features
- **Deposit Money** to start playing
- Choose **1 to 3** to bet on hitting the same symbol
- **Custom betting system**
  - Place a total bet amount.
  - The bet is split evenly between the amount of lines the users betted on
- Randomized **spinning of the slots** with symbols of A, B, C, D
-  Each symbol has a random payout multiplier:
  -  A -> 5x
  -  B -> 4x
  -  C -> 3x
  -  D -> 2x
- **Winning system**
  - Match all your symbols based on the amount of lines you betted to hit
- Keeps track of your **balance** while playing until you run out of money
- Option to **play again** after each round

## 🛠️ Programming/languages used
- **JavaScript (node.js)**
- **prompt-sync** for command-line input

## 📂 Project Structure
- slotMachine.js # Main game file
- README.md # Documentation
- package.json # Dependencies

## ▶️ How to Play
1. Clone this repo
2. Install the dependencies (npm install prompt-sync)
3. Run the game on the slotMachine.js file
4. Follow the prompts/instructions within the terminal to play
