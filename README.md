# Hangman Game (Python)

A simple, command-line version of the classic guessing game, Hangman. This project serves as a great introduction to basic Python concepts like loops, conditional statements, lists, and string manipulation.

## 🎯 How to Play

The game selects a **secret word** randomly from a predefined list.
You are given a limited number of **guesses** (e.g., 6 or 7).
1.  Enter a single letter guess.
2.  If the letter is in the word, it will be revealed in all its correct positions.
3.  If the letter is **not** in the word, you lose a guess.
4.  The game ends when you either guess the entire word (Win!) or run out of guesses (Game Over!).

## ✨ Features

* **Random Word Selection:** A different word is chosen for each game.
* **Guess Tracking:** Keeps track of letters already guessed to prevent duplicates.
* **Lives/Attempts Counter:** Clear feedback on remaining attempts.
* **Simple Command Line Interface (CLI):** Easy to play directly in the terminal.

## 🚀 Setup and Running the Game

### Prerequisites

* **Python 3.x** (Required to run the script)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone  https://github.com/jtina12/Hangman-game.git

    cd hangman-python
    ```
2.  **Run the script:**
    ```bash
    python hangman.py
    ```
    

## 🤝 Acknowledgements

This implementation was inspired by or based on a tutorial from **GeeksforGeeks**.
