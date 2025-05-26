# Follower_Guessing_Game
🔢 Follower Guessing Game
A fun command-line game where you guess who has more Instagram followers between two celebrities, brands, or influencers.

📌 Overview
This game is inspired by the "Higher-Lower" format and built using Python. In each round, you're shown two accounts and must guess which one has more followers. If you're correct, your score increases and the game continues. The game ends when you guess incorrectly.

This project is great for learning:

Conditional logic

Loops

Function structuring

Working with dictionaries and lists

Importing and using modules

📁 Project Structure
.
├── main.py         # Main game logic
├── art.py          # ASCII art for game visuals (logo and vs symbol)
├── game_data.py    # Data for accounts (names, follower counts, etc.)

🎮 How to Play
Run the main.py file.

Compare two Instagram accounts.

Type A or B to guess who has more followers.

If you're right, your score increases and the game continues.

The game ends when your guess is incorrect.

Note: Each round replaces the previous B with the new A to keep the game dynamic and avoid repetition.

✨ Features
Randomized choices each round

Clears screen for a clean user experience

Modular structure for easy editing

ASCII art for better UI

Dynamic score tracking

✅ Requirements
Python 3.x

replit module (optional — used for clearing the screen in Replit environments)

📦 Note
If you're running this outside of Replit, you may replace from replit import clear with:

import os
def clear():
    os.system('cls' if os.name == 'nt' else 'clear')

📜 License
This project is licensed under the MIT License.

