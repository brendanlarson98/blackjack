# blackjack

Here we have an implementation of the game blackjack in Python.

Overall flow:
We randomly assign the dealer (computer) and human player cards from our dictionary deck. While our player's score is below 21 and wants to be dealt, we will continue to deal and calculate the score. For simplicity, I've left aces to be a score of 11. Once the player has stayed their hand, our computer is dealt until they reach a score of at least 16. If neither player has busted, we compare scores to see who is closer to 21 (dealer wins on ties)
