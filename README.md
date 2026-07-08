🃏 Blackjack Game (Python)

A simple command-line Blackjack game built in Python. Play against the computer dealer — try to get as close to 21 as possible without going over!

How to Play


Run the script:


bash   python blackjack.py


You and the computer are each dealt 2 cards. You can see all of your cards, but only the computer's first card.
Type y to draw another card ("hit"), or n to stop ("stand").
The computer will keep drawing cards until its score is 17 or higher.
The final scores are compared and a winner is announced.


Rules


Card values:

Number cards (2–10) are worth their face value.
Jack, Queen, King are all worth 10.
Ace is worth 11, but automatically counts as 1 if needed to avoid busting.



A 2-card hand totaling 21 is a Blackjack — an automatic win (unless both players get one, which is a draw).
Going over 21 is a bust — an automatic loss.
If both scores are equal, it's a draw.


Example Output

Your cards: [10, 7], current score: 17
Computer's first card: 9
Type 'y' to get another card, type 'n' to pass: n
Your final hand: [10, 7], final score: 17
Computer's final hand: [9, 6, 5], final score: 20
You lose

Requirements


Python 3.x
No external libraries needed (uses only the built-in random module)


File Structure

blackjack-game/
├── blackjack.py    # Main game script
└── README.md       # Project documentation

License

Feel free to use, modify, and share this project.
