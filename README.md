# UnoAgent
RLCard documentation - https://rlcard.org/rlcard.games.uno.html

Uno tournament rules(not yet implemented, ignore for now) - http://www.tournaments.cleverclark.com/Tournaments/images/Uno%20Clark%20Rules.pdf

To play as player:
Choose the integer value assigned to each move, not the number affiliated with the card
EX: 
======== Actions You Can Choose =========
0: 9, 1: 6, 2: 4
Choose 0, 1, or 2

State contents:
Example: {'hand': ['r-6', 'y-draw_2', 'y-9', 'g-7', 'g-3', 'b-8', 'r-5'], 'target': 'g-2', 'played_cards': ['g-2'], 'legal_actions': ['g-7', 'g-3'], 'num_cards': [7, 7], 'num_players': 2, 'current_player': 0}
hand - the cards in current players hand
target - the top of the discard pile
played_cards - card that have been played this game
legal_actions - legal actions for turn
num_players - number of players in the game
current_player - current player (0= player 1; 1= player 2; etc...)
