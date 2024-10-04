# Blackjack_game


I implemented a simple text-based game that simulates the popular card game. The game is structured to allow the player to make strategic decisions while keeping track of wins and losses against the dealer.

The game begins by initializing key variables such as player and dealer scores, win counters, and game state flags. Upon starting a new game, the player is dealt a card, and their score is updated accordingly. A set of options is presented to the player, allowing them to either draw another card, hold their hand, view statistics, or exit the game. To enhance the user experience, input validation is in place to ensure that player choices are within acceptable bounds.

One key strategy in the game is the decision-making process when the player chooses to "hit" and draw additional cards. The player can draw cards until they either reach a score of 21 (Blackjack) or exceed 21, resulting in a loss. If the player decides to "hold," the dealer reveals their score, and the winner is determined based on the final scores. This approach reflects the classic rules of Blackjack, providing players with familiar gameplay mechanics.

The game also incorporates statistical tracking, allowing players to view their performance metrics, including the number of wins, losses, ties, and overall game statistics. This feature encourages strategic play by providing insights into player performance over time.

Overall, this Blackjack project serves as a practical application of programming concepts such as loops, conditionals, and user input handling, while also offering a fun and interactive gaming experience.
