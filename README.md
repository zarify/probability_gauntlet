# Probability Gauntlet

A single-page educational game for practicing probability concepts.

## Description

Students navigate a board by rolling dice and making probability-based decisions at challenge gates. The game rewards optimal probability choices and penalizes poor ones through score adjustments.

## Features

- Three randomness sources: dice (2d6), standard playing cards, and token bag
- Eight challenge gates with shuffled conditions each game
- Score tracking with optimal choice bonuses/penalties
- Visual probability statistics after each challenge
- Persistent high score tracking

## Usage

Open `index.html` in a web browser. No server or external dependencies required.

## Game Rules

1. Roll a die to move forward on the board
2. At challenge gates, choose between three options (dice roll, card draw, or token pull)
3. Each option has a success condition - calculate which has the highest probability
4. Pass the challenge to stay in place; fail to move back 2 squares
5. Choosing the optimal probability reduces your score by 1; sub-optimal choices add 1
6. Reach square 25 to finish - lowest score wins

## Technical Details

- Pure HTML/CSS/JavaScript
- No build process or dependencies
- Runs entirely client-side
- Uses localStorage for high score persistence
