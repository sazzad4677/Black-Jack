# Blackjack Game 🎲🃏  

A simple command-line Blackjack game written in Python.

## 📌 Description  
This is a Python-based game of **Blackjack** where the user plays against the computer (dealer). The game follows standard Blackjack rules:  

- The goal is to get as close to **21** as possible without going over.
- **Face cards (J, Q, K)** are worth **10 points**.
- **Aces (A)** can be worth **11 or 1**, depending on what benefits the player.
- If a player gets **Blackjack (an Ace and a 10-point card on the first draw)**, they win automatically.
- The dealer must draw cards until they reach **17 or higher**.
- The game continues until either the player or dealer wins or busts.

## 🚀 How to Play  
1. Run the script in a Python environment.  
2. You'll be asked if you want to play a round of Blackjack (`y/n`).  
3. Each player is dealt **two** random cards.  
4. The player can choose to **hit (draw another card)** or **stand (keep their current hand)**.  
5. The dealer plays after the player stops drawing cards.  
6. The winner is determined based on Blackjack rules.  

## 🛠 Requirements  
- Python 3.x  
- `art` module (for displaying the game logo)  

### Install Dependencies  
If you don’t have the `art` module, install it using:  
```bash
pip install art
```

## 📜 Code Overview  
- `deal_card()`: Returns a random card from a predefined deck.  
- `calculate_score()`: Calculates the score of a given hand and checks for Blackjack.  
- `compare()`: Compares the scores of the player and dealer to determine the winner.  
- `play_game()`: Handles the game logic, including card dealing, user input, and score evaluation.  

## 🎮 Play the Game  
To start playing, run:  
```bash
python blackjack.py
```

## ✨ Example Gameplay  
```
Do you want to play blackjack? (y/n): y

Your cards: [10, 7], current score: 17
Computer first card: 9
Do you want to deal another card? (y/n): n

Your final hand: [10, 7], final score: 17
Computer's final hand: [9, 10], final score: 19
You lost
```

Enjoy playing! 😃🎲♠️