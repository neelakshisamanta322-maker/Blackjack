🃏 Blackjack Game (Console Version)

A fully interactive Python Blackjack game that runs in the terminal.
This project simulates real Blackjack rules, includes ASCII-art style card visuals, handles Aces intelligently, and provides a complete player vs. dealer experience.

blackjackgame

⭐ Features

🎴 Visual ASCII card display for both player and dealer

🧮 Ace value handling (1 or 11 automatically adjusted)

🃟 Full 52-card deck with suits (♥ ♦ ♣ ♠)

🔄 Real Blackjack mechanics:

Player Hit / Stand

Dealer auto-plays (hits until score ≥17)

Blackjack recognition

Bust detection

🎮 Smooth game flow with interactive inputs

🧹 Automatic screen clearing during gameplay

🧠 Uses OOP (Card class) and functions for clean structure

🎮 Gameplay Overview
1. Game Start

The game prints title banners and instructions.

A deck of 52 cards is created using init_deck().

2. Dealing Cards

Both player and dealer receive 2 cards.

One dealer card is hidden (classic Blackjack style).

3. Player Turn

Player chooses:

H → Hit (draw card)

S → Stand (keep score)

Ace values are dynamically adjusted to prevent busting.

4. Dealer Turn

Dealer reveals hidden card.

Dealer must hit until their score reaches 17 or above.

Dealer busting results in an automatic player win.

5. Win Conditions

The script checks:

Player Blackjack

Dealer Blackjack

Player bust

Dealer bust

Score comparison

Tie (push)

🧱 Code Structure
Classes
Card

Represents an individual playing card with:

card_face (A, 2–10, J, Q, K)

value (numerical value for Blackjack)

symbol (Unicode suit symbol)

Functions

show_cards() → Renders ASCII art cards

deal_card() → Picks and removes a random card from deck

play_blackjack() → Main gameplay loop

init_deck() → Creates the full 52-card deck

▶️ Running the Game

Make sure you have Python 3 installed.

python blackjackgame.py

📁 File Included

blackjackgame.py — Full Blackjack game logic # Blackjack
This project simulates real Blackjack rules, includes ASCII-art style card visuals, handles Aces intelligently, and provides a complete player vs. dealer experience.
