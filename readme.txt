Description of the Snake, Water, Gun Game in Python
The Snake, Water, Gun game is a fun, Python-based command-line game inspired by the classic "Rock, Paper, Scissors." In this game, a player competes against the computer by selecting one of three choices: Snake, Water, or Gun. Each choice interacts differently with the others, leading to unique outcomes based on a set of simple rules:

Snake drinks Water but is defeated by Gun.
Water douses Gun but is drunk by Snake.
Gun kills Snake but is defeated by Water.
Game Rules
Choices: The player inputs a choice of either "Snake," "Water," or "Gun" in each round.
Computer Choice: The computer randomly selects one of the three choices.
Outcomes:
If both the player and computer make the same choice, it's a tie.
Otherwise, the winner is determined by the interactions:
Snake wins against Water, loses to Gun.
Water wins against Gun, loses to Snake.
Gun wins against Snake, loses to Water.
Scoring and Winning
The game consists of a set number of rounds, chosen by the player at the start.
After each round, the scores are updated:
Player wins: Player gets a point.
Computer wins: Computer gets a point.
Tie: No points awarded.
At the end of all rounds, the total scores determine the overall winner.