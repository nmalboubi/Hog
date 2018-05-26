# Hog
Develop a simulator and multiple strategies for the dice game Hog.

Implement higher-order functions, experiment with random number generators, and generate ASCII art.

In Hog, two players alternate turns trying to reach 100 points first. On each turn, the current player chooses some number of dice to roll, up to 10. She scores the sum of the dice outcomes, unless any of the dice come up a 1 (Pig out), in which case she scores only 1 point for the turn.

To spice up the game, there are three additional special rules:

Hog Tied: If the sum of both players' scores ends in a seven (e.g., 17, 27, 57), then the current player can roll at most once.

Hog Wild: If the sum of both players' scores is a multiple of seven (e.g., 14, 21, 35), then the current player rolls four-sided dice instead of the usual six-sided dice.

Free Bacon: If a player chooses to roll zero dice, she scores one more than the tens digit of her opponent's score. E.g., if the first player has 32 points, the second player can score four by rolling zero dice. If the opponent has fewer than 10 points (tens digit is zero), then the player scores one.
