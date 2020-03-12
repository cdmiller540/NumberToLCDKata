# Yahtzee Kata
## Problem Description (Part 1)

**DO NOT READ ON TO PART 2**


The game of yahtzee is a simple dice game. Each round, each player rolls five six sided dice. The player may choose to reroll some or all of the dice up to three times (including the original roll). The player then places the roll at a category, such as ones, twos, sixes, pair, two pairs etc. If the roll is compatible with the score, the player gets a score for this roll according to the rules. If the roll is not compatible, the player gets a score of zero for this roll.

Create a solution to score a given roll and a category. The solution should output the score for this roll. The possible categories are listed below. **Make sure your solution is well tested**

### Yahtzee rules description and suggested test cases

The following categories exists:

* Ones, Twos, Threes, Fours, Fives, Sixes: The player scores the sum of the dice that reads one, two, three, four, five or six, respectively. For example, 1, 1, 2, 4, 4 placed on “fours” gives 8 points.
* Pair: The player scores the sum of the two highest matching dice. For example, 3, 3, 3, 4, 4 placed on “pair” gives 8.
* Large straight: If the dice read 2,3,4,5,6, the player scores 20 (the sum of all the dice), otherwise 0.
* Yahtzee: If all dice are the have the same number, the player scores 50 points, otherwise 0.
* Chance: The player gets the sum of all dice, no matter what they read.

## Part 2
Update your solution from Part 1 to support two new categories:
* Four of a kind: If there are four dice with the same number, the player scores the sum of these dice. Otherwise, the player scores 0. For example, 2, 2, 2, 2, 5 places on “four of a kind” gives 8.
* Full house: If the dice are two of a kind and three of a kind, the player scores the sum of all the dice. For example, 1,1,2,2,2 placed on “full house” gives 8. 4,4,4,4,4 is not “full house”.
