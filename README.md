# High-Low Game

## Overview

The High-Low Game is a simple Python game where a player guesses if their number is higher or lower than the computer's number. Points are awarded based on whether the player's guess matches the truth. The game is played over a series of rounds, and the final score is displayed at the end.

## How It Works

1. **Welcome Message**: 
   - The game starts with a welcome message and instructions.

2. **Game Setup**:
   - The game is played for a fixed number of rounds (5 in this case).
   - The player's score starts at 0.

3. **Game Loop**:
   - For each round:
     - A random number is generated for the computer.
     - A random number is assigned to the player.
     - The player is informed of their number and asked to guess if it is "higher" or "lower" than the computer's number.
     - The player's guess is checked against the actual comparison.
     - Points are awarded for correct guesses.

4. **Score Evaluation**:
   - The game evaluates the final score and provides feedback:
     - Perfect score (5 points): "Wow you played perfectly!"
     - Half points: "Good job, you played really well!"
     -Less than Half points: "Better Luck Next Time"

5. **End of Game**:
   - A final thank you message is displayed once all rounds are completed.


