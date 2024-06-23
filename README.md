Blackjack Game
This project is a simple implementation of a Blackjack game using Python. The game allows a user to play a simplified version of Blackjack against the computer.

Getting Started
Prerequisites
Make sure you have Python installed on your system. This project does not require any external libraries.

Running the Game
Clone the repository to your local machine.
Navigate to the project directory.
Run the Python script to start the game.


How to Play
When the game starts, both the user and the computer are dealt two cards each.
The user's cards and the computer's first card are displayed.
The user can choose to either draw another card ('y') or pass ('n').
If the user draws a card and their total exceeds 21, they lose.
The computer will keep drawing cards until its total is 17 or higher.
The final scores are compared to determine the winner.
Game Rules
Number cards (2-10) are worth their face value.
Face cards (Jack, Queen, King) are each worth 10 points.
Aces can be worth 11 or 1 point, whichever is more beneficial without busting (going over 21).
A hand with an Ace and a 10-value card is called a "Blackjack" and is the highest hand.
If both the user and the computer have the same score, the game is a draw.
If the user or the computer exceeds 21 points, they lose.
Code Explanation
deal_card()
This function randomly selects a card from a standard deck of cards (excluding suits) and returns its value.

calculate_score(cards)
This function calculates the total score of a given hand of cards. If the hand contains an Ace and the total score exceeds 21, the Ace is counted as 1 instead of 11. If the hand is a Blackjack (an Ace and a 10-value card), it returns 0.

compare(user_score, computer_score)
This function compares the user's score with the computer's score and returns the result of the game.

Main Game Loop
The game starts by dealing two cards to both the user and the computer.
The user is then prompted to draw another card or pass.
The computer draws cards until its total score is 17 or higher.
The final scores are displayed, and the result of the game is announced.
Example
plaintext
Copy code
Your cards: [10, 7], current score: 17
Computer's first card: 9
Type 'y' to get another card, type 'n' to pass: n
Your final hand: [10, 7], final score: 17
Computer's final hand: [9, 8], final score: 17
Draw
Contributing
Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy the game!
